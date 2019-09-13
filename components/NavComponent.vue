<template>
  <nav class="navigation">
    <div class="nav-logo">
      <figure>
        <img src="../assets/img/petdoctor-logo-green.png" alt>
      </figure>
    </div>
    <ul class="nav-main">
      <li class="nav-item">
        <a href="http://" target="_blank" rel="noopener noreferrer">Nav</a>
      </li>
      <li class="nav-item">
        <a href="http://" target="_blank" rel="noopener noreferrer">Nav</a>
      </li>
      <li class="nav-item">
        <a href="http://" target="_blank" rel="noopener noreferrer">Nav</a>
      </li>
      <li class="nav-item">
        <a href="http://" target="_blank" rel="noopener noreferrer">Nav</a>
      </li>
      <li class="nav-item">
        <a href="http://" target="_blank" rel="noopener noreferrer">Nav</a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.navigation {
  height: 100px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-left: 50px;
  padding-right: 50px;
  padding-top: 5px;
  padding-bottom: 5px;
  -webkit-box-shadow: 0px 6px 5px -6px rgba(0, 0, 0, 0.75);
  -moz-box-shadow: 0px 6px 5px -6px rgba(0, 0, 0, 0.75);
  box-shadow: 0px 6px 5px -6px rgba(0, 0, 0, 0.75);
  position: sticky;

  .nav-logo {
    img {
      height: 90px;
    }
  }

  .nav-main {
    display: flex;

    .nav-item {
      list-style-type: none;
      padding: 15px;

      a {
        color: #000;
        text-decoration: none;
        font-size: 20px;
      }
    }
  }
}
</style>



