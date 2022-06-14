<template>
    <div class="about-container">
        <h3>About us</h3>
        <div class="about-divs">
            <div class="image">
                <figure><img src="../assets/Group.png" alt="workers"></figure>
            </div>
            <div class="text">
                <h5>FORWARD THINKING</h5>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Cum ea ipsa aspernatur perferendis dolorum dignissimos accusamus pariatur repudiandae sit itaque natus, laborum blanditiis exercitationem a odit suscipit quibusdam sint voluptatum? Nam earum eaque odio officiis iste animi a, similique cum
                </p>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Voluptate fugit illo, at, nihil excepturi magnam dolores numquam alias temporibus ipsum iure dignissimos architecto! Repellat accusamus amet itaque, dolorem quidem quae quos voluptas suscipit accusantium doloremque harum repudiandae fugit quod excepturi,</p>
            </div> 
        </div>
    </div>
</template>

<style scoped>
.about-container{
    position: absolute;
    top: 26.8em;
    /* border: 1px solid black; */
    padding: 20px 50px;
}
h3{
    text-align: center;
    color: #113447;
}
.about-divs{
    display: flex;
}
.image{
    width: 50%;
}
img{
    width: 380px;
    position: relative;
    right: 20px;
}
.text{
    width: 50%
}
h5{
    color: #3eb5f5;
}
p{
    text-align: justify;
    font-weight: 400;
    font-size: 16px;
    line-height: 24px;
    color: #666666;
}
</style>

