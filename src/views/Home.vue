<template>
  <div class="home">
    <br>
    <h1 style="text-align:center;color:darkblue;font-size:40px">Prodaja uređaja PRUR</h1>
    <br>
    <v-parallax
      dark
      src="..\assets\Pozadina.jpg"
      style="height:500px"
    >
      
    </v-parallax>
    <v-container>
    <br> <br> <br>

    <p id="text" style="text-align:center;font-size:30px" class = "indigo lighten-1">
      <b>LINK ZA VIZIJU:</b> <a href ="https://docs.google.com/document/d/1wjlTuFE9WsNjAdaUO1eB5VC4M6KlusyK/edit" 
      target="_blank"
      style="color:white">Vizija</a>
    </p>

    <br><br><br>
    <v-row>
      <v-col cols="7" style="padding-left:250px">
    <v-img 
    src="..\assets\Ivona.jpg"
    style="height:200px;width:200px">
    </v-img>
    <p id="text">
      <br>
      <b>Ivona Krezić</b><br>
      Studentica 3. godine informatike<br>
      Imam 22 godine, dolazim iz Mostara. <br>
      Slobodno vrijeme nastojim iskoristiti što <br>
      efektivnije, tako da se bavim sportom, <br>
      vozim biciklo, boksam, družim se sa <br>
      prijateljima, putujem, te učim <br>
      uvijek nešto novo pretražujući internet.
    </p>
      </v-col>
      <v-col>
    <v-img 
    src="..\assets\Elizabeta.jpg"
    style="height:200px;width:200px">
    
    </v-img>
    <p id="text">
      <br>
      <b>Elizabeta Miličević</b><br>
      Studentica 3. godine informatike<br>
      Imam 21 godinu, dolazim iz Kiseljaka. <br>
      U slobodno vrijeme volim crtati, svirati klavir, <br>
      čitati knjige i provoditi vrijeme sa svojim <br>
      prijateljima.
    </p>
      </v-col>
    </v-row>

    <br><br><br>

    <h3 class = "indigo lighten-1">O našem projektu:</h3>
    <p id="text">

      <br>
      Cilj našek projekta je napraviti pouzdanu stranicu za prodaju i kupovinu uređaja kao što su računala
      , laptopi, mobiteli, te tableti. Na ovoj web aplikaciji korisnici će moći praviti svoje profile kojima će moći 
      kupovati ili prodavati svoje nove ili korištene uređaje.

    </p>
    <br><br>
    <h3 class = "indigo lighten-1">Motivacija:</h3>
    <p id="text">
      <br>
      Želimo testirati naše znanje i naučiti više o kreiranju stranica na internetu uz pomoć novih tehnologija.
      
    </p>
    <br> <br>
    <h4 class = "indigo lighten-1">Tehnologije koje ćemo koristiti u ovome projektu su:</h4>
    <p id="text">
      <br><br>
      <v-row>
        <v-col>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>Vue.js</li>
        <li>PHP</li>
      </ul>
        </v-col>
        <v-col>
          <v-img src ="https://i.pinimg.com/originals/4a/75/25/4a7525f0f00df7f2aac5604b10cab82c.png"
          style="height:150px;width:250px"
          >
          </v-img>
        </v-col>
      </v-row>
    </p>

    </v-container>
  </div>
</template>

<style scoped>
#text{
  font-family: 'Times New Roman', Times, serif; 
}
</style>

<script>
export default {
  name: 'Home',
  
}
</script>
