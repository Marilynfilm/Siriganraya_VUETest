<template>
  <div>
    <img alt="FilmPic" src="./assets/film.jpg" />
    <p>Name: {{ myname.Name }} {{ myname.Surname }}</p>
    <p>Nickname: {{ myname.Nickname }}</p>
    <p>Age: {{ myname.Age }}</p>
    <p>University: {{ myname.University }}</p>
  </div>
</template>

<script>
export default {
  data: () => ({
    myname: [
      { Name: "Siriganraya" },
      { Surname: "Chandee" },
      { Nickname: "Film" },
      { Age: "21" },
      { University: "RMUTR" },
    ],
  }),
};
</script>

<style lang="less" scoped>
p {
  font-size: 13pt;
}
img {
  width: 60%;
  margin-left: 20%;
}
</style>