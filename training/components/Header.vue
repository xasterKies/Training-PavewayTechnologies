<template>
   <div class="header">
        <nav class="navbar navbar-light navbar-fixed-top" style="background-color: #e3f2fd;" >
        <div class="container">
            <div class="navbar-header">
                <!------------------Responsive button --------------------->
                <button  type ="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navi">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <a href="" class="navbar-brand">
                    <img src="../assets/pavewayLogo.png" alt="logo" class="logo pull-left logo-responsive d-inline-block align-top">
                    <h1 class="name pull-left">PaveWay Training</h1>
                </a>
            </div>


            <div class="collapse navbar-collapse pull-right" id="navi">
                <!------------------Navigation menu --------------------->
                <span className="btn-sign">
                <Button color= "primary" variant="outline-light btn-raised"><span>Login</span></Button>
            </span>
            
            <span className="btn-sign">
                <Button  variant="btn-outline-light btn-raised"><span>Sign up</span></Button>
            </span>
                <!------------------Navigation menu ends --------------------->
            </div>



        </div>
    </nav>
            
 </div>
   
</template>

<script>
export default {
    Name : 'Header'
}
</script>

<style>
    .header {
    color: white !important;
    display: flex!important;
    padding: 20px!important;
    align-items: center!important;
    justify-content: space-between!important;
    background-image: linear-gradient(to right, #000, #00439b);
   
}

/*Removing scroll*/
.header::-webkit-scrollbar {
    display: none!important;
}

.header {
    -ms-overflow-style: none !important;
    scrollbar-width: none !important;
}
/*Removing scroll*/

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

.name {
    font-size: 30px;
    text-decoration: solid;
    padding-bottom: 15px;
    padding-left: 5px;
    font-weight: 0.5;
    color: #ffffff
}

.navbar {
    padding: 25px 0px;
    border-bottom: none !important;
    transition: all 0.5s ease-in-out;
}

.header__icon:hover > p {
    display: inline-flex;
}

.header__icon--active > p {
    display: inline-flex;
}

h1 {
    letter-spacing: 2px!important;
    margin-right: auto!important;
    font-weight: 700;
    color: white;
    margin-top: -10px;
}

.btn-sign {
    padding: 5px !important;
    display: flex !important;
    flex-direction: column !important;
}

.btn-sign:hover {
    box-shadow: white !important;
}

span > Button {
    flex-direction: column;
    text-transform: uppercase;
    letter-spacing: 3px;
    margin-top: 15px;
    margin-left: auto;
    margin-right: auto;
    font-size: small;
}

.logo {
    max-width: 10%;
    height: auto;
    display: flex;
    margin-right: auto;
}

.logo-responsive {
    margin-top: -20px;
    
}

.navbar-brand {
    
    margin: 0px !important;
    padding: 0px !important;
}
</style>