<template>
  <Nav />

  <div class="posts">
    <div class="main-post">
      <div class="texts">
        <span class="timestamp">2099-12-31 23:08</span>
        <h1>디스코드 새로운 언론사 등장</h1>
        <p>디스코드에 새로운 언론사가 등장하였다. 이름은 Discord News이고, 한국인 운영자가 운영하고 있다. 많은 사람들이 이에 대해 긍정적인 의견을 보내고 있으며, 운영사는 이러한 상황에 많은 성원에 감사를 표하고 부족한 점이 많으니 피드백을 부탁한다는 말을 남겼다.</p>
        <a>더 알아보기 ></a>
      </div>
      <img src="../assets/backbg.png" width="250px">
    </div>
  </div>
</template>

<script>
import Nav from '../components/Nav.vue'

export default {
  name: 'Index',
  components: {
    Nav,
  }
}
</script>

<style>
.posts {
  padding: 80px 30%;
}

.main-post {
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
}

.main-post h1 {
  margin-top: 0;
}

.main-post img {
  margin-left: 20px;
  border-radius: 30px;
}

.main-post .timestamp {
  font-size: 12px;
}

.posts a {
  text-decoration: none;
 color: #909090;
}
</style>