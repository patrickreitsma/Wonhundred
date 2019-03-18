<template>
  <nav>
    <div class="update">
      <span class="updatetext">
        We have updated our sustainable initiatives -- READ MORE
      </span>
    </div>
    <ul class="nav">
      <li class="navbtn search">
        <img class="navbtn glass" src="../static/glass.png" height="1024" width="1024"/>
        <p class="navtextsearch">
          Search
        </p>
      </li>
      <li class="logo">
        <img class="logotext nav" src="../static/nav.png"/>
        <h3 class="logotext">WON HUNDRED</h3>
        <img class="logotext cart" src="../static/cart2.png" />
      </li>
      <li class="navbtn right">
        <p class="navtext">
          Shopping Bag (0)
        </p>
      </li>
    </ul>
    <ul class="nav twee">
      <li class="navbtn journal">
        <p class="navtextjournal">
          Journal
        </p>
      </li>
      <li class="navbtn women">
        <p class="navtextwomen">
          Women
        </p>
      </li>
      <li class="navbtn men">
        <p class="navtextmen">
          Men
        </p>
      </li>
      <li class="navbtn currency">
        <p class="navtextcurrency">
          Currency
        </p>
      </li>
    </ul>
  </nav>
</template>

<style scoped lang="scss">
  .nav {
    display: flex;
    flex-wrap: wrap;
    padding: 0;
    list-style: none;
    background-color: #ffffff;
    width: auto;
  }
  .logo {
    width: 100%;
    order: -1;
    border: $border;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }
  .logotext{
    display: flex;
    align-items: center;
    height: 100%;
  }
  .logotext.cart{
    width: 44px;
    height: 100%;
    align-self: center;
    border-left: $border;
  }
  .logotext.nav {
    width: 46px;
    height: 100%;
    border: none;
    border-right: $border;
    align-self: center;
  }
  .navbtn {
    border: $border;
    justify-content: center;
    width: 50%;
    display: flex;
    flex-wrap: wrap;
    height: 3rem;
    align-items: center;
    font-weight: bold;
  }
  .navbtn.glass {
    height: 15px;
    width: 15px;
    border: none;
    margin-left: 0.6rem;
  }
  .navbtn.search {
    height: 40px;
    width: 100%;
    padding-left: 2%;
    order: 0;
    align-content: center;
    justify-content: flex-start;
    border-top: none;
    border-bottom: none;
    font-weight: lighter;
  }
  .navtextsearch {
    padding-left: 0.5rem;
  }
  .navbtn.women {
    order: -1;
    border-right: none;
    border-bottom: none;
  }
  .navbtn.men {
    order: 0;
    border-bottom: none;
  }
  .navbtn.journal{
    order: 1;
    border-right: none;
  }
  .navbtn.currency {
    order: 1;
  }
  .navbtn.right,
  .update,
  .updatetext {
    display: none;
  }
  @include breakpoint(md) {
    .logotext{
      font-size: 1.25rem;
      font-weight: bold;
    }
    .navbtn.glass {
      margin-left: 0.9%;
    }
    .navbtn.search {
      padding-left: 1%;
    }
  }
  @media only screen and (min-width: 1024px) {
    .navbtn.glass,
    .logotext.nav,
    .logotext.cart {
      display: none;
    }
  }
  @include breakpoint(l) {
    .navbtn.right,
    .update,
    .updatetext {
      display: block;
    }
    .update {
      padding: 0;
      background-color: #3e6c15;
      height: 40px;
      display: flex;
      justify-content: center;
      align-items: center;
      .updatetext {
        color: #fff;
      }
    }
    .nav,
    .nav2{
      background-color: #ffffff;
      width: auto;
      height: 60px;
    }
    .nav2 {
      border-bottom: $border;
    }
    .navbtn {
      width: 25%;
      height: 100%;
    }
    .navbtn.search {
      width: 25%;
      order: -1;
      border: $border;
      border-bottom: none;
      height: 100%;
      padding: 0;
      justify-content: center;
      font-weight: bold;
    }
    .navbtn.right {
      border-left: $border;
      border-bottom: none;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .navbtn.journal {
      border-left: none;
    }
    .navbtn.men,
    .navbtn.women{
      border-bottom: $border;
    }
    .logo {
      font-size: 2rem;
      font-weight: bolder;
      width: 50%;
      height: 100%;
      justify-content: center;
      align-items: center;
      border-left: none;
      border-right: none;
      border-bottom: none;
    }
  }
</style>
