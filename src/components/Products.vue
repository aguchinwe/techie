<template>
    <!-- <div> -->
         <div class="product-container">
        <h3>Products</h3>
        <div class="grid-container">
            <div class="grid-item">
                <div class="grid-item-header"><figure><img src="../assets/Group 67dark1.png" alt="Education"></figure>
                <span>IOT (M2M Cpmmunication)</span></div>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Animi similique amet, consectetur quis quasi pariatur neque, unde incidunt minima nemo nam recusandae voluptates esse exercitationem sunt at rerum est laborum.</p>
            </div>
            <div class="grid-item">
                <div class="grid-item-header"><figure><img src="../assets/Group 672dark.png" alt="Education"></figure>
                <span>Cyber-Security</span></div>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium voluptates ratione ab numquam distinctio, dolor maxime quae id alias est sunt maiores nihil quaerat nulla natus assumenda tempora molestias porro.</p>
            </div>
            <div class="grid-item">
                <div class="grid-item-header"><figure><img src="../assets/Group 673dark.png" alt="Education"></figure>
                <span>Mobile & Web Development</span></div>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis velit, eius accusamus aperiam nulla voluptate dolor consectetur rerum quo quam nesciunt pariatur laborum accusantium ipsa omnis, reprehenderit exercitationem ipsam id.</p>
            </div>
             <div class="grid-item">
                <div class="grid-item-header"><figure><img src="../assets/Group 67dark1.png" alt="Education"></figure>
                <span>Embedded Systems</span></div>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Animi similique amet, consectetur quis quasi pariatur neque, unde incidunt minima nemo nam recusandae voluptates esse exercitationem sunt at rerum est laborum.</p>
            </div>
             <div class="grid-item">
                <div class="grid-item-header"><figure><img src="../assets/Group 672dark.png" alt="Education"></figure>
                <span>Robotics Process Automation</span></div>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Animi similique amet, consectetur quis quasi pariatur neque, unde incidunt minima nemo nam recusandae voluptates esse exercitationem sunt at rerum est laborum.</p>
            </div>
             <div class="grid-item">
                <div class="grid-item-header"><figure><img src="../assets/Group 673dark.png" alt="Education"></figure>
                <span>AI/Machine Learning</span></div>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Animi similique amet, consectetur quis quasi pariatur neque, unde incidunt minima nemo nam recusandae voluptates esse exercitationem sunt at rerum est laborum.</p>
            </div>
        </div>

    </div>
</template>

<style scoped>
.product-container{
    position: absolute;
    top: 77.2em;
    /* border: 1px solid black; */
    padding: 20px 50px;
}
h3{
    text-align: center;
    color: #003654;
}
.grid-container{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 1em;
    grid-auto-rows: minmax(100px, auto);
    
}  
.grid-item{
    border-radius: 5px;
    margin: 10px;
    padding: 20px;
    box-shadow: 0px 20px 50px 2px rgba(0, 0, 0, 0.08);
    
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
    padding-left: 18px;
    width: 50%;
    color: #003654;
    
}
.grid-item p{
    color: #666;
    font-size: 16px;
}

</style>
