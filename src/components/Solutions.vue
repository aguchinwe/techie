<template>
    <div class="solution-container">
        <h3>Solutions</h3>
        <div class="grid-container">
            <div class="grid-item">
                <div class="grid-item-header"><figure><img src="../assets/Group 67Edu.png" alt="Education"></figure>
                <span>Educational Organizations</span></div>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Animi similique amet, consectetur quis quasi pariatur neque, unde incidunt minima nemo nam recusandae voluptates esse exercitationem sunt at rerum est laborum.</p>
            </div>
            <div class="grid-item">
                <div class="grid-item-header"><figure><img src="../assets/Group 67sale.png" alt="Education"></figure>
                <span>All Sales Enterprises</span></div>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium voluptates ratione ab numquam distinctio, dolor maxime quae id alias est sunt maiores nihil quaerat nulla natus assumenda tempora molestias porro.</p>
            </div>
            <div class="grid-item">
                <div class="grid-item-header"><figure><img src="../assets/Group 67people.png" alt="Education"></figure>
                <span>Consumer brands</span></div>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis velit, eius accusamus aperiam nulla voluptate dolor consectetur rerum quo quam nesciunt pariatur laborum accusantium ipsa omnis, reprehenderit exercitationem ipsam id.</p>
            </div>
        </div>
    </div>
</template>
<style scoped>
.solution-container{
    position: absolute;
    top: 53.9em;
    /* border: 1px solid black; */
    background-image: url("../assets/image 7.png"),linear-gradient(#003654,#0a1e29);
    padding: 20px 50px;
}
h3{
    text-align: center;
    color: #fff;
}
.grid-container{
    display: flex;
    
}  
.grid-item{
    background-color: #fff;
    max-width: 395px;
    max-height: 334px;
    border-radius: 5px;
    margin: 10px;
    padding: 20px;
} 
.grid-item-header{
    display: flex;
    align-items: center;
    /* padding-left: 10px; */
} 
.grid-item-header figure{
    margin: 0px;
}
.grid-item-header figure img{
    width: 50px;
}
.grid-item-header span{
    padding-left: 20px;
    width: 30%;
    color: #003654;
    
}
.grid-item p{
    color: #666;
    font-size: 16px;
}
    /* linear-gradient(#003654); */

</style>
