<template>
  <section class="list">
    <div class="point-in-time side-to-side">
      <div class="image">
        <img src="http://lorempixel.com/600/700/"/>
      </div>
      <div class="text-on-right text">
        <p>Something about the image the first</p>
      </div>
    </div>
    <div class="point-in-time side-to-side">
      <div class="image">
        <img src="http://lorempixel.com/300/500/"/>
      </div>
      <div class="text-on-right text">
        <p>Something about the image the second</p>
      </div>
    </div>
    <div class="point-in-time">
      <div class="image">
        <img src="http://lorempixel.com/1000/500/"/>
      </div>
      <div class="text text-on-bottom">
        <p>Something about the image the third</p>
      </div>
    </div>
    <div class="point-in-time side-to-side">
      <div class="text text-on-left">
        <p>Something about the image the last</p>
      </div>
      <div class="image">
        <img src="http://lorempixel.com/200/700/"/>
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
  padding: 30px;
  border: 1px #999 solid;
  margin: 30px auto;
}
.side-to-side{
  display: flex;
  flex-direction: row;
}
.image{

}
.text-on-right{
  padding-left: 2em;
}
.text-on-left{
  padding-right: 2em;
}
.text-on-bottom{
  padding-top: 2em;
  display: block;
}
</style>
