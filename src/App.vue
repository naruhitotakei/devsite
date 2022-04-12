<template>
  <v-app>
    <div class="mx-auto color-gray header">
      <div class="main">
        <v-row class="ml-5 mr-2">
          <v-col cols="3">
            <h1 class="normal-font-weight">SITE NAME</h1>
          </v-col>
          <v-col cols="9" class="mr-auto text-right">
            <v-btn
              class="
                btn-1-one
                boxshadow-none
                border-show
                background-color-white
                header-btn-font
                btn-rounded
              "
              width="125"
              height="53"
              ><i class="fas fa-heart"> </i>お気に入り</v-btn
            >
            <v-btn
              class="
                btn-1-go
                boxshadow-none
                border-show
                background-color-white
                header-btn-font
                btn-rounded
              "
              width="125"
              height="53"
              >閲覧履歴</v-btn
            >
            <v-btn
              class="
                btn-1-go
                boxshadow-none
                border-show
                background-color-white
                header-btn-font
                btn-rounded
              "
              width="125"
              height="53"
              >会員登録</v-btn
            >
            <v-btn
              class="
                btn-1
                boxshadow-none
                border-show
                background-color-white
                header-btn-font
                btn-rounded
              "
              width="125"
              height="53"
              >ログイン</v-btn
            >
          </v-col>
        </v-row>
        <v-row class="mt-4">
          <v-col>
            <div class="top-button-group">
              <v-btn
                value="recent"
                class="
                  border-show
                  boxshadow-none
                  background-color-white
                  py-5
                  top-button
                  header-btn-font
                "
                height="60"
              >
                カテゴリ1
              </v-btn>
              <v-btn
                value="recent"
                class="
                  border-show
                  boxshadow-none
                  background-color-white
                  py-5
                  top-button
                  header-btn-font
                "
                height="60"
              >
                カテゴリ2
              </v-btn>
              <v-btn
                value="recent"
                class="
                  border-show
                  boxshadow-none
                  background-color-white
                  py-5
                  top-button
                  header-btn-font
                "
                height="60"
              >
                カテゴリ3
              </v-btn>
              <v-btn
                value="recent"
                class="
                  border-show
                  boxshadow-none
                  background-color-white
                  py-5
                  top-button
                  header-btn-font
                "
                height="60"
              >
                カテゴリ4
              </v-btn>
              <v-btn
                value="recent"
                class="
                  border-show
                  boxshadow-none
                  background-color-white
                  py-5
                  top-button
                  header-btn-font
                "
                height="60"
              >
                カテゴリ5
              </v-btn>
              <v-btn
                value="recent"
                class="
                  border-show
                  boxshadow-none
                  background-color-white
                  py-5
                  top-button
                  header-btn-font
                "
                height="60"
              >
                カテゴリ6
              </v-btn>
            </div>
          </v-col>
        </v-row>

        <v-row class="main-content">
          <v-col cols="9" class="main-content-one" lg="9" sm="12">
            <div class="mt-3">
              <h1><i class="fas fa-search mr-4"></i>お店を探す</h1>
              <div class="group1-main">
                <div>
                  <v-row>
                    <v-col cols="4">
                      <v-card
                        width="116px"
                        height="116px"
                        class="boxshadow-none border-show-big group1-card"
                      >
                        <i
                          style="font-size: 50px"
                          class="fas fa-map-marked-alt ml-8 mt-2"
                        >
                        </i>
                        <div class="group1-p-font text-center">
                          <span style="font-b">エリア</span>
                          <br />
                          <span>から探す</span>
                        </div>
                      </v-card>
                    </v-col>
                    <v-col>
                      <v-card
                        width="116px"
                        height="116px"
                        class="boxshadow-none border-show-big group1-card"
                      >
                        <i
                          style="font-size: 50px"
                          class="fas fa-subway ml-8 mt-2"
                        >
                        </i>
                        <div class="text-center group1-p-font">
                          <p>駅<br />から探す</p>
                        </div>
                      </v-card>
                    </v-col>
                    <v-col>
                      <v-card
                        width="116px"
                        height="116px"
                        class="boxshadow-none border-show-big group1-card"
                      >
                        <i
                          style="font-size: 50px"
                          class="fas fa-map-marked-alt ml-8 mt-2"
                        >
                        </i>
                        <div class="text-center group1-p-font">
                          <p>
                            現在地 <br />
                            から探す
                          </p>
                        </div>
                      </v-card>
                    </v-col>
                  </v-row>
                  <v-row>
                    <v-col>
                      <input
                        class="search border-show group1-search-font"
                        type="text"
                        placeholder="    キーワードから探す"
                      /><v-icon
                        class="border-show px-2 py-2"
                        style="color: white; background-color: #3ab2f6"
                      >
                        fas fa-search
                      </v-icon>
                    </v-col>
                  </v-row>
                </div>
              </div>
            </div>
            <div class="mt-16 group2">
              <h1 class="mt-6 mb-5">
                <i class="fas fa-file-search mr-3"></i>目的からお店を探す
              </h1>
              <v-row class="pl-14 mt-4">
                <v-col cols="4" v-for="item in group2_array" :key="item">
                  <v-btn class="btn-blue py-7 group2-btn">
                    {{ item }}
                  </v-btn>
                </v-col>
              </v-row>
            </div>

            <div class="group4">
              <h1 class="mb-10"><i class="fas fa-edit mr-5"></i>新着記事</h1>
              <div class="group4-div">
                <v-row class="pl-14">
                  <v-col cols="4 pr-6" v-for="item in group2_array" :key="item">
                    <v-card
                      height="370"
                      class="boxshadow-none border-show border-none"
                    >
                      <v-img
                        height="134"
                        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                      ></v-img>
                      <v-card-title class="normal-font-weight-big"
                        >記事タイトル記事タイトル記事タイトル</v-card-title
                      >
                      <hr width="80%" class="ml-6" />
                      <v-card-text>
                        <div class="d-flex justify-space-between">
                          <p>2018/07/21</p>
                          <p class="group-p">ブログ用タグ</p>
                        </div>
                        <p class="card-text-font margin-none">
                          記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋...
                        </p>
                      </v-card-text>
                    </v-card>
                  </v-col>
                </v-row>
              </div>

              <div class="mt-10 group4-but ml-9 text-center">
                <v-btn class="pl-12 py-6 btn-blue border-none boxshadow-none"
                  >記事一覧を見る<span class="pl-6">></span>
                </v-btn>
              </div>
            </div>

            <div class="group5 mt-16">
              <h1><i class="fas fa-edit mr-5"></i> 新着のお店</h1>
              <div class="pl-6">
                <div class="group5-ad mt-3 pr-3"></div>
                <v-row class="mt-8 pl-8">
                  <v-col
                    cols="4"
                    class="pr-5"
                    v-for="item in group2_array"
                    :key="item"
                  >
                    <v-card class="boxshadow-none border-show border-none">
                      <v-img
                        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                      ></v-img>
                      <v-card-title class="normal-font-weight-big"
                        >記事タイトル</v-card-title
                      >
                      <v-card-text>
                        <p class="card-text-font">東京都/千代田区/九段下</p>
                        <p class="card-text-font">
                          お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文...
                        </p>
                      </v-card-text>
                    </v-card>
                  </v-col>
                </v-row>
              </div>
              <div class="mt-10 group4-but ml-9 text-center">
                <v-btn class="pl-12 py-6 btn-blue border-none boxshadow-none"
                  >記事一覧を見る<span class="pl-6">></span>
                </v-btn>
              </div>
            </div>

            <div class="group6 mt-16">
              <h1><i class="fas fa-comments mr-5"></i> 新着の口コミ</h1>
              <v-row class="mt-6">
                <v-col cols="6" class="pl-16 pr-5" v-for="item in [1, 2, 3, 4]" :key="item">
                  <v-card
                    class="
                      group6-card
                      boxshadow-none
                      border-show border-none
                    "
                  >
                    <v-card-title
                      class="justify-space-between normal-font-weight-big"
                    >
                      <span class="card-text-font">記事タイトル</span>
                      <div class="d-flex">
                        <v-rating
                          :value="4.5"
                          color="amber"
                          dense
                          half-increments
                          readonly
                          size="14"
                        ></v-rating>
                        4.5
                      </div>
                    </v-card-title>
                    <hr width="80%" class="ml-6" />

                    <v-card-text>
                      <div class="d-flex justify-space-between">
                        <p class="card-text-font">口コミ投稿者名 20代・男性</p>
                        <p class="card-text-font">投稿日 2022/01/16</p>
                      </div>
                      <p class="card-text-font">
                        口コミタイトル口コミタイトル口コミタイトル
                      </p>
                      <p class="card-text-font">
                        口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文口コミ本文...
                      </p>
                      <div class="text-right float-right d-flex">

                        <div class="group6-div1"><i class="far fa-thumbs-up"></i> 参考になった！</div>
                        <div class="group6-div2"><div class="triangle-left"></div><div class="triangle-left-two"></div> 15</div>
                      </div>
                    </v-card-text>
                  </v-card>
                </v-col>
              </v-row>
            </div>
          </v-col>

          <v-col cols="3" lg="3" sm="12" class="siderbar">
            <v-row class="mt-1 sidebar-group1">
              <v-col>
                <v-card
                  class="
                    sidebar-group1-card
                    boxshadow-none
                    border-show border-none
                    d-flex
                    justify-center
                    align-center
                  "
                  height="50"
                >
                  <div>掲載ご希望の方はコチラ</div>
                </v-card>
                <v-card class="mt-5 boxshadow-none border-show border-none">
                  <v-card-title
                    ><i style="font-size: 35px" class="far fa-newspaper"></i>
                    <span style="font-size: 16px" class="ml-2"
                      >お知らせ</span
                    ></v-card-title
                  >
                  <v-card-text style="margin-top -20px">
                    <div>
                      <span class="card-text-font mb-4">2022/01/13</span>
                      <br />
                      <span class="card-text-font">
                        新着情報テキスト抜粋部分新着情報テキスト抜粋部分新着情報テキスト抜粋部分新着情報テキスト抜粋部分新着情報テキスト...
                      </span>
                    </div>
                    <div class="mt-4">
                      <span class="card-text-font mb-4">2021/07/21</span>
                      <br />
                      <span class="card-text-font">
                        新着情報テキスト抜粋部分新着情報テキスト抜粋部分新着情報テキスト抜粋部分新着情報テキスト抜粋部分新着情報テキスト...
                      </span>
                    </div>
                    <div class="text-right mt-4" style="margin-bottom -30px">
                      <span class="card-text-font" >お知らせ一覧</span>
                    </div>
                  </v-card-text>
                </v-card>
                <div class="slider-ad-one"></div>
                <div class="mt-6">
                  <h4 class="pl-3 mb-4"><i style="font-size: 25px" class="fas fa-crown mr-2"></i> カテゴリから探す</h4>
                  <div v-for="item in [1,2,3,4,5,6]" :key="item">
                  <v-card
                    rounded="0"
                    class="
                      sidebar-group1-card2
                      boxshadow-none
                      border-show border-none
                      d-flex
                      justify-center
                      align-center
                    "
                    height="65"
                    style="margin-top: -2px"
                  >
                    <div>カテゴリ{{item}}</div>
                  </v-card>
                  </div>
                </div>
                <div class="mt-8">
                  <h4 class="pl-3"><i style="font-size: 25px;" class="fas fa-crown mr-2"></i> 人気の記事</h4>
                  <div class="mt-6">
                    <div v-for="item in [1,2,3,4,5,6,7,8,9,0]" :key="item">
                      <v-row class="mx-auto image">
                        <v-col cols="4">
                          <img
                            height="64.43"
                            src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                            alt=""
                          />
                        </v-col>
                        <v-col cols="8"  class=" mt-2 d-flex
                      justify-center
                      align-center">
                          <p class="normal-font ">
                            人気の情報タイトル人気の情報タイトル人気の情報タイトル人気の情報タイトル
                          </p>
                        </v-col>
                      </v-row>
                    </div>
                  </div>
                </div>
              </v-col>
            </v-row>
            <div class="slider-ad-2 "></div>
          </v-col>

          <v-row class="group7 footer-font ml-16">
            <v-row>
              <v-col>
                <div class="group7-ad"></div>
              </v-col>
              <v-col class="ml-12">
                <h3>目的からお店を探す</h3>
                <br />
                <span>〜がしたい１</span>
                <br>
                <span>〜がしたい2</span>
                <br>
                <span>〜がしたい3</span>
                <br>
                <span>〜がしたい4</span>
                <br>
                <span>〜がしたい5</span>
                <br>
                <span>〜がしたい6</span>
              </v-col>
              <v-col>
                <h3>目的からお店を探す</h3>
                <br />
                <span>〜がしたい１</span>
                <br>
                <span>〜がしたい2</span>
                <br>
                <span>〜がしたい3</span>
                <br>
                <span>〜がしたい4</span>
                <br>
                <span>〜がしたい5</span>
                <br>
                <span>〜がしたい6</span>
              </v-col>
              <v-col>
                <span>会員登録</span>
                <br>
                <span>お店掲載希望の方</span>
                <br>
                <span>ログイン</span>
                <br>
                <span>お気に入り</span>
                <br>
                <span>閲覧履歴</span>
                <br>
                <span>運営者情報</span>
                <br>
                <span>プライバシーポリシー</span>
                <br>
                <span>利用規約</span> 
                <br>
                <span>お問い合わせ</span>
                <br>
                <span>サイトマップ</span>
              </v-col>
            </v-row>
          </v-row>
        </v-row>
        <div class="text-center mt-12">
          <span>SITE NAME</span>
          <br />
          <span>Copyrigth @SITE NAME All Rigths Reserved</span>
        </div>
      </div>
    </div>
  </v-app>
