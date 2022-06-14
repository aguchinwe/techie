<script>
export default {
    
}
</script>

<template>
    <div class="container">
         <div class="header-div">
             <figure><img src="../assets/logos 1.png" alt="Company logo"></figure>
            
            <div class="header-icons">
                <ul>
                    <li><a href="./#/About.vue">About us</a> </li>
                    <li><a href="./#/Solutions.vue">Solutions</a></li>
                    <li><a href="./#/Products.vue">Products</a> </li>
                    <li><a href="./#/OurProcess.vue">Our Process</a></li>
                </ul>
            </div>
            <button><a href="./#/Contact.vue">Contact Us</a> </button>  
        </div>
         </div>
    
</template>

<style scoped>

.header-div{
    width: 99.8%;
    height: 76px;
    position: absolute;
    display: flex;
    border: 1px solid #fff;
    margin: 0 auto;
    justify-content: space-evenly;
    align-items: center;
    
}
.header-div figure{
    width: 135px;
    height: 45px;
}
.header-icons{
    width: 364px;
    height: 18px;
    display: flex;
    flex-direction: row;
    }
.header-icons ul, li{
    display: flex;
    text-decoration: none;
    margin: 0px;
    
}
.header-icons li a{
    display: flex;
    text-decoration: none;
    padding: 0px 12px;
    font-size: 14px;
    color: #4a4a4a;
}
.header-icons li a:hover{
    color: #1f99db;
}
button{
    margin: 0px;
    padding: 10px;
    border-radius: 30px;
    border: 1px solid #003654;
    background-color: #fff;
    color: #1f99db;
    font-size: 13px;
    width: 124px;
    height: 48px;

}
button a{
     display: flex;
    text-decoration: none;
    padding: 0px 12px;
    font-size: 14px;
    color: #4a4a4a;
}
button a:hover{
    color: #1f99db;

}
</style>


