<template>
        <div class="process-grid-container">
            <h3>Our Process</h3> 
            <div class="grid-container">
            <div class="grid-item">
                <div class="grid-item-header">
                <figure><img src="../assets/group.png" alt="nothing yet"></figure>
                <span>User Research</span>
            </div>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam ipsa mollitia, assumenda, excepturi blanditiis ratione repudiandae labore hic esse quis, consequatur id nesciunt autem doloribus incidunt dicta rem voluptatem veniam!</p>
            </div>
            <div class="grid-item">
                <div class="grid-item-header">
                <figure><img src="../assets/group.png" alt="nothing yet"></figure>
                <span>User Research</span>
            </div>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam ipsa mollitia, assumenda, excepturi blanditiis ratione repudiandae labore hic esse quis, consequatur id nesciunt autem doloribus incidunt dicta rem voluptatem veniam!</p>
            </div>
            <div class="grid-item">
                <div class="grid-item-header">
                <figure><img src="../assets/group.png" alt="nothing yet"></figure>
                <span>User Research</span>
            </div>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam ipsa mollitia, assumenda, excepturi blanditiis ratione repudiandae labore hic esse quis, consequatur id nesciunt autem doloribus incidunt dicta rem voluptatem veniam!</p>
            </div>
            <div class="grid-item">
                <div class="grid-item-header">
                <figure><img src="../assets/group.png" alt="nothing yet"></figure>
                <span>User Research</span>
            </div>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam ipsa mollitia, assumenda, excepturi blanditiis ratione repudiandae labore hic esse quis, consequatur id nesciunt autem doloribus incidunt dicta rem voluptatem veniam!</p>
            </div>
        </div> 
     </div>
    
</template>

<style scoped>
.process-grid-container{
    position: absolute;
    top: 120.7em;
    /* border: 1px solid black; */
    padding: 40px 100px;
    background-image: url("../assets/image 7.png");
    opacity: 0.9;
    /* background-color: #003654; */
}
h3{
    /* text-align: center; */
    color: #003654;
}
.grid-container{
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-gap: 1em;
    grid-auto-rows: minmax(100px, auto);
   
}  
.grid-item{
    /* border-radius: 5px;
    margin: 10px;
    padding: 20px; */
    box-shadow: 0px 20px 50px 2px rgba(0, 0, 0, 0.08);
     background-color: #fff;
} 
/* .grid-item-header{
    display: flex;
    align-items: center;
    
}  */
.grid-item-header figure{
    margin: 0px;
}
.grid-item-header figure img{
    width: 50px;
}
.grid-item-header span{
    padding-left: 18px;
    width: 50%;
    color: #003654;
    
}
.grid-item p{
    color: #666;
    font-size: 16px;
}

</style>
