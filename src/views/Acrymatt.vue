<template>
    <div>
        <v-row>
            <!-- <v-col> -->
                <!-- <v-layout> -->
                    <v-card flat color="#BDBDBD" class="rounded-xl mtop mbottom" height="auto" width="35%">
                        <v-row>
                            <!-- <v-col cols="6">
                            </v-col>
                            <v-col cols="6"> -->
                                <v-navigation-drawer floating permanent class="ml-auto mr-4 my-4 rounded-xl">
                                    <v-list dense rounded>
                                        <v-list-item v-for="item in items" :key="item.title" link>
                                            <v-list-item-icon>
                                                    <v-icon>{{ item.icon }}</v-icon>
                                            </v-list-item-icon>
                                            <v-list-item-content>
                                                <v-list-item-title>{{ item.title }}</v-list-item-title>
                                            </v-list-item-content>
                                        </v-list-item>
                                    </v-list>
                                </v-navigation-drawer>
                            <!-- </v-col> -->
                        </v-row>
                    </v-card>
                <!-- </v-layout> -->
            <!-- </v-col>
            <v-col> -->
                <v-layout class="mtop">
                <v-container class="cont">
                    <v-layout class="produ" row wrap>
                        <!-- <v-flex xs12 sm6 lg6 md6 xl4 pa-2 class="essai">
                        <v-hover>
                            <v-img :class="hover ? 'zoom' : ''" src="https://images.unsplash.com/photo-1600585152220-90363fe7e115?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80" class="essaiimg" :aspect-ratio="16/9">
                              <v-container fill-height>
                                <v-row >
                                  <v-col>
                                    <v-text class="name">ACRYMATT-AM010</v-text>
                                  </v-col>
                                </v-row>
                              </v-container>
                            </v-img>
                        </v-hover>
                        </v-flex>
                        <v-flex xs12 sm6 lg6 md6 xl4 pa-2 class="essai">
                        <v-hover>
                            <v-img :class="hover ? 'zoom' : ''" src="https://images.unsplash.com/photo-1600585152220-90363fe7e115?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80" class="essaiimg" :aspect-ratio="16/9">
                              <v-container fill-height>
                                <v-row >
                                  <v-col>
                                    <v-text class="name">ACRYMATT-AM010</v-text>
                                  </v-col>
                                </v-row>
                              </v-container>
                            </v-img>
                        </v-hover>
                        </v-flex>
                        <v-flex xs12 sm6 lg6 md6 xl4 pa-2 class="essai">
                        <v-hover>
                            <v-img :class="hover ? 'zoom' : ''" src="https://images.unsplash.com/photo-1600585152220-90363fe7e115?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80" class="essaiimg" :aspect-ratio="16/9">
                              <v-container fill-height>
                                <v-row >
                                  <v-col>
                                    <v-text class="name">ACRYMATT-AM010</v-text>
                                  </v-col>
                                </v-row>
                              </v-container>
                            </v-img>
                        </v-hover>
                        </v-flex>
                        <v-flex xs12 sm6 lg6 md6 xl4 pa-2 class="essai">
                        <v-hover>
                            <v-img :class="hover ? 'zoom' : ''" src="https://images.unsplash.com/photo-1600585152220-90363fe7e115?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80" class="essaiimg" :aspect-ratio="16/9">
                              <v-container fill-height>
                                <v-row >
                                  <v-col>
                                    <v-text class="name">ACRYMATT-AM010</v-text>
                                  </v-col>
                                </v-row>
                              </v-container>
                            </v-img>
                        </v-hover>
                        </v-flex> -->
                        <v-flex v-for="item in items2" :key="item.kenn" xs12 sm6 lg6 md6 xl4 pa-2 class="rounded-xl essai">
                        <v-hover>
                            <v-img :class="hover ? 'zoom' : ''" :src="item.url" class="rounded-xl essaiimg" :aspect-ratio="16/9">
                              <v-container fill-height>
                                <v-row >
                                  <v-col>
                                    <v-text class="name">{{item.kenn}}</v-text>
                                  </v-col>
                                </v-row>
                              </v-container>
                            </v-img>
                        </v-hover>
                        </v-flex>
                    </v-layout>
                </v-container>
                </v-layout>
                <!-- </v-col> -->
            </v-row>
    </div>
