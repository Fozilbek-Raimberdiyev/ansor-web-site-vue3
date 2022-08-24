<template>
  <div>
    <NavBar></NavBar>
    <MainBanner></MainBanner>
    <FindCourse></FindCourse>
    <HowItWork></HowItWork>
    <OnlineCourses></OnlineCourses>
  </div>
</template>

<script>
import MainBanner from "@/components/mainBanner.vue";
import HowItWork from "../components/howItWork.vue";
export default {
    components: { MainBanner, HowItWork }
}
</script>
<style>
::-webkit-scrollbar {
  width: 7px;
}
::-webkit-scrollbar-track {
  background: #ccc;
}
::-webkit-scrollbar-thumb {
  background: #e9bc43;
  border-radius: 15px;
  border: 1px solid #ecb213;
}
.btn {
  outline: none;
  color: #fff;
}
</style>
