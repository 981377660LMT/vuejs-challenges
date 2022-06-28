<!--info-header-start--><h1>v-focus <img src="https://img.shields.io/badge/-medium-d9901a" alt="medium"/> <img src="https://img.shields.io/badge/-%23Directives-999" alt="#Directives"/></h1><blockquote><p>By webfansplz <a href="https://github.com/webfansplz" target="_blank">@webfansplz</a></p></blockquote><p><a href="https://sfc.vuejs.org/#eyJBcHAudnVlIjoiPHNjcmlwdCBzZXR1cCBsYW5nPSd0cyc+XG5pbXBvcnQgeyByZWYgfSBmcm9tIFwidnVlXCJcblxuY29uc3Qgc3RhdGUgPSByZWYoZmFsc2UpXG5cbi8qKlxuICogSW1wbGVtZW50IHRoZSBjdXN0b20gZGlyZWN0aXZlXG4gKiBNYWtlIHN1cmUgdGhlIGlucHV0IGVsZW1lbnQgd2lsbCBmb2N1cy9ibHVyIHdoZW4gdG9nZ2xlIGBzdGF0ZWAgYXV0b21hdGljYWxseVxuICpcbiovXG5cbmNvbnN0IFZGb2N1cyA9IHtcblxufVxuXG5zZXRJbnRlcnZhbCgoKSA9PiB7XG4gIHN0YXRlLnZhbHVlID0gIXN0YXRlLnZhbHVlXG59LCAyMDAwKVxuXG48L3NjcmlwdD5cblxuPHRlbXBsYXRlPlxuICA8aW5wdXQgdi1mb2N1cz1cInN0YXRlXCIgdHlwZT1cInRleHRcIj5cbjwvdGVtcGxhdGU+XG4ifQ==" target="_blank"><img src="https://img.shields.io/badge/-Take%20the%20Challenge-213547?logo=vue.js&logoColor=42b883" alt="Take the Challenge"/></a> &nbsp;&nbsp;&nbsp;<a href="./README.zh-CN.md" target="_blank"><img src="https://img.shields.io/badge/-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-gray" alt="简体中文"/></a> </p><!--info-header-end-->


For this challenge, we'll start write custom directive. Let's start with `v-focus` 👇: 

```ts
<script setup lang='ts'>
import { ref } from "vue"

const state = ref(false)

/**
 * Implement the custom directive
 * Make sure the input element will focus/blur when toggle `state` automatically
 *
*/

const VFocus = {

}

setInterval(() => {
  state.value = !state.value
}, 2000)

</script>

<template>
  <input v-focus="state" type="text">
</template>

```

Click the `Take the Challenge` button to start coding! Happy Hacking!
