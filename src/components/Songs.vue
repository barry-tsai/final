<template>
    <div>
	<div class="blanks"></div>
    <iframe class="song" width="956" height="538" src="https://www.youtube.com/embed/bVTxnMVIcJE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
    <div class="Flex">
        <h1 class="Title">夏日線索 Summer Clues【輾轉】Demo ver.</h1>
        <el-button @click="drawer = true" type="primary" style="margin-left: 10%; margin-top: 2%"  class="button">
            歌詞
        </el-button>
        <el-drawer
            title="Title"
            :visible.sync="drawer"
            :with-header="false">
            <div class="lyrics">
            <span>
                夏日線索 Summer Clues【輾轉】Demo ver.<br><br>
                作詞 | MR.<br>
                作曲 | 夏日線索<br>
                編曲 | 夏日線索<br><br>
                是什麼在不成眠的夜翻騰<br>
                窗外微亮滲透過失眠夜色<br>
                麻木已久卻還悸動的炙熱<br>
                重複著<br>
                渴望擁抱但遺失所有清澈<br><br>
                是什麼在不完整的夜翻滾<br>
                又一個人在看著天亮恍神<br>
                漣漪太短你給的都太溫和<br>
                厭倦了<br>
                渴望逃離卻又失而復得<br><br>
                日子斑駁 在昨夜夢中<br>
                我是燈火 仍為你閃爍<br>
                輾轉拼湊 散落一地溫柔<br>
                倘若無可奈何就放手<br><br>
                是什麼把那些眼淚都沸騰<br>
                或者還在期待什麼會發生<br>
                習慣失去習慣獨自再振奮<br>
                無所謂了<br>
                渴望誰找到自己又如何<br><br>
                日子斑駁 在昨夜夢中<br>
                我是燈火 仍為你閃爍<br>
                輾轉拼湊 散落一地溫柔<br>
                倘若無可奈何就放手<br><br>
                是什麼在不成眠的夜翻騰<br>
                窗外微亮滲透過失眠夜色<br>
            </span>
            </div>
        </el-drawer>
    </div>
	<div class="buttom"></div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                drawer: false,
            };
        }
    };
</script>

<style lang="sass">
.song
    margin-left: 10%

.blanks
    height: 20px

.buttom
    height: 50px

.lyrics
    margin-left: 5%
    font-size: 20px
    margin-top: 5%

.button
    background-color: black
    border: solid black
    font-size: 20px
    font-family: "竹風體"

.Title
    //border: solid red
    width: 60.8%
    font-size: 30px
    margin-top: 2%

.Flex
    display: flex
    flex-direction: row
    //border: solid orange
    margin-left: 10%

</style>