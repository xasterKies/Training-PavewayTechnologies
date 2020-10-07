<template>
      <center>
        <div class="navi">
            <div className="header__icons">
                <div className="header__icon header__icon--active">
                    <HomeIcon/>
                    <p>Home</p>
                </div>
                <div className="header__icon">
                    <FlashOnIcon/>
                    <p>Trending</p>
                </div>
                <div className="header__icon">
                    <LiveTvIcon/>
                    <p>Live Tv</p>
                </div>
                <div className="header__icon">
                    <VideoLibraryIcon/>
                    <p>Collections</p>
                </div>
                <div className="header__icon">
                    <SearchIcon/>
                    <p>Search</p>
                </div>
                <div className="header__icon">
                    <PersonOutlineIcon/>
                    <p>Account</p>
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
    padding: 20px;
    align-items: center;
    justify-content: space-between;
    overflow-x: scroll;
    margin-top: 100px;
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
    display: flex;
    align-items: center;
    text-align: center;
}

.header > img {
    object-fit: contain;
    height: 80px;
}

.header__icon {
    display: flex;
    flex-direction: column;
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