<template>
  <div class="main">
    <div class="footer">
      <div class="footerbox1">
        <div class="newsletter">
          <p class="title news">
            Sign up to newsletter
          </p>
          <div class="email">
            <p class="emailtxt">
              Your E-mail
            </p>
          </div>
          <div class="gender left">
            <p class="gendertxt">
              Women
            </p>
          </div>
          <div class="gender">
            <p class="gendertxt">
              Men
            </p>
          </div>
        </div>
        <div class="footermenu">
          <p class="content">
            <b>Shopping</b><br>
            Gift Card<br>
            Terms & Conditions<br>
            Privacy Policy<br>
            Delivery<br>
            Payment<br>
            Returns<br>
            Account<br>
          </p>
          <p class="content twee">
            <b>Company</b><br>
            Contact<br>
            Sustainbility<br>
            About<br>
            Careers<br>
            Stores<br>
            Press<br>
            B2B<br>
          </p>
        </div>
      </div>
    </div>
    <div class="footerbox3">
      <p class="socialmedia">
        Instagram Facebook
        © 2018 Won Hundred
      </p>
    </div>
  </div>
</template>
<style scoped lang="scss">
  .footer {
    height: 100%;
    display: flex;
  }
  .footerbox1 {
    height: 500px;
    border: $border;
    width: 100%;
    display: flex;
    flex-wrap: wrap;
  }
  .title {
    display: flex;
    flex-wrap: wrap;
    font-weight: bold;
    font-size: 0.875rem;
    width: 100%;
    justify-content: center;
  }
  .title.news {
    margin-top: 2rem;
    height: 20px;
  }
  .newsletter {
    display: flex;
    width: 100%;
    flex-wrap: wrap;
    flex-direction: row;
    align-content: flex-start;
    margin-bottom: 2%;
  }
  .email {
    border: $border;
    height: 46px;
    width: 100%;
    margin: 0 5% 0 5%;
    display: flex;
    justify-content: flex-start;
    align-items: center;
  }
  .emailtxt {
    margin-left: 0.5rem;
    font-weight: lighter;
    font-size: 0.75rem;
  }
  .gender {
    width: 45%;
    height: 46px;
    border: $border;
    border-top: none;
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: bold;
  }
  .gender.left {
    margin-left: 5%;
    border-right: none;
  }
  .gendertxt {
    font-size: 0.875rem;
  }
  .footermenu {
    width: 100%;
    height: 239px;
    display: flex;
    flex-wrap: wrap;
    flex-direction: column;
    line-height: 2.5;
    margin-bottom: 2%;
  }
  .content {
    width: 43%;
    font-size: 13px;
    margin-left: 6%;
  }
  .content.twee {
    margin: 0;
    margin-right: 5%;
  }
  .footerbox3 {
    border: $border;
    border-top: none;
    margin-bottom: 1rem;
  }
  .socialmedia  {
    font-size: 0.8125rem;
    padding: 3%;
  }

  @include breakpoint(md) {
  }
  @include breakpoint(l) {
    .footerbox1 {
      height: 234px;
    }
    .newsletter {
      display: flex;
      flex-wrap: wrap;
      width: 50%;
      height: 100%;
      border-right: $border;
      margin: 0;
    }
    .title.news {
      justify-content: flex-start;
      margin: 3% 0 2% 4%;
    }
    .email {
      width: 40%;
      margin: 0 0 0 4%;
    }
    .gender {
      border-top: $border;
      width: 25%;
      margin: 0;
    }
    .gender.left {
      margin: 0;
      border-left: none;
    }
    .footermenu {
      width: 50%;
      height: 249px;
    }
    .content  {
      font-size: 0.9375rem;
      line-height: 1.5;
      height: 94%;
      width: 50%;
      margin: 0;
      padding: 3% 0 0 4%;
      text-align: left;
    }
    .content.twee {
      border-left: $border;
      padding: 3% 0 0 4%;
    }
    .footerbox3 {
      width: 100%;
      height: 40px;
      align-items: center;
      display: flex;
      justify-content: center;
    }
    .socialmedia {
      padding: 0;
    }
  }
</style>
