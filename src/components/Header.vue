<template>
    <div class="p-16 space-y-16">
        <div class="flex justify-center items-center space-x-24">
            <img src="/img/headshot.png" alt="Me" class="avatar mask mask-circle w-64 h-64">
            <div class="flex flex-col space-y-5 text-center">
                <h1 class="text-4xl font-bold">Ryan Carnovsky</h1>
                <p class="font-semibold italic">Systems Administrator &amp;&amp; Web Developer</p>
                <div class="flex justify-center space-x-5 mb-16">
                    <a href="https://github.com/rcsadlerfan" target="_blank">
                        <CodeIcon class="header-icon" />
                    </a>
                    <a href="https://twitter.com/RandomITNinja1" target="_blank">
                        <AtSymbolIcon class="header-icon" />
                    </a>
                    <!-- <a href="/docs/Resume.pdf" target="_blank">
                        <DocumentIcon class="header-icon" />
                    </a> -->
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import { CodeIcon, AtSymbolIcon, DocumentIcon } from '@heroicons/vue/solid'

export default {
    name: 'Header',
    components: {
        CodeIcon,
        AtSymbolIcon,
        DocumentIcon
    }
}
</script>