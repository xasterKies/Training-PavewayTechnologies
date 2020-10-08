<template>
      <center>
        <div class="navi col-md-12">
            <div class="container-fluid">
            <div className="header__icons">
                
                <div className="header__icon header__icon--active">
                    <i class="fa fa-home"></i>
                    <p>Home</p>
                </div>
                
                <div className="header__icon">
                    <i class="fa fa-home"></i>
                    <p>Courses</p>
                </div>
                
                
                <div className="header__icon">
                    <i class="fa fa-home"></i>
                    <p>My Courses</p>
                </div>
                
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
    color: white;
    display: flex;
    padding: 0px;
    align-items: center;
    justify-content: space-between;
    overflow-x: scroll;

    margin-top: 35px;
    background-image: linear-gradient(to right, rgba(0, 0, 0, 0.89), #88cdff4f) !important;

}

/*Removing scroll*/
.navi::-webkit-scrollbar {
    display: none;
}

.navi {
    -ms-overflow-style: none;
    scrollbar-width: none;
}

/*Removing scroll*/

.header__icons {
    
    align-items: center;
    text-align: center;
    flex: 1;
    flex-direction: row;
    justify-content: space-around;
}

.header > img {
    object-fit: contain;
    height: 80px;
}

.header__icon {
    border: white;
    cursor: pointer;
    width: 100px;
}

.header__icon > .MuiSvgIcon-root {
    margin-left: auto;
    margin-right: auto;
    font-size: 30px;
}

.header__icon > p {
    display: none;
    text-transform: uppercase;
    letter-spacing: 3px;
    margin-left: auto;
    margin-right: auto;
    font-size: small;
}

.header__icon:hover > p {
    display: inline-flex;
}


.header__icon--active > p {
    display: inline-flex;
}




</style>