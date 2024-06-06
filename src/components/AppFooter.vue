
<script>
export default {
    name: 'AppFooter'
};
</script>

<template>
    <footer>
        <div class="container">
          <div>
            <p>Boolando s.r.l</p>
            <p>informazioni legali</p>
          </div>
          <div>
            <p>Trovaci anche su</p>
            <p></p>
          </div>
        </div>

    </footer>

</template>

<style scoped lang="scss">
  footer {
    background-color: black;
    height: 100px;
    position: fixed;
    bottom: 0;
    left: 0;
    right: 0;
  } footer .container {
    display: flex;
    justify-content: space-between;
  } footer p {
    color: white;
  } footer > div p:first-child {
    font-weight: 600;
    margin-top: 30px;
  }
</style>