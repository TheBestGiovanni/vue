<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  <h1 class="raulo">Giovanni e l'informatica :D</h1>

  <div class="space"></div>

  <div class="fackerbygionny">
    
    <h1 class="cool">
      Ciao questa è una prova bella!
      Questo testo non ha nessun senso e non ha 
      nessuna ragione di esistere lol
    </h1>

  </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
@import url(https://fonts.googleapis.com/css?family=Anonymous+Pro);

.hello {
  font-family: 'Anonymous Pro', monospace; 
}

.container {
  width: 600px;
  margin: auto;
}

.page {
  display: grid;
  grid-template-columns: 6rem auto;
  grid-template-rows: 2rem auto;
}

.raulo {
  margin-left: 43%;
  /*text-align: center;*/
}

.space {
  height: 300px;
}

.cool {
  margin-left: 15px;
  margin-right: 15px;
  text-align: justify;
}

.fackerbygionny {
  margin-left: 30%;
  margin-right: 30%;
  border-radius: 14px;
  box-shadow:  50px 50px 100px #c8c8c8,
               -50px -50px 100px #ffffff;
  position: relative;
  background: rgba( 255, 255, 255, 0.15 );
  box-shadow: 0 8px 32px 0 rgba( 31, 38, 135, 0.37 );
  backdrop-filter: blur( 20.0px );
  -webkit-backdrop-filter: blur( 20.0px );
  border-radius: 10px;
  border: 1px solid rgba( 255, 255, 255, 0.18 );
  height: 140px;
}
</style>
