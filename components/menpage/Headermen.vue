<template>
  <header>
    <h1>Men's New Arrival</h1>
    <ul class="color">
      <li>All colours</li>
      <li>Black</li>
      <li>Blue</li>
      <li>Brown</li>
      <li>Green</li>
      <li>Grey</li>
      <li>Multi</li>
      <li>Neutrals</li>
      <li>Pink</li>
      <li>Red</li>
      <li>White</li>
      <li>Yellow</li>
    </ul>
    <span class="sort">
      <p class="allcolours">All Colours ></p>
      <p class="Sort">Sort ></p>
    </span>
  </header>
</template>

<style scoped lang="scss">
  h1 {
    font-size: 1.875rem;
    text-align: center;
    width: 100%;
  }
  .sort {
    margin-top: 3rem;
    display: flex;
    justify-content: space-between;
    width: 100%;
    p {
      @include header-content-men;
      font-weight: normal;
    }
  }
  .color {
    display: none;
  }
  /*Width 768px*/
  @include breakpoint(md) {
    p {
      font-size: 0.75rem;
    }
  }
  /*width 1024px*/
  @include breakpoint(l) {
    .allcolours {
      display: none;
    }
    h1 {
      @include primary-header;
    }
    .color {
      @include header-content-men;
      display: flex;
      justify-content: space-around;
      align-items: center;
      width: 100%;
      height: 80px;
    }
    .sort {
      @include header-content-men;
      display: flex;
      justify-content: flex-end;
      margin: 0;
    }
  }
</style>
