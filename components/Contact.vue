<template>
  <v-container grid-list-xl>
    <v-layout row wrap justify-center class="my-5">
      <v-flex xs12 sm4>
        <v-card class="elevation-0 transparent">
          <v-card-title primary-title class="layout justify-center">
            <div class="headline">
              会社情報
            </div>
          </v-card-title>
          <v-card-text>
            SZM株式会社は”すずめかわいい”をモットーにおいしいお米を追い求める架空企業です。社員数は3人で日々おいしいお米の研究を行っています。我々はお米のスペシャリストです。今日も農家さんに感謝しながら「いただきます」
          </v-card-text>
        </v-card>
      </v-flex>
      <v-flex xs12 sm4 offset-sm1>
        <v-card class="elevation-0 transparent">
          <v-card-title primary-title class="layout justify-center">
            <div class="headline">
              お問い合わせ
            </div>
          </v-card-title>
          <v-card-text>
            架空企業のウェブサイトですので、お問い合わせは一切受け付けておりません。
          </v-card-text>
          <v-list class="transparent">
            <v-list-tile>
              <v-list-tile-action>
                <v-icon class="blue--text text--lighten-2">
                  phone
                </v-icon>
              </v-list-tile-action>
              <v-list-tile-content>
                <v-list-tile-title>
                  0120-XXX-XXX
                </v-list-tile-title>
              </v-list-tile-content>
            </v-list-tile>
            <v-list-tile>
              <v-list-tile-action>
                <v-icon class="blue--text text--lighten-2">
                  place
                </v-icon>
              </v-list-tile-action>
              <v-list-tile-content>
                <v-list-tile-title>茨城県ひたちなか市</v-list-tile-title>
              </v-list-tile-content>
            </v-list-tile>
            <v-list-tile>
              <v-list-tile-action>
                <v-icon class="blue--text text--lighten-2">
                  email
                </v-icon>
              </v-list-tile-action>
              <v-list-tile-content>
                <v-list-tile-title>
                  hogehoge@example.com
                </v-list-tile-title>
              </v-list-tile-content>
            </v-list-tile>
          </v-list>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>
