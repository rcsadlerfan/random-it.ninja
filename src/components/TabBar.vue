<template>
    <div class="w-full mb-6">
        <div class="tabs flex justify-center">
            <RouterLink to="/" class="tab tab-bordered" :class="{'tab-active': active === 'about'}" @click="setActiveTab('about')">About</RouterLink>
            <RouterLink to="/" class="tab tab-bordered" :class="{'tab-active': active === 'blog'}" @click="setActiveTab('blog')">Blog</RouterLink>
        </div>
    </div>
</template>

<script>
import { RouterLink } from 'vue-router';

export default {
    name: 'TaabBar',
    data () {
        return {
            active: 'about'
        }
    },
    methods: {
        setActiveTab(tabName) {
            this.active = tabName;
        }
    },
    components: {
        RouterLink
    }
}
</script>