<template>
  <section class="list">
    <div class="point-in-time side-to-side">
    <div class="image">
      <img src="blending-in-with-locals.JPG"/>
    </div>
      <div class="text-on-right text">
        <p>Chris blended right in</p>
      </div>
    </div>
    <div class="point-in-time">
      <div class="image">
        <img src="chris-confused.JPG"/>
      </div>
      <div class="text text-on-bottom">
        <p>Chris confused</p>
      </div>
    </div>
    <div class="point-in-time side-to-side">
      <div class="text text-on-left">
        <p>Chris hiding</p>
      </div>
      <div class="image">
        <img src="stone-wall-peekaboo.JPG"/>
      </div>

    </div>
  </section>
</template>

<script>

export default {
  components: {

  }
}
</script>

<style>
 .point-in-time{
  margin: 20px auto;
  padding:10px;
  border-radius: 3px;
  box-shadow: 1px 1px 2px #999;
  background-color: rgba(255, 228, 196, .3);
}
img{
  width: 100%;
}
p{
  display: block;
  font-family: Helvetica;
  font-size: 1.2em;
}
.side-to-side{
  display: flex;
  flex-direction: column;
}

@media screen and (min-width: 670px) {

  .list{
    min-height: 100vh;
    margin: 20px;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    text-align: center;

  }
  .point-in-time{
    border-radius: 3px;
    box-shadow: 1px 1px 2px #999;
    padding: 30px;
    border: 1px #999 solid;
    margin: 30px auto;
    background-color: rgba(255, 228, 196, .3);
  }
  .side-to-side{
    display: flex;
    flex-direction: row;
  }
  .text-on-right{
    min-width: 40%;
    padding-left: 2em;
  }
  .text-on-left{
    min-width: 40%;
    padding-right: 2em;
  }
  .text-on-bottom{
    padding-top: 3em;
    display: block;
  }
}



</style>