</template>

<style scoped>
.triangle-left {
  position: absolute;
  top: 5px;
  left: -5px;
	border-top: 5px solid transparent;
	border-right: 5px solid #555;
	border-bottom: 5px solid transparent;
}
.triangle-left-two {
  position: absolute;
  top: 6px;
  left: -4px;
	border-top: 4px solid transparent;
	border-right: 4px solid white;
	border-bottom: 4px solid transparent;
}
.group6-div1 {
  width: 125px;
  border: 1px solid #777777 !important;
  box-sizing: border-box !important;
  border-radius: 10px !important;
}
.group6-div2 {
  position: relative;
  margin-left: 8px;
  border: 1px solid #777777 !important;
  border-radius: 4px !important;
  width: 36px;
  text-align: center;
}
.v-card__text {
  margin-bottom: -10px;
}
.group1-card {
  border-radius: 12px !important;
}
.footer-font{
  font-family: Roboto;
  font-weight: 700;
  font-style: normal;
  font-size: 14px;
  line-height: 26.15px;
}
.image {
  margin-top: -20px;
}
.group2 {
  margin-bottom: 74px !important;
}
.group2-btn {
  color: white !important;
  font-weight: 900 !important;
  font-style: normal !important;
  font-size: 18px !important;
  line-height: 21.09px !important;
  border-radius: 10px !important;
  padding-left: 73px !important;
  padding-right: 73px !important;
}
.group1-p-font {
  font-weight: 900 !important;
  color: #777777 !important;
  font-style: normal !important;
  font-size: 18px !important;
  line-height: 26.73px !important;
}
.group1-main {
  margin-top: 12px !important;
  padding-left: 111px !important;
  /* padding-right: 111px; */
}
.main-content {
  margin-top: 30px !important;
}
.header {
  margin-top: 99px;
  max-width: 1240px !important;
}
.header-btn-font {
  color: #777777 !important;
  font-family: Roboto;
  font-weight: 700 !important;
  font-style: normal !important;
  font-size: 16px !important;
  line-height: 16px !important;
}
.btn-rounded {
  border-radius: 10px !important;
}
i {
  color: #3ab2f6;
}
.btn-blue {
  background-color: #3ab2f6 !important;
  color: #fff !important;
  font-weight: 900 !important;
  font-style: normal !important;
  font-size: 18px !important;
  line-height: 34.75px;
}
.siderbar {
}
@media only screen and (max-width: 1264px) {
  .siderbar {
    /* padding-left: 25px; */
    padding-right: 48px !important;
    padding-bottom: -200px !important;
    margin-left: 40px;
  }
  .main-content-one {
    margin-left: 5px;
  }
  .top-button-group {
    margin-left: 17px;
  }
  .group7 {
    margin-top: 500px;
  }
}
.margin-none {
  margin: 0 !important;
}
.border-none {
  border-radius: 0 !important;
}
.group-p {
  background-color: #c4c4c4;
}
.card-text-font {
  font-weight: 900 !important;
  font-size: 13px !important;
  line-height: 14.41px !important;
  letter-spacing: 1% !important;
}
.border-show-big {
  border: 2px solid #bbbdbf !important;
  /* box-shadow:  */
}
.top-button-group {
  display: flex;
  width: 100%;
}
.nav-font {
    font-family: Roboto !important;
  font-weight: 700 !important;
  font-style: normal !important;
  font-size: 18px !important;
  line-height: 16px !important;
  align-content: center !important;
}

