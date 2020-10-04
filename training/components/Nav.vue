<template>
  <div>
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
            <div class="header__icons">
                <div class="header__icon header__icon--active">
                    <ShoppingBasketIcon/>
                    <p>Products</p>
                </div>
            </div>
            <div class="header__icons">
                <div class="header__icon header__icon--active">
                    <CardGiftcardIcon/>
                    <p>Support</p>
                </div>
            </div>
        </div>
  </div>
</template>

<script>
import HomeIcon from '@material-ui/icons/Home'
import ThumbsUpIcon from '@material-ui/icons/ThumbUpSharp'
import ShoppingBasketIcon from '@material-ui/icons/ShoppingBasket';
import SupervisorAccountIcon from '@material-ui/icons/SupervisorAccount';
import CardGiftcardIcon from '@material-ui/icons/CardGiftcard';
import ArrowDropDownIcon from '@material-ui/icons/ArrowDropDown';

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