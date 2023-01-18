<template>
  <slot />
</template>

<script setup>
import * as Prism from 'prismjs'
import 'prismjs/plugins/diff-highlight/prism-diff-highlight'
// import 'prismjs/plugins/diff-highlight/prism-diff-highlight.css'
import 'prismjs/plugins/line-highlight/prism-line-highlight'
// import 'prismjs/plugins/line-highlight/prism-line-highlight.css'
import 'prismjs/plugins/line-numbers/prism-line-numbers'
import 'prismjs/plugins/line-numbers/prism-line-numbers.css'
import 'prismjs/components/prism-diff'
import 'prismjs/components/prism-apex'
// import 'prismjs/themes/prism-tomorrow.css'

onMounted(() => {
  Prism.highlightAll()
})
</script>