.top-button-group .top-button {
  flex: 1;
  border-radius: 0;
}

.normal-font-weight {
  font-weight: 400;
}
.normal-font-weight-big {
  font-weight: 700;
  font-size: 18px;
  line-height: 21.09px;
  color: #777777;
}
.color-gray {
  color: #777777;
}
.border-show {
  border: 1px solid #bbbdbf !important;
}

.background-color-white {
  background-color: white !important;
}

.normal-font {
  font-size: 11px !important;
}

.boxshadow-none {
  box-shadow: none !important;
}

.v-overflow-bottom-navigation {
  border: 1px solid black !important;
  /* border-color: grey !important; */
}
.btn-1-go {
  margin-left: 15px;
  font-family: "Arial, sans-serif";
}
.btn-1-one {
  margin-left: 50px;
}
.btn-1 {
  margin-left: 15px;
}
.slider-ad-2 {
  margin-top: 30px;
  height: 730px;
  background-color: #e5e5e5;
  border: 0.3px solid black !important;
}
.sidebar-group1-card2 {
  /* margin-top: -20px; */
  text-align: center;
}
.sidebar-group1-card2 p {
  margin-top: 5px;
}
table tr {
  border: 1px, solid black !important;
}
table {
  width: 100%;
}
.slider-ad-one {
  margin-top: 20px;
  /* width: 300px; */
  height: 250px;
  background-color: #e5e5e5;
  border: 0.3px solid black !important;
}
/* p {
  font-size: smaller;
  line-height: 12px;
} */
.sidebar-group1-card {
  text-align: center;
}
.group7 {
  margin-top: 180px;
  margin-left: 30px;
}
.group7-ad {
  width: 300px;
  height: 260px;
  background-color: #e5e5e5;
  border: 0.3px solid black !important;
}
.group6-card {
  height: 280px;
  /* width: 380px; */
}
.group6-div {
  /* margin-left: 40px; */
  margin-top: 50px;
}
.group6 {
  margin-top: 40px !important;
}
.group5-div {
  margin-top: 40px;
}
.group5-ad {
  background-color: #e5e5e5;
  /* width: 830px; */
  height: 100px;
  margin-left: 30px;
  margin-top: 10px;
  border: 0.3px solid black !important;
}
.group5 {
  margin-top: 30px;
}
.group4-but {
  /* margin-left: 350px; */
}
.group4-but-but {
  background-color: #777777 !important;
  color: white !important;
  padding-left: 50px !important;
  padding-right: 5px !important;
}
.group4-div {
  margin-top: 10px;
}
.group4 {
  margin-top: 60px;
}
.group-but {
  margin-top: 25px;
}
.card {
  width: 116px;
  height: 116px;
  /* border: 1px, solid; */
}
.card-one {
  margin-left: 110px;
}
.card-two {
  margin-left: 150px;
}
.card-three {
  margin-left: 150px;
}
.search {
  width: 78%;
  padding-top: 7px;
  padding-bottom: 9px;
}
</style>

<script>
// import HelloWorld from './components/HelloWorld';
// import japanIcon from "./assets/icon/japan.png";

export default {
  name: "App",

  data: () => ({
    group2_array: [
      "〜がしたい1",
      "〜がしたい2",
      "〜がしたい3",
      "〜がしたい4",
      "〜がしたい5",
      "〜がしたい6",
    ],
    //
  }),
};
</script>
