<template>
  <div class="row">
    <div class="column">
      <p>SOFT SKILLS</p>
      <p>ทักษะในการปรับตัว : 100%</p>
      <p>ทักษะในการเรียนรู้สิ่งใหม่ : 100%</p>
      <p>ทักษะในการคิดบวก : 100%</p>
      <p>ทักษะในการทำงานเป็นทีม : 100%</p>
      <p>ทักษะในการแก้ปัญหา : 100%</p>
    </div>
    <div class="column">
      <p>HARD SKILLS</p>
      <p>HTML : 80%</p>
      <p>C# : 80%</p>
      <p>PHP : 60%</p>
      <p>CSS : 60%</p>
    </div>
  </div>
  <button @click="goToContact()">Contact</button>
</template>

<script>
export default {
  methods: {
    goToContact() {
      this.$router.push("/contact");
    },
  },
};
</script>

<style lang="less" scoped>
p {
  font-size: 13pt;
}
* {
  box-sizing: border-box;
}
.column {
  float: left;
  width: 50%;
  padding: 10px;
  height: 300px;
}
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>