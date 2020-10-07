<template>
      <center>
        <div class="navi">
            <div class="header__icons">
                    <div class="header__icon header__icon--active">
                        <HomeIcon/>
                        <p>Home</p>
                    </div>
            </div>
            <div class="header__icons">
                <div class="header__icon header__icon--active">
                    <SupervisorAccountIcon/>
                    <p>Contestant<span><ArrowDropDownIcon/></span></p>
                </div>
            </div>
            <div class="header__icons">
                <div class="header__icon header__icon--active">
                    <ThumbsUpIcon/>
                    <p>Vote</p>
                </div>
            </div>
            
        </div>
    </center>
</template>

<script>



export default {
    Name: 'Nav'
}
</script>

<style>
   .navi {
       margin-top: 50px
   }


</style>