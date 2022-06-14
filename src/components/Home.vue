<template>
    <div>
        <section class="home">
            <div class="left">
                <h2>It is <span>Amazing</span></h2>
                <p class="left-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda officia, modi quam soluta pariatur excepturi maxime provident, dolor non, nulla a eligendi in maiores nobis quos corrupti unde eius dolorem natus tempore dolore harum quasi nostrum sunt! Voluptatem, vero repellat.</p>
                
                <div class="bullet-wrapper">
                    <div class="bullet"></div>
                    <div class="bullet-w"></div>
                    <div class="bullet-w"></div>
                </div>
                <button>Learn more</button>
            </div>
            <div class="right">
                <figure><img src="../assets/Group 66globe.png" alt="globe" class="globe"></figure>
            </div>
        </section>   

    </div>
</template>

<style scoped>
.home{
    position: absolute;
    width: 89.9%;
    /* width: 950px; */
    /* height: 650px; */
    top: 78px;
    border: 1px solid black;
    display: flex;
    background-image: linear-gradient(#003654,#0a1e29, #11181b);
    justify-content: space-evenly;
    padding: 20px 50px;
}
.left{
    width: 491px;
    /* border: 1px solid #000; */
    
}
.left h2{
    color: #fff;
}
.left h2 span{
    color: #07a5fa;
}
.left-text{
    text-align: justify;
    line-height: 21px;
    color: #fff;
    font-size: 16px;
    font-weight: 400;
}
.bullet-wrapper{
    display: flex;
}
.bullet{
    width: 12px;
    height: 12px;
    background-color: #07a5fa;
    border-radius: 12px;

}
.bullet-w{
    width: 12px;
    height: 12px;
    background-color: #fff;
    border-radius: 12px;
    margin-left: 5px;
}
.right{
    width: 50%;
    /* border: 1px solid black; */
}
.globe{
    width: 274px;
    height: 273px;
    position: relative;
    left: 65px;
}
button{
    margin: 0px;
    padding: 5px;
    border-radius: 30px;
    border: 1px solid #e5e5e5;
    background-color: inherit;
    color: #e5e5e5;
    font-size: 11px;
    width: 114px;
    height: 38px;
    position: relative;
    top: 30px;
}
</style>

