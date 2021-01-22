<template>
    <div>
        <div class="blanks"></div>
        <div class="demo-type">
            <el-avatar :size="160" class="head"><img src="~@/assets/su.png"></el-avatar>
            <h1 style="describe">
                <h1 class="font">樂團</h1>
                <a href="https://www.instagram.com/summer_clues/?hl=zh-tw" style="text-decoration:none;" class="font">Instagram : summer_clues</a>
                <h1 class="font">「在某個夏天，我們用音樂把生活裡遺落的線索都撿起。」</h1>
            </h1>
        </div>
        <div class="blank"></div>
        <div class="demo-type">
            <el-avatar :size="160" class="head"><img src="~@/assets/ct.jpg"></el-avatar>
            <h1 style="describe">
                <h1 class="font">主唱 : 曾偌荃</h1>
                <a href="https://www.instagram.com/ct.910419/?hl=zh-tw" class="font" style="text-decoration:none;">Instagram : ct.910419</a>
                <h1 class="font">「甜點是人類最偉大的發明。」</h1>
            </h1>
        </div>
        <div class="blank"></div>
        <div class="demo-type">
            <el-avatar :size="160" class="head"><img src="~@/assets/sh.png"></el-avatar>
            <h1 style="describe">
                <h1 class="font">吉他、作詞、作曲 : 施柏年</h1>
                <a href="https://www.instagram.com/marcusrose_1205._/?hl=zh-tw" class="font" style="text-decoration:none;">Instagram : marcusrose_1205._</a>
                <h1 class="font">「做喜歡的事，讓喜歡的事有價值。」</h1>
            </h1>
        </div>
        <div class="blank"></div>
    </div>
</template>

<style lang="sass">
.demo-type
    height: 180px
    display: flex
    flex-direction: row
    margin-left: 15%
    margin-right: 15%
    background-image: url('~@/assets/wh.jpeg')
    background-color: rgb(255, 255, 255, .6)
    background-blend-mode: lighten


.head
    //border: solid green
    margin-left: 9%
    margin-top: 0.6%

.describe
    display: flex
    justify-content: space-between

.font
    //border: solid yellow
    line-height: 1
    margin-left: 10%
    font-size: 25px
    text-align: left
    width: 800px

.blank
    //border: solid blue
    height: 80px

</style>