<template>
    <header>
        <div class="member_icon"></div>
        <ul class="nav">
            <li></li>
        </ul>
    </header>
    <div class="container">
        <div class="function">
            <button type="button" class="btn _primary">按鈕</button
            ><label class="normal_search"
                ><input type="text" /><i class="material-icons">
                    search
                </i></label
            >
        </div>
        <div class="tbBox">
            <div class="tbBox_head">
                <table>
                    <caption class="tbBox_title"></caption>
                    <tr>
                        <th class="_tb_w20%">欄位1</th>
                        <th class="_tb_w20%">欄位2</th>
                        <th class="_tb_w20%">欄位3</th>
                        <th class="_tb_w20%">欄位4</th>
                        <th class="_tb_w20%">欄位5</th>
                    </tr>
                </table>
            </div>
            <div class="tbBox_body">
                <!-- <TitleTable
                v-for="(item, index) in member1.sort"
                :key="index"
                :stockNmae="item"
                :stockIndex="index"
            ></TitleTable> -->
            </div>
        </div>
        <!--v-if-->
    </div>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
export default {
    name: "App",
    components: {
        HelloWorld,
    },
};
</script>
<style lang="scss" src="./assets/scss/all.scss"></style>

<style lang="scss">
</style>
