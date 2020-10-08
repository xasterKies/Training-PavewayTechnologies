<template>
  <div>
      <section class="slider text-center" id="slider">
            <div class="slider-overlay">
                <div class="slider-content">
                    
                    <br>
                    <div class="text"></div>
                    <br><br>
                    <div class="cta-div">
                        <a href="" class="btn1"><span class="con-text">Contact Us</span></a>
                    </div>
                    <br>
                    <br>
                    

                </div>

            </div>


        </section>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.slider {
    width: 100%;
    height: 700px;
    background-image: url('../assets/vue-mastery.webp');
    background-size: cover;
    background-position: center;
}

.slider-overlay{
    width: 100%;
    height: 100%;
    background: rgba(0,0,0,0.65);
    position: relative;
}

.slider-content{
    position: absolute;
    top: 39%;
    width: 100%;
}
</style>