<template>
      <div class="navi">
          <div>
            <div class="header__icons">
                    <div class="header__icon header__icon--active">
                        <i class="fas fa-home"></i>
                        <p>Home</p>
                    </div>
            </div>
            <div class="header__icons">
                <div class="header__icon header__icon--active">
                    
                    <p>Courses<span></span></p>
                </div>
            </div>
            <div class="header__icons">
                <div class="header__icon header__icon--active">
                    
                    <p>My Courses</p>
                </div>
            </div>
            </div>
            
        </div>
  
</template>

<script>



export default {
    Name: 'Nav'
}
</script>

<style>
    .navi {
    display: flex!important;
    color: white!important;
    overflow-x: scroll!important;
    padding: 10px!important;
    padding-left: 40px!important;
    background-image: linear-gradient(to right, #051421, #042727);
}

/*Hiding scrollbar*/
.navi::-webkit-scrollbar {
    display: none!important;
}

.navi {
    -ms-overflow-style: none!important;
    scrollbar-width: none !important;
}
/*Hiding the scrollbar*/

.navi > div {
    cursor: pointer;
    margin-left: 30px;
    margin-right: 30px;
    font-weight: 400;
    opacity: 0.7;
    transition: transform 70ms ease-out;
    font-size: 20px;
}

.navi > div:hover {
    opacity: 1;
    transform: scale(1.2)
}


</style>