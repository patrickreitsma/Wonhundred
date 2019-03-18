<template>
  <div class="main">
    <div class="greendiv">
      <img class="greencross" alt="greencross" src="https://cdn.shopify.com/s/files/1/0092/9605/2282/articles/lookbook-blog_1080x.jpg?v=1551172618">
      <div class="greentext">
        <h1 class="titlegreencross">
          Spring Summer 19 Lookbook
        </h1>
        <p class="textgreencross">
          This season’s collection marks the beginning of an inspiring journey to reunite with everyone’s inner rebel. Dress code: exciting but disciplined, joyful in its formal silhouette. Get inspired through this season's lookbook and shop your favourite looks.
          <br> <br><i>All looks are continuously updated along with new arrivals in our...</i>
        </p>
        <p class="buttongreencross">
          <br>Read post-->
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.greendiv {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
}
.greencross{
  height: auto;
  width: 100%;
  order: 0;
  align-self: flex-start;
}
.greentext {
  width: 100%;
  order: 1;
}
.titlegreencross{
  width: 100%;
  font-size: 1.9rem;
  font-weight: bolder;
  text-align: left;
  margin-top: 4rem;
  margin-bottom: 1.8rem;
}
.textgreencross {
  text-align: left;
  font-size: 0.8125rem;
}
.buttongreencross{
  font-weight: bold;
  font-size: 0.9375rem;
  display: flex;
  justify-content: flex-end;
  padding: 10% 0 2% 0;
}
@include breakpoint(md) {
  .titlegreencross{
    margin: 4% 0 4% 0;
  }
  .buttongreencross{
    font-weight: bold;
    font-size: 1.25rem;
    display: flex;
    justify-content: flex-end;
    padding: 10% 0 0 0;
  }
}
@include breakpoint(l) {
  .greendiv {
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
  }
  .greencross {
    width: 50%;
    height: auto;
    order: 0;
    align-self: flex-start;
  }
  .titlegreencross {
    width: auto;
    font-size: 3.875rem;
    transform: translate(-8%,-7%);
    padding: 15% 0 10% 0;

  }
  .textgreencross {
    font-size: 0.9375rem;
    text-align: start;
    margin-left: 15%;
  }
  .buttongreencross {
    margin-left: 15%;
    align-self: flex-start;
    font-size: 1.25rem;
  }
  .greentext {
    width: 50%;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
  }
}
</style>
