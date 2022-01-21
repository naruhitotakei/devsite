<template>
  <v-app>
    <div class="container color-gray mt-10" max-width="1240">
      <v-row>
        <v-col cols="6">
          <h1 class="normal-font-weight">SITE NAME</h1>
        </v-col>
        <v-col cols="6" class="mr-auto text-right">
          <v-btn
            class="
              btn-1-one
              boxshadow-none
              border-show
              background-color-white
              normal-font
            "
            ><v-icon> fas fa-heart </v-icon>お気に入り</v-btn
          >
          <v-btn
            class="
              btn-1-go
              boxshadow-none
              border-show
              background-color-white
              normal-font
            "
            >お気に入り1</v-btn
          >
          <v-btn
            class="
              btn-1-go
              boxshadow-none
              border-show
              background-color-white
              normal-font
            "
            >お気に入り2</v-btn
          >
          <v-btn
            class="
              btn-1
              boxshadow-none
              border-show
              background-color-white
              normal-font
            "
            >お気に入り3</v-btn
          >
        </v-col>
      </v-row>
      <v-row>
        <div class="top-button-group">
          <v-btn
            value="recent"
            class="
              border-show
              boxshadow-none
              background-color-white
              py-5
              top-button
              normal-font
            "
          >
            お気に入り1
          </v-btn>
          <v-btn
            value="recent"
            class="
              border-show
              boxshadow-none
              background-color-white
              py-5
              top-button
              normal-font
            "
          >
            お気に入り2
          </v-btn>
          <v-btn
            value="recent"
            class="
              border-show
              boxshadow-none
              background-color-white
              py-5
              top-button
              normal-font
            "
          >
            お気に入り3
          </v-btn>
          <v-btn
            value="recent"
            class="
              border-show
              boxshadow-none
              background-color-white
              py-5
              top-button
              normal-font
            "
          >
            お気に入り4
          </v-btn>
          <v-btn
            value="recent"
            class="
              border-show
              boxshadow-none
              background-color-white
              py-5
              top-button
              normal-font
            "
          >
            お気に入り5
          </v-btn>
          <v-btn
            value="recent"
            class="
              border-show
              boxshadow-none
              background-color-white
              py-5
              top-button
              normal-font
            "
          >
            お気に入り6
          </v-btn>
        </div>
      </v-row>
      <v-row class="mt-4">
        <v-col cols="9">
          <v-row>
            <div class="mt-4">
              <h1><v-icon> fas fa-search </v-icon> お店を探す</h1>
              <div>
                <v-row class="justify-space-between mt-2 mb-4">
                  <v-card
                    width="116px"
                    height="116px"
                    class="card-one boxshadow-none border-show-big"
                  >
                    <img
                      src="./assets/icon/japan.png"
                      width="50"
                      height="48.73"
                      class="ml-8 mt-2"
                    />
                    <div class="pl-7 pr-8 pt-2 normal-font">
                      <p>エリアから探す</p>
                    </div>
                  </v-card>
                  <v-card
                    width="116px"
                    height="116px"
                    class="card-two boxshadow-none border-show-big"
                  >
                    <v-icon size="50" class="ml-8 mt-5">fas fa-subway</v-icon>
                    <div class="pl-7 pr-8 pt-2 text-center normal-font">
                      <p>駅<br />から探す</p>
                    </div>
                  </v-card>
                  <v-card
                    width="116px"
                    height="116px"
                    class="card-three boxshadow-none border-show-big"
                  >
                    <v-icon size="50" class="ml-8 mt-5"
                      >fas fa-map-marked-alt</v-icon
                    >
                    <div class="pl-7 pr-8 pt-2 text-center normal-font">
                      <p>現在地 から探す</p>
                    </div>
                  </v-card>
                </v-row>
                <v-row class="">
                  <input
                    class="search border-show pl-4"
                    type="text"
                    placeholder="キーワードから探す"
                  /><v-icon
                    class="border-show px-2"
                    style="color: white; background-color: #777777"
                  >
                    fas fa-search
                  </v-icon>
                </v-row>
              </div>
            </div>
            <div class="mt-16">
              <h1><i class="fas fa-file-search"></i> 目的からお店を探す</h1>
              <div class="group-but">
                <v-row>
                  <v-btn
                    x-large
                    width="250"
                    class="ml-16 background-color-white"
                    >〜がしたい１</v-btn
                  >
                  <v-btn x-large width="250" class="ml-7 background-color-white"
                    >〜がしたい2</v-btn
                  >
                  <v-btn x-large width="250" class="ml-7 background-color-white"
                    >〜がしたい3</v-btn
                  >
                </v-row>
                <v-row class="mt-10">
                  <v-btn
                    x-large
                    width="250"
                    class="ml-16 background-color-white"
                    >〜がしたい 4</v-btn
                  >
                  <v-btn x-large width="250" class="ml-7 background-color-white"
                    >〜がしたい 5</v-btn
                  >
                  <v-btn x-large width="250" class="ml-7 background-color-white"
                    >〜がしたい6</v-btn
                  >
                </v-row>
              </div>
            </div>

            <div class="group4">
              <h1 class="mb-10"><i class="fas fa-edit"></i> 新着記事</h1>
              <div class="group4-div">
                <v-row class="justify-space-between">
                  <v-card
                    width="255"
                    height="370"
                    class="ml-15 boxshadow-none border-show border-none"
                  >
                    <v-img
                      height="134"
                      width="255"
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
                  <v-card
                    width="255"
                    height="370"
                    class="ml-6 boxshadow-none border-show border-none"
                  >
                    <v-img
                      height="134"
                      width="255"
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
                      <p class="card-text-font">
                        記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋...
                      </p>
                    </v-card-text>
                  </v-card>
                  <v-card
                    width="255"
                    height="370"
                    class="ml-6 boxshadow-none border-show border-none"
                  >
                    <v-img
                      height="134"
                      width="255"
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
                      <p class="card-text-font">
                        記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋...
                      </p>
                    </v-card-text>
                  </v-card>
                </v-row>
                <v-row class="justify-space-between mt-10">
                  <v-card
                    width="255"
                    height="370"
                    class="ml-15 boxshadow-none border-show border-none"
                  >
                    <v-img
                      height="134"
                      width="255"
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
                      <p class="card-text-font">
                        記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋...
                      </p>
                    </v-card-text>
                  </v-card>
                  <v-card
                    width="255"
                    height="370"
                    class="ml-6 boxshadow-none border-show border-none"
                  >
                    <v-img
                      height="134"
                      width="255"
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
                      <p class="card-text-font">
                        記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋...
                      </p>
                    </v-card-text>
                  </v-card>
                  <v-card
                    width="255"
                    height="370"
                    class="ml-6 boxshadow-none border-show border-none"
                  >
                    <v-img
                      height="134"
                      width="255"
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
                      <p class="card-text-font">
                        記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋記事本文抜粋...
                      </p>
                    </v-card-text>
                  </v-card>
                </v-row>
              </div>

              <div class="mt-10 group4-but">
                <v-btn class="group4-but-but border-none boxshadow-none"
                  >記事一覧を見る <span class="pl-6">></span>
                </v-btn>
              </div>
            </div>
          </v-row>

          <v-row class="group5">
            <h1>新着のお店</h1>
            <div class="group5-ad"></div>
            <div class="group5-div">
              <v-row class="justify-space-between">
                <v-card
                  width="250"
                  height="330"
                  class="ml-10 boxshadow-none border-show border-none"
                >
                  <v-img
                    height="134"
                    width="249"
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
                <v-card
                  width="250"
                  height="330"
                  class="ml-10 boxshadow-none border-show border-none"
                >
                  <v-img
                    height="134"
                    width="249"
                    src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                  ></v-img>
                  <v-card-title class="normal-font-weight-big"
                    >記事タイトル</v-card-title
                  >
                  <v-card-text>
                    <p>東京都/千代田区/九段下</p>
                    <p class="card-text-font">
                      お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文お店紹介文...
                    </p>
                  </v-card-text>
                </v-card>
                <v-card
                  width="250"
                  height="330"
                  class="ml-10 boxshadow-none border-show border-none"
                >
                  <v-img
                    height="134"
                    width="249"
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
              </v-row>
              <v-row class="justify-space-between mt-10">
                <v-card
                  width="250"
                  height="330"
                  class="ml-10 boxshadow-none border-show border-none"
                >
                  <v-img
                    height="134"
                    width="249"
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
                <v-card
                  width="250"
                  height="330"
                  class="ml-10 boxshadow-none border-show border-none"
                >
                  <v-img
                    height="134"
                    width="249"
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
                <v-card
                  width="250"
                  height="330"
                  class="ml-10 boxshadow-none border-show border-none"
                >
                  <v-img
                    height="134"
                    width="249"
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
              </v-row>
              <div class="mt-10 group4-but">
                <v-btn class="group4-but-but border-none boxshadow-none"
                  >記事一覧を見る<span class="pl-6">></span></v-btn
                >
              </div>
            </div>
          </v-row>

          <v-row class="group6 justify-space-between">
            <h1>新着の口コミ</h1>
            <div class="group6-div">
              <v-row>
                <v-card
                  class="
                    group6-card
                    ml-10
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
                  </v-card-text>
                </v-card>
                <v-card
                  class="
                    group6-card
                    ml-16
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
                  </v-card-text>
                </v-card>
              </v-row>

              <v-row class="mt-10">
                <v-card
                  class="
                    group6-card
                    ml-10
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
                  </v-card-text>
                </v-card>
                <v-card
                  class="
                    group6-card
                    ml-16
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
                  </v-card-text>
                </v-card>
              </v-row>
            </div>
          </v-row>
        </v-col>
        <v-col cols="3">
          <v-row class="mt-1 sidebar-group1">
            <v-card
              class="sidebar-group1-card boxshadow-none border-show border-none"
              width="300"
              height="60"
            >
              <p class="mt-5">掲載ご希望の方はコチラ</p>
            </v-card>
            <v-card class="mt-5 boxshadow-none border-show border-none">
              <v-card-title>お知らせ</v-card-title>
              <v-card-text>
                <div>
                  <p class="card-text-font">2022/01/01</p>
                  <p class="card-text-font">
                    テキスト抜粋部分新着情報テキスト抜粋部分新着情報テキスト抜粋部分新着情報テキスト抜粋部分新着情報テキスト...
                  </p>
                </div>
                <div>
                  <p class="card-text-font">2022/01/01</p>
                  <p class="card-text-font">
                    テキスト抜粋部分新着情報テキスト抜粋部分新着情報テキスト抜粋部分新着情報テキスト抜粋部分新着情報テキスト...
                  </p>
                </div>
                <span>お知らせ一覧</span>
              </v-card-text>
            </v-card>
            <div class="slider-ad-one"></div>
            <div class="mt-4">
              <h4><i class="fas fa-crown"></i> カテゴリから探す</h4>
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
                width="300"
                height="60"
              >
                <div>カテゴリ1</div>
              </v-card>
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
                width="300"
                height="60"
              >
                <div>カテゴリ2</div>
              </v-card>
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
                width="300"
                height="60"
              >
                <div>カテゴリ3</div>
              </v-card>
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
                width="300"
                height="60"
              >
                <div>カテゴリ1</div>
              </v-card>
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
                width="300"
                height="60"
              >
                <div>カテゴリ1</div>
              </v-card>
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
                width="300"
                height="60"
              >
                <div>カテゴリ1</div>
              </v-card>
            </div>
            <div class="mt-4">
              <h4><i class="fas fa-crown"></i> 人気の記事</h4>
              <div>
                <div>
                  <v-row class="mx-auto img">
                    <v-col cols="2">
                      <img
                        height="32"
                        width="46.7"
                        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                        alt=""
                      />
                    </v-col>
                    <v-col cols="8">
                      <p>
                        人気の情報タイトル人気の情報タイトル人気の情報タイトル人気の情報タイトル
                      </p>
                    </v-col>
                  </v-row>
                </div>
                <div>
                  <v-row class="mx-auto img">
                    <v-col cols="2">
                      <img
                        height="32"
                        width="46.7"
                        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                        alt=""
                      />
                    </v-col>
                    <v-col cols="8">
                      <p>
                        人気の情報タイトル人気の情報タイトル人気の情報タイトル人気の情報タイトル
                      </p>
                    </v-col>
                  </v-row>
                </div>
                <div>
                  <v-row class="mx-auto img">
                    <v-col cols="2">
                      <img
                        height="32"
                        width="46.7"
                        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                        alt=""
                      />
                    </v-col>
                    <v-col cols="8">
                      <p>
                        人気の情報タイトル人気の情報タイトル人気の情報タイトル人気の情報タイトル
                      </p>
                    </v-col>
                  </v-row>
                </div>
                <div>
                  <v-row class="mx-auto img">
                    <v-col cols="2">
                      <img
                        height="32"
                        width="46.7"
                        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                        alt=""
                      />
                    </v-col>
                    <v-col cols="8">
                      <p>
                        人気の情報タイトル人気の情報タイトル人気の情報タイトル人気の情報タイトル
                      </p>
                    </v-col>
                  </v-row>
                </div>
                <div>
                  <v-row class="mx-auto img">
                    <v-col cols="2">
                      <img
                        height="32"
                        width="46.7"
                        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                        alt=""
                      />
                    </v-col>
                    <v-col cols="8">
                      <p>
                        人気の情報タイトル人気の情報タイトル人気の情報タイトル人気の情報タイトル
                      </p>
                    </v-col>
                  </v-row>
                </div>
                <div>
                  <v-row class="mx-auto img">
                    <v-col cols="2">
                      <img
                        height="32"
                        width="46.7"
                        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                        alt=""
                      />
                    </v-col>
                    <v-col cols="8">
                      <p>
                        人気の情報タイトル人気の情報タイトル人気の情報タイトル人気の情報タイトル
                      </p>
                    </v-col>
                  </v-row>
                </div>
                <div>
                  <v-row class="mx-auto img">
                    <v-col cols="2">
                      <img
                        height="32"
                        width="46.7"
                        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                        alt=""
                      />
                    </v-col>
                    <v-col cols="8">
                      <p>
                        人気の情報タイトル人気の情報タイトル人気の情報タイトル人気の情報タイトル
                      </p>
                    </v-col>
                  </v-row>
                </div>
                <div>
                  <v-row class="mx-auto img">
                    <v-col cols="2">
                      <img
                        height="32"
                        width="46.7"
                        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                        alt=""
                      />
                    </v-col>
                    <v-col cols="8">
                      <p>
                        人気の情報タイトル人気の情報タイトル人気の情報タイトル人気の情報タイトル
                      </p>
                    </v-col>
                  </v-row>
                </div>
                <div>
                  <v-row class="mx-auto img">
                    <v-col cols="2">
                      <img
                        height="32"
                        width="46.7"
                        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                        alt=""
                      />
                    </v-col>
                    <v-col cols="8">
                      <p>
                        人気の情報タイトル人気の情報タイトル人気の情報タイトル人気の情報タイトル
                      </p>
                    </v-col>
                  </v-row>
                </div>
                <div>
                  <v-row class="mx-auto img">
                    <v-col cols="2">
                      <img
                        height="32"
                        width="46.7"
                        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                        alt=""
                      />
                    </v-col>
                    <v-col cols="8">
                      <p>
                        人気の情報タイトル人気の情報タイトル人気の情報タイトル人気の情報タイトル
                      </p>
                    </v-col>
                  </v-row>
                </div>
                <div>
                  <v-row class="mx-auto img">
                    <v-col cols="2">
                      <img
                        height="32"
                        width="46.7"
                        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
                        alt=""
                      />
                    </v-col>
                    <v-col cols="8">
                      <p>
                        人気の情報タイトル人気の情報タイトル人気の情報タイトル人気の情報タイトル
                      </p>
                    </v-col>
                  </v-row>
                </div>
              </div>
            </div>
          </v-row>
          <div class="slider-ad-2"></div>
        </v-col>

        <v-row class="group7" style="margin-top: -15px">
          <v-row>
            <v-col>
              <div class="group7-ad"></div>
            </v-col>
            <v-col class="ml-12">
              <h5>目的からお店を探す</h5>
              <br />
              <p>〜がしたい１</p>
              <p>〜がしたい2</p>
              <p>〜がしたい3</p>
              <p>〜がしたい4</p>
              <p>〜がしたい5</p>
              <p>〜がしたい6</p>
            </v-col>
            <v-col>
              <h5>目的からお店を探す</h5>
              <br />
              <p>〜がしたい１</p>
              <p>〜がしたい2</p>
              <p>〜がしたい3</p>
              <p>〜がしたい4</p>
              <p>〜がしたい5</p>
              <p>〜がしたい6</p>
            </v-col>
            <v-col>
              <h5>会員登録</h5>
              <br />
              <p>お店掲載希望の方</p>
              <p>〜がしたい2</p>
              <p>〜がしたい3</p>
              <p>〜がしたい4</p>
              <p>〜がしたい5</p>
              <p>〜がしたい6</p>
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
  </v-app>
</template>

<style scoped>
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
  font-weight: 700;
  size: 16px;
  line-height: 18.75px;
  letter-spacing: 1%;
}
.border-show-big {
  border: 2px solid #bbbdbf !important;
  /* box-shadow:  */
}
.top-button-group {
  display: flex;
  width: 100%;
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
  width: 300px;
  height: 700px;
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
  width: 300px;
  height: 200px;
  background-color: #e5e5e5;
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
  height: 250px;
  background-color: #e5e5e5;
}
.group6-card {
  height: 280px;
  width: 380px;
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
  width: 830px;
  height: 100px;
  margin-left: 30px;
  margin-top: 10px;
}
.group5 {
  margin-top: 30px;
}
.group4-but {
  margin-left: 350px;
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
  margin-top: 20px;
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
  width: 620px;
  height: 40px;
  margin-left: 110px;
  /* width: 90%; */
}
</style>

<script>
// import HelloWorld from './components/HelloWorld';
// import japanIcon from "./assets/icon/japan.png";

export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
