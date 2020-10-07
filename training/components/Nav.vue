<template>
      <center>
        <div className="navi">
            <div className="header__icons">
                    <div className="header__icon header__icon--active">
                        <HomeIcon/>
                        <p>Home</p>
                    </div>
            </div>
            <div className="header__icons">
                <div className="header__icon header__icon--active">
                    <SupervisorAccountIcon/>
                    <p>Contestant<span><ArrowDropDownIcon/></span></p>
                </div>
            </div>
            <div className="header__icons">
                <div className="header__icon header__icon--active">
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
    display: flex!important;
    color: white!important;
    overflow-x: scroll!important;
    padding: 10px!important;
    padding-left: 40px!important;
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

.header__icons {
    display: flex;
    align-items: center;
    text-align: center;
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


</style>