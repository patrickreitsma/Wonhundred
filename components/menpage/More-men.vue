<template>
  <div class="buttons">
    <button class="button previous">Previous Page</button>
    <button class="button number">1 2 3 4</button>
    <button class="button next">Next Page</button>
  </div>
</template>

<style scoped lang="scss">
  .buttons {
    height: 110px;
    display: flex;
    flex-wrap: wrap;
    color: white;
  }
  .button {
    @include buttonmobile;
    background-color: white;
  }
  .button.previous {
    font-weight: lighter;
    color: #808080;
  }
  .button.number {
    display: none;
  }
  /*Width 1024px*/
  @include breakpoint(l) {
    .buttons {
      border-bottom: $border;
      margin-bottom: 10%;
    }
    .button {
      @include buttonipad;
    }
    .button.previous {
      border-left: $border;
    }
    .button.next {
      border-right: $border;
    }
    .button.number {
      display: flex;
    }
  }
</style>
