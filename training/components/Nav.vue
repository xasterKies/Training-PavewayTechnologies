<template>
  <div>
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
            <div className="header__icons">
                <div className="header__icon header__icon--active">
                    <ShoppingBasketIcon/>
                    <p>Products</p>
                </div>
            </div>
            <div className="header__icons">
                <div className="header__icon header__icon--active">
                    <CardGiftcardIcon/>
                    <p>Support</p>
                </div>
            </div>
        </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>