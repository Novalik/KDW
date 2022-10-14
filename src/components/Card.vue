<template>
  <div class="card p-5 m-10 rounded-lg w-[500px] h-[200px] bg-neutral-800 flex items-center justify-center">
    <img class="w-40 h-40 object-cover rounded-lg mr-5" src="../assets/backbg.png" />
    <div class="ml-2">
      <div class="title text-neutral-200 mb-2 text-lg">"프론트 노동" 열일하는 개발자 디아</div>
      <div class="content text-neutral-500">개발자인 디아는 스네 위키 개발을 위해 프론트 개발을 하고 있습니다, 개발자인 디아는 스네 위키 개발을 위해 프론트 개발을 하고 있습니다</div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Card'
}
</script>

<style scoped>
  .content {
    /* 한 줄 자르기 */
    display: inline-block;
    width: 280px;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;

    /* 여러 줄 자르기 추가 스타일 */
    white-space: normal;
    line-height: 1.2;
    height: 3.6em;
    text-align: left;
    word-wrap: break-word;
    display: -webkit-box;
    -webkit-line-clamp: 3;
    -webkit-box-orient: vertical;
  }
</style>
