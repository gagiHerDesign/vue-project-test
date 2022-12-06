<template lang="pug">
#home
  img(:src="principal")
  br
  p
    |Bahashishi「オアシス」（2007年9月5日發售）
    br
    |Bahashishi「約束」（2007年11月14日發售）
    br
    | Bahashishi「キセキ」（2008年2月13日）
    br
    |「Do You Ever Shine?」（2014年6月4日發售）
</template>

<script setup>
// 如果圖片 src 是綁定本機圖片，不能直接寫路徑
// const principal = '@/assets/0104.jpg'
const principal = new URL('@/assets/kkk.png', import.meta.url).href
</script>
