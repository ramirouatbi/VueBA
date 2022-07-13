<template>
    <div>
         <Navbar2/>
        <v-img src="@/assets/room.jpg" height="600" width="auto">
            <v-container fill-height>
                <v-row>
                    <v-col  align="center">
                        <div> 
                            <router-link class="aa" to="/">Home</router-link> / 
                            <router-link class="aa" to="#">{{ $route.name }}</router-link> 
                        </div>
                    </v-col>
                </v-row>
            </v-container>
        </v-img>
       <div class="block">
             <v-container>
                <h2 class="titlega text-center">Products</h2>
             </v-container>
        </div>
        <v-container class="cont">
    <v-layout row wrap class="bords">
        <v-flex xs12 sm6 md4 lg3 xl3>
          <div class="flip-card">
                <div class="flip-card-inner">
                  <div class="flip-card-front">
                    <v-img class="white--text align-center" gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container>
                        <!-- <v-row>
                            <v-col justify="center" align="center">
                              <i class='fas fa-info-circle fa-3x icon' style='color: white'></i>
                              
                            </v-col>
                        </v-row> -->
                        <!-- <v-row>
                          <v-col justify="center" align="center"> -->
                              	 <h1 class="text-center font-size">ACRYMATT PANELS</h1>
            <div class="text-center mt-2">
              <v-btn class="white--text caption"  href="/shop" text> DETAILS  <v-icon class="white--text caption mx-2">mdi-information-outline</v-icon></v-btn>
            </div>
                          <!-- </v-col>
                        </v-row> -->
                      </v-container>
                    </v-img>
                  </div>
                   <div class="flip-card-back">
                    <v-img gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container fill-height>
                        <v-row>
                            <v-col justify="center" align="center">
                              <v-btn rounded x-large color="indigo darken-1 white--text" class="goProduct" to="/acrymatt">GO TO PRODUCT</v-btn>
                            </v-col>
                        </v-row>
                      </v-container>
                    </v-img>
                  </div>
                </div>
            </div>
        </v-flex>
          <v-flex xs12 sm6 md4 lg3 xl3>
          <div class="flip-card">
                <div class="flip-card-inner">
                  <div class="flip-card-front">
                    <v-img class="white--text align-center" gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container>
                        <!-- <v-row>
                            <v-col justify="center" align="center">
                              <i class='fas fa-info-circle fa-3x icon' style='color: white'></i>
                              
                            </v-col>
                        </v-row> -->
                        <!-- <v-row>
                          <v-col justify="center" align="center"> -->
                              	 <h1 class="text-center font-size">ANTISCRATCH ACRYLIC PANELS</h1>
            <div class="text-center mt-2">
              <v-btn class="white--text caption"  href="/shop" text> DETAILS  <v-icon class="white--text caption mx-2">mdi-information-outline</v-icon></v-btn>
            </div>
                          <!-- </v-col>
                        </v-row> -->
                      </v-container>
                    </v-img>
                  </div>
                   <div class="flip-card-back">
                    <v-img gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container fill-height>
                        <v-row>
                            <v-col justify="center" align="center">
                              <v-btn rounded x-large color="indigo darken-1 white--text" class="goProduct" to="/acrymatt">GO TO PRODUCT</v-btn>
                            </v-col>
                        </v-row>
                      </v-container>
                    </v-img>
                  </div>
                </div>
            </div>
        </v-flex>
        <v-flex xs12 sm6 md4 lg3 xl3>
          <div class="flip-card">
                <div class="flip-card-inner">
                  <div class="flip-card-front">
                    <v-img class="white--text align-center" gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container>
                        <!-- <v-row>
                            <v-col justify="center" align="center">
                              <i class='fas fa-info-circle fa-3x icon' style='color: white'></i>
                              
                            </v-col>
                        </v-row> -->
                        <!-- <v-row>
                          <v-col justify="center" align="center"> -->
                              	 <h1 class="text-center font-size">ACRYMATT PANELS</h1>
            <div class="text-center mt-2">
              <v-btn class="white--text caption"  href="/shop" text> DETAILS  <v-icon class="white--text caption mx-2">mdi-information-outline</v-icon></v-btn>
            </div>
                          <!-- </v-col>
                        </v-row> -->
                      </v-container>
                    </v-img>
                  </div>
                   <div class="flip-card-back">
                    <v-img gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container fill-height>
                        <v-row>
                            <v-col justify="center" align="center">
                              <v-btn rounded x-large color="indigo darken-1 white--text" class="goProduct" to="/acrymatt">GO TO PRODUCT</v-btn>
                            </v-col>
                        </v-row>
                      </v-container>
                    </v-img>
                  </div>
                </div>
            </div>
        </v-flex>
         <v-flex xs12 sm6 md4 lg3 xl3>
          <div class="flip-card">
                <div class="flip-card-inner">
                  <div class="flip-card-front">
                    <v-img class="white--text align-center" gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container>
                        <!-- <v-row>
                            <v-col justify="center" align="center">
                              <i class='fas fa-info-circle fa-3x icon' style='color: white'></i>
                              
                            </v-col>
                        </v-row> -->
                        <!-- <v-row>
                          <v-col justify="center" align="center"> -->
                              	 <h1 class="text-center font-size">HIGH GLOSS PANELS</h1>
            <div class="text-center mt-2">
              <v-btn class="white--text caption"  href="/shop" text> DETAILS  <v-icon class="white--text caption mx-2">mdi-information-outline</v-icon></v-btn>
            </div>
                          <!-- </v-col>
                        </v-row> -->
                      </v-container>
                    </v-img>
                  </div>
                   <div class="flip-card-back">
                    <v-img gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container fill-height>
                        <v-row>
                            <v-col justify="center" align="center">
                              <v-btn rounded x-large color="indigo darken-1 white--text" class="goProduct" to="/acrymatt">GO TO PRODUCT</v-btn>
                            </v-col>
                        </v-row>
                      </v-container>
                    </v-img>
                  </div>
                </div>
            </div>
        </v-flex>
        <v-flex xs12 sm6 md4 lg3 xl3 class="animate__animated animate__backInUp essai">
          <div class="flip-card">
                <div class="flip-card-inner">
                  <div class="flip-card-front">
                    <v-img class="white--text align-center" gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container>
                        <!-- <v-row>
                            <v-col justify="center" align="center">
                              <i class='fas fa-info-circle fa-3x icon' style='color: white'></i>
                              
                            </v-col>
                        </v-row> -->
                        <!-- <v-row>
                          <v-col justify="center" align="center"> -->
                              	 <h1 class="text-center font-size">ACRYMATT PANELS</h1>
            <div class="text-center mt-2">
              <v-btn class="white--text caption"  href="/shop" text> DETAILS  <v-icon class="white--text caption mx-2">mdi-information-outline</v-icon></v-btn>
            </div>
                          <!-- </v-col>
                        </v-row> -->
                      </v-container>
                    </v-img>
                  </div>
                   <div class="flip-card-back">
                    <v-img gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container fill-height>
                        <v-row>
                            <v-col justify="center" align="center">
                              <v-btn rounded x-large color="indigo darken-1 white--text" class="goProduct" to="/acrymatt">GO TO PRODUCT</v-btn>
                            </v-col>
                        </v-row>
                      </v-container>
                    </v-img>
                  </div>
                </div>
            </div>
        </v-flex>
        <v-flex xs12 sm6 md4 lg3 xl3 class="animate__animated animate__backInUp essai">
          <div class="flip-card">
                <div class="flip-card-inner">
                  <div class="flip-card-front">
                    <v-img class="white--text align-center" gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container>
                        <!-- <v-row>
                            <v-col justify="center" align="center">
                              <i class='fas fa-info-circle fa-3x icon' style='color: white'></i>
                              
                            </v-col>
                        </v-row> -->
                        <!-- <v-row>
                          <v-col justify="center" align="center"> -->
                              	 <h1 class="text-center font-size">ACRYMATT PANELS</h1>
            <div class="text-center mt-2">
              <v-btn class="white--text caption"  href="/shop" text> DETAILS  <v-icon class="white--text caption mx-2">mdi-information-outline</v-icon></v-btn>
            </div>
                          <!-- </v-col>
                        </v-row> -->
                      </v-container>
                    </v-img>
                  </div>
                   <div class="flip-card-back">
                    <v-img gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container fill-height>
                        <v-row>
                            <v-col justify="center" align="center">
                              <v-btn rounded x-large color="indigo darken-1 white--text" class="goProduct" to="/acrymatt">GO TO PRODUCT</v-btn>
                            </v-col>
                        </v-row>
                      </v-container>
                    </v-img>
                  </div>
                </div>
            </div>
        </v-flex>
        <v-flex xs12 sm6 md4 lg3 xl3 class="animate__animated animate__backInUp essai">
          <div class="flip-card">
                <div class="flip-card-inner">
                  <div class="flip-card-front">
                    <v-img class="white--text align-center" gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container>
                        <!-- <v-row>
                            <v-col justify="center" align="center">
                              <i class='fas fa-info-circle fa-3x icon' style='color: white'></i>
                              
                            </v-col>
                        </v-row> -->
                        <!-- <v-row>
                          <v-col justify="center" align="center"> -->
                              	 <h1 class="text-center font-size">ACRYMATT PANELS</h1>
            <div class="text-center mt-2">
              <v-btn class="white--text caption"  href="/shop" text> DETAILS  <v-icon class="white--text caption mx-2">mdi-information-outline</v-icon></v-btn>
            </div>
                          <!-- </v-col>
                        </v-row> -->
                      </v-container>
                    </v-img>
                  </div>
                   <div class="flip-card-back">
                    <v-img gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container fill-height>
                        <v-row>
                            <v-col justify="center" align="center">
                              <v-btn rounded x-large color="indigo darken-1 white--text" class="goProduct" to="/acrymatt">GO TO PRODUCT</v-btn>
                            </v-col>
                        </v-row>
                      </v-container>
                    </v-img>
                  </div>
                </div>
            </div>
        </v-flex>
        <v-flex xs12 sm6 md4 lg3 xl3 class="animate__animated animate__backInUp essai">
          <div class="flip-card">
                <div class="flip-card-inner">
                  <div class="flip-card-front">
                    <v-img class="white--text align-center" gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container>
                        <!-- <v-row>
                            <v-col justify="center" align="center">
                              <i class='fas fa-info-circle fa-3x icon' style='color: white'></i>
                              
                            </v-col>
                        </v-row> -->
                        <!-- <v-row>
                          <v-col justify="center" align="center"> -->
                              	 <h1 class="text-center font-size">ACRYMATT PANELS</h1>
            <div class="text-center mt-2">
              <v-btn class="white--text caption"  href="/shop" text> DETAILS  <v-icon class="white--text caption mx-2">mdi-information-outline</v-icon></v-btn>
            </div>
                          <!-- </v-col>
                        </v-row> -->
                      </v-container>
                    </v-img>
                  </div>
                   <div class="flip-card-back">
                    <v-img gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)" src="https://images.pexels.com/photos/2440471/pexels-photo-2440471.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" :aspect-ratio="9/16">
                      <v-container fill-height>
                        <v-row>
                            <v-col justify="center" align="center">
                              <v-btn rounded x-large color="indigo darken-1 white--text" class="goProduct" to="/acrymatt">GO TO PRODUCT</v-btn>
                            </v-col>
                        </v-row>
                      </v-container>
                    </v-img>
                  </div>
                </div>
            </div>
        </v-flex>
    </v-layout>
   </v-container>
   <Formular/> 
   <Footer/> 
    </div>
