<!--info-header-start--><h1>计数器 <img src="https://img.shields.io/badge/-%E4%B8%AD%E7%AD%89-d9901a" alt="中等"/> <img src="https://img.shields.io/badge/-%23Composable%20Function-999" alt="#Composable Function"/></h1><blockquote><p>By webfansplz <a href="https://github.com/webfansplz" target="_blank">@webfansplz</a></p></blockquote><p><a href="https://sfc.vuejs.org/#eyJBcHAudnVlIjoiPHNjcmlwdCBzZXR1cCBsYW5nPSd0cyc+XG5cbmludGVyZmFjZSBVc2VDb3VudGVyT3B0aW9ucyB7XG4gIG1pbj86IG51bWJlclxuICBtYXg/OiBudW1iZXJcbn1cblxuLyoqXG4gKiBJbXBsZW1lbnQgdGhlIGNvbXBvc2FibGUgZnVuY3Rpb25cbiAqIE1ha2UgdGhlIGZ1bmN0aW9uIHdvcmsgZmluZVxuKi9cbmZ1bmN0aW9uIHVzZUNvdW50ZXIoaW5pdGlhbFZhbHVlID0gMCwgb3B0aW9uczogVXNlQ291bnRlck9wdGlvbnMgPSB7fSkge1xuXG59XG5cbmNvbnN0IHsgY291bnQsIGluYywgZGVjLCByZXNldCB9ID0gdXNlQ291bnRlcigwLCB7IG1pbjogMCwgbWF4OiAxMCB9KVxuXG48L3NjcmlwdD5cblxuPHRlbXBsYXRlPlxuICA8cD5Db3VudDoge3sgY291bnQgfX08L3A+XG4gIDxidXR0b24gQGNsaWNrPVwiaW5jXCI+XG4gICAgaW5jXG4gIDwvYnV0dG9uPlxuICA8YnV0dG9uIEBjbGljaz1cImRlY1wiPlxuICAgIGRlY1xuICA8L2J1dHRvbj5cbiAgPGJ1dHRvbiBAY2xpY2s9XCJyZXNldFwiPlxuICAgIHJlc2V0XG4gIDwvYnV0dG9uPlxuPC90ZW1wbGF0ZT5cbiJ9" target="_blank"><img src="https://img.shields.io/badge/-%E6%8E%A5%E5%8F%97%E6%8C%91%E6%88%98-213547?logo=vue.js&logoColor=42b883" alt="接受挑战"/></a> &nbsp;&nbsp;&nbsp;<a href="./README.md" target="_blank"><img src="https://img.shields.io/badge/-English-gray" alt="English"/></a> </p><!--info-header-end-->


在这个挑战中,我们将实现一个计数器. 👇: 


```ts
<script setup lang='ts'>

interface UseCounterOptions {
  min?: number
  max?: number
}

/**
 * 实现计数器函数,确保功能正常工作
 * 1. 加 (+)
 * 2. 减 (-)
 * 3. 重置 
 * 4. 最小值 & 最大值 选项支持
*/
function useCounter(initialValue = 0, options: UseCounterOptions = {}) {

}

const { count, inc, dec, reset } = useCounter(0, { min: 0, max: 10 })

</script>

```

点击上方的 `接受挑战` 开始编码 ！旅途愉快 ！
