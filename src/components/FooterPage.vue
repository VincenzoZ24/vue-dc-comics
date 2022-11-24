<template>
  <footer>
    <div class="container_list_footer">
      <ul>
        <h5>DC COMICS</h5>
        <li>COMICS</li>
        <li>COMICS</li>
        <li>COMICS</li>
        <li>COMICS</li>
        <li>COMICS</li>
        <li>COMICS</li>
        <li>COMICS</li>
        <li>COMICS</li>
      </ul>
      <ul>
        <h5>DC</h5>
        <li>GAMES</li>
        <li>GAMES</li>
        <li>GAMES</li>
        <li>GAMES</li>
        <li>GAMES</li>
        <li>GAMES</li>
        <li>GAMES</li>
        <li>GAMES</li>
        <li>GAMES</li>
        <li>GAMES</li>
      </ul>
      <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
      </ul>
      <img src="@/img/dc-logo-bg.png" alt="">
    </div>
    <section>
      <div class="sign_up">
        <button>SIGN-UP NOW</button>
        <div class="social">
          <div>
            <h3>FOLLOW US</h3>
          </div>
          <img src="@/img/footer-pinterest.png" alt="">
          <img src="@/img/footer-periscope.png" alt="">
          <img src="@/img/footer-facebook.png" alt="">
          <img src="@/img/footer-twitter.png" alt="">
          <img src="@/img/footer-youtube.png" alt="">
        </div>
      </div>
    </section>
  </footer>
</template>

<script>
export default {
};
</script>

<style lang="scss" scoped>
footer{
  background-image: url("@/img/footer-bg.jpg");
  .container_list_footer{
    max-width: 1200px;
    margin: auto;
    padding-top: 2rem;
    display: flex;
    justify-content: space-between;
    height: 25rem;
    ul{
      color: white;
      h5{
        margin-bottom: 1rem
      }
      li{
        color: gray;
        font-size: 12px;
        list-style: none;
        margin-bottom: .5rem;
      }
    }
    img{
      width: 50%;
      object-fit: cover;
    }
  }
  section{
    background-color: rgb(60, 59, 59);
    .sign_up{
      max-width: 1200px;
      margin: auto;
      padding: 2rem;
      display: flex;
      justify-content: space-between;
      color: white;
      button{
        padding: 1rem;
        background-color: gray;
        border: 1px solid blue;
        color: white;
      }
      .social{
        display: flex;
        gap: 1rem;
        img{
          object-fit: contain;
        }
      }
    }
  }
}
</style>