</template>

<script>

    import Navbar2 from '../components/Navbar2'
    import Footer from '../components/Footer'
    import Formular from '../components/Formular'

  export default {
    

    name: 'Produkte',

    components: {
        Navbar2,
        Footer,
        Formular,
    },
    data(){
        return{
          products:[
          {id:1,title:'Acrmymatt Panels', url:'https://images.pexels.com/photos/833045/pexels-photo-833045.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1'},
          {id:2,num:'Matt Panels',url:'https://images.pexels.com/photos/7614546/pexels-photo-7614546.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1'},
          {id:3,num:'Kitchen and Bathrooms Cabinets', url:'https://images.pexels.com/photos/3315291/pexels-photo-3315291.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1'},
          {id:4,num:'Interior Doors',url:'https://images.pexels.com/photos/813688/pexels-photo-813688.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1'},
          {id:5,num:'Standart Panels',url:'https://images.pexels.com/photos/1454805/pexels-photo-1454805.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1'},
        ],
    }
    }
    
  }
</script>

<style scoped>


h1,
.h1,
h2,
.h2,
h3,
.h3,
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  font-family: headings-font-family;
  font-weight: 500;
  margin: 0 0 0.5em;
  color: headings-color;
}

h2,
.h2 {
  font-size: 20px;
}


.block {
  padding: 60px 0;
  border-bottom: 1px solid darken(white, 10%);

  @media only screen and (max-width: 599px) {
    padding: 20px 0;
  }}

.titlega{
    font-size: 30px;
    padding: 0 0 10px;
    margin: 0 0 40px;
    position: relative;
  

    @media only screen and (max-width: 599px) {
      font-size: 24px;
      padding: 0 0 5px;
      margin: 0 0 25px;
    }}

    .titlega::after {
      content: '';
      background: black;
      width: 60px;
      height: 1px;
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);

      @media only screen and (max-width: 599px) {
        width: 30px;
      }
    }

    .cont{
        flex-wrap: wrap;
    }

  .bords{
    margin-left: 10%;
    margin-right: 10%;
  }

  .flip-card {
  background-color: transparent;
  perspective: 1000px;
}

.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.6s;
  transform-style: preserve-3d;
}

.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.flip-card-back {
  background-color: #2980b9;
  color: white;
  transform: rotateY(180deg);
}

.essai{
  margin-bottom: 60%;
  margin-top:44%;
}
  
</style>