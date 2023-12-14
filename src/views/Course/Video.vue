<template>
  <div class="course_video_wrapper">
    课程视频已完成制作，单击下方链接确认下载。
  </div>
  <button class="submit_btn"  @click="next">下载课程视频</button>
  <button class="next_btn"  @click="next">进入下一页</button>
</template>

<script setup>

</script>

<style>
.submit_btn {
  width: 220px;
  line-height: 40px;
  color: #fff;
  background: tomato;
  outline: none;
  border: none;
  border-radius: 10px;
  cursor: pointer;
  margin-top: 20px;
}
.next_btn {
  width: 220px;
  line-height: 40px;
  color: #fff;
  background: tomato;
  outline: none;
  border: none;
  border-radius: 10px;
  cursor: pointer;
  margin-top: 207px;
}

</style>