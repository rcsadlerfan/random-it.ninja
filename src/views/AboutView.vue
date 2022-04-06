<template>
    <div class="space-y-16 pr-72 pb-20">
        <WorkExperience />
        <Skills />
        <Organizations />
    </div>
</template>

<script>
import WorkExperience from '../components/WorkExperience.vue';
import Skills from '../components/Skills.vue';
import Organizations from '../components/Organizations.vue';

export default {
    name: 'AboutView',
    components: {
        WorkExperience,
        Skills,
        Organizations
    }
}
</script>