</template>

<script>

  export default {
    name: 'Acrymatt',

  data () {
    return {
      items: [
        { title: 'ACRYMATT PANELS', icon: 'mdi-open-in-new' },
        { title: 'ANTI-SCRATCH ACRYLIC PANELS', icon: 'mdi-open-in-new' },
        { title: 'STANDART ACRYLIC PANELS', icon: 'mdi-open-in-new' },
        { title: 'HIGH GLOSS PANELS', icon: 'mdi-open-in-new' },
        { title: 'SUPER MATT PANELS', icon: 'mdi-open-in-new' },
        { title: 'MELAMINE COATED DOOR SURFACES', icon: 'mdi-open-in-new' },
        { title: 'STEEL DOOR SURFACES', icon: 'mdi-open-in-new' },
        { title: 'PET PANELS', icon: 'mdi-open-in-new' },
        { title: 'INTERIOR DOORS', icon: 'mdi-open-in-new' },
        { title: 'KITCHEN & BATHROOM CABINETS', icon: 'mdi-open-in-new' },
        { title: 'MEVA PREMIUM PANELS', icon: 'mdi-open-in-new' },


      ],
      items2: [
        { kenn:'ACRYMATT-AM010', url:'https://images.unsplash.com/photo-1600585152220-90363fe7e115?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80' },
        { kenn:'ACRYMATT-AM011', url:'https://images.unsplash.com/photo-1600585152220-90363fe7e115?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80' },
        { kenn:'ACRYMATT-AM012', url:'https://images.unsplash.com/photo-1600585152220-90363fe7e115?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80' },
        { kenn:'ACRYMATT-AM013', url:'https://images.unsplash.com/photo-1600585152220-90363fe7e115?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80' },
      ],
    }
  }
  }

</script>


<style scoped>

.marginLeft {
  margin-left: -90px;
}
.mtop {
  margin-top: 100px;
}
.mbottom {
  margin-bottom: 100px;
}
.v-card.borderme {
  border: 2px solid green !important;
}
.v-card.borderout {
  border: 1px solid #d5f0db !important;
}
.v-btn:not(.v-btn--round).v-size--default.add {
  min-width: 0px !important;
}
.theme--light.v-sheet--outlined.mobile {
  border: 2px solid black !important;
}
@media only screen and (max-width: 600px) {
  h2.title1 {
    font-size: 15px;
  }
  h2.title2 {
    font-size: 15px;
  }
  .top {
    margin-top: 20px;
  }
}
@media only screen and (min-width: 600px) {
  .top {
    margin-top: 70px;
  }
}
@media only screen and (min-width: 768px) {
  .top {
    margin-top: 120px;
  }
}

/* @media only screen and (max-width: 1263px) and (min-width: 400px) {
  .produ {
    margin-left:20%;
  }
}
 */

.essaiimg:hover {
  transform: translate3D(0,-1px,0) scale(1.09);
}

.name{
    background-color: #004474;
    color: #fff;
    font-size: 17px;
    font-weight: 600;
    /* left: 20px; */
    padding: 15px 15px 15px 15px; 
    /* top: 90px; */
}

@media only screen and (max-width: 1329px) and (min-width: 1268px) {
  .name{
    background-color: #004474;
    color: #fff;
    font-size: 17px;
    font-weight: 600;
    /* left: 20px; */
    padding: 10px 10px 10px; 
    /* top: 90px; */
}
}

@media only screen and (max-width: 1267px) and (min-width: 935px) {
  .name{
    background-color: #004474;
    color: #fff;
    font-size: 12px;
    font-weight: 600;
    /* left: 20px; */
    padding: 5px 5px 5px; 
    /* top: 90px; */
}
}

@media only screen and (max-width: 934px) and (min-width: 400px) {
  .name{
    display:none;
}
.namee{
    background-color: #004474;
    color: #fff;
    font-size: 12px;
    font-weight: 600;
    /* left: 20px; */
    padding: 5px 5px 5px; 
    /* top: 90px; */
}
}

    

</style>