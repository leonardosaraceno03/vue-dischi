<template>
  <header>
    <div>
        <img src="../assets/Spotify_logo_without_text.svg.webp" alt="logo">
    </div>
  </header>
</template>

<script>
export default {
}
</script>

<style  scoped lang="scss">
header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #2e3a46;
}
header > div > img{
    width: 100px;
    padding: 10px 20px;
}
</style>