<template>
    <div class="product-container">
        <h3>Meet Our Team</h3>
        <div class="grid-container">
            <div class="grid-item">
                <div class="grid-item-picture"><figure><img src="../assets/Ellipse 8pix.png" alt="human"></figure>
                <span>Peter Ugah</span></div>
                <p>CTO</p>
            </div>
             <div class="grid-item">
                <div class="grid-item-picture"><figure><img src="../assets/Ellipse 8pix.png" alt="human"></figure>
                <span>Peter Ugah</span></div>
                <p>CTO</p>
            </div>
             <div class="grid-item">
                <div class="grid-item-picture"><figure><img src="../assets/Ellipse 8pix.png" alt="human"></figure>
                <span>Peter Ugah</span></div>
                <p>CTO</p>
            </div>
             <div class="grid-item">
                <div class="grid-item-picture"><figure><img src="../assets/Ellipse 8pix.png" alt="human"></figure>
                <span>Peter Ugah</span></div>
                <p>CTO</p>
            </div>
             <div class="grid-item">
                <div class="grid-item-picture"><figure><img src="../assets/Ellipse 8pix.png" alt="human"></figure>
                <span>Peter Ugah</span></div>
                <p>CTO</p>
            </div>
             <div class="grid-item">
                <div class="grid-item-picture"><figure><img src="../assets/Ellipse 8pix.png" alt="human"></figure>
                <span>Peter Ugah</span></div>
                <p>CTO</p>
            </div>
        </div>

    </div>
</template>

<style scoped>
.product-container{
    position: absolute;
    top: 158.5em;
    /* border: 1px solid black; */
    padding: 20px 50px;
}
.grid-container{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 1em;
    grid-auto-rows: minmax(100px, auto);
    
}  
.grid-item{
    box-shadow: 0px 20px 50px 2px rgba(0, 0, 0, 0.08);
}
img{
    width: 151px;
}
/* .grid-item-picture span{
text-align: center;
font-size: 14px;
justify-items: center;
} */
</style>

