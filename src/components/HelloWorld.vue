<template>
  <div class="brand-logo">
    <img class="dolan-img" alt="DolanLabs logo" src="../../src/assets/dolanwithtext-logo.png">
  </div>
  <nav class="navbar">
    <ul id="menu-list">
      <li>Team</li>
      <li>Kegiatan</li>
      <li>Kontak</li>
    </ul>
  </nav>
  <div class="content">
    <h1 class="hero">DolanLabs Community</h1>
    <p class="description">
      DolanLabs adalah komunitas non-profit yang mempelajari hal-hal terkait product development.
    </p>
    <button class="btn-join">Gabung DolanLabs</button>
  </div>
  <div class="illustration">
    <img src="../../src/assets/illustration.png" alt="" class="illustration-img">
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.dolan-img {
  position: absolute;
  width: 183.45px;
  height: 48px;
  left: 84px;
  top: 40px;
}
.navbar {
  position: sticky;
  width: 563px;
  height: 48px;
  left: 675px;
  top: 40px;
}
ul#menu-list li {
  display: inline;
  list-style-type: none;
  width: 47px;
  height: 24px;
  left: 0px;
  top: 0px;
  font-family: Poppins, Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 24px;
  color: #F8F9FF;
  margin: 0px 30px;
  text-decoration: none;
}
.hero {
  position: absolute;
  width: 491px;
  height: 61px;
  left: 84px;
  top: 293px;
  text-align: left;
  font-family: "Playfair Display", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 46px;
  line-height: 61px;
  color: #FFFFFF;
}
.description {
  position: absolute;
  width: 474px;
  height: 48px;
  left: 84px;
  top: 378px;
  text-align: left;
  font-family: Poppins, Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 24px;
  color: #FFFFFF;
}
.btn-join {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 12px 40px;
  position: absolute;
  width: 235px;
  height: 48px;
  left: 84px;
  top: 450px;
  background: #FFA24D;
  border-radius: 5px;
  font-family: Poppins, Helvetica, Arial, sans-serif;
  font-weight: bold;
}
.illustration {
  position: absolute;
  width: 500px;
  height: 500px;
  left: 680px;
  top: 172px;
}
</style>
