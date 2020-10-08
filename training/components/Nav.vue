<template>
      <center>
        <div class="navi container">
            <ul class="nav navbar-nav">
                    <i class="fa fa-home"></i>
                    <li>Home</li>
                
                    <i class="fa fa-home"></i>
                    <li>Courses</li>
                
                    <i class="fa fa-home"></i>
                    <li>My Courses</li>
                
            </ul>
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

li {
    display: none;
    letter-spacing: 1px;
    margin-left: auto;
    margin-right: auto;
    font-size: 15px;
    padding: 25px;
    font-weight: 700;
    opacity: 0.8;
    transition: transform 70ms ease-out;
}

li:hover {
    opacity: 1;
    transform: scale(1.2)
}

.header__icon:hover > p {
    display: inline-flex;
}


.header__icon--active > p {
    display: inline-flex;
}




</style>