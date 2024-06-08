<template>
  <!-- Separación entre componentes -------------------------------------------------------------------------------------------- -->
  <div class="ManualDeSteam">
    <div class="ManualDeSteam-bg">
      <div class="ManualCuatro">
        <div class="Frame2">
          <div class="Frame1"></div>
        </div>
        <div class="Frame7">
          <div class="IntroducciN">Introducción</div>
          <div class="Imagotipo">Imagotipo</div>
          <div class="AplicaciNCromTica">Aplicación cromática</div>
          <div class="TipografA">Tipografía</div>
          <div class="IdentidadDiMica">Identidad dinámica</div>
        </div>
        <div class="Group98">
          <img class="Group" src="../static/ggroup.png">
          <img class="Group-steam" src="../static/steam.png">
        </div>
      </div>
    </div>
    <div class="ManualDeMarca">Manual<br>de marca</div>
  </div>
  <!-- Separación entre componentes -------------------------------------------------------------------------------------------- -->
</template>

<script>
export default {
  name: 'Primero'
}
</script>

<style scoped>
.ManualDeSteam {
  width: 1920px;
  height: 23502px;
  position: relative;
  background: white;
}

.ManualDeSteam-bg {
  width: 1920px;
  height: 1211px;
  position: absolute;
  background: #CB0368;
}

.ManualCuatro {
  width: 2150px;
  height: 1211px;
  position: absolute;
  background: linear-gradient(180deg, #F20444 0%, #2400FF 100%);
}

.Frame2 {
  position: absolute;
  left: 519.50px;
  top: 86.50px;
  display: inline-flex;
  justify-content: flex-start;
  align-items: flex-start;
}

.Frame1 {
  padding: 14px 39px;
}

.Frame7 {
  position: absolute;
  left: 1605px;
  top: 884px;
  display: inline-flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-end;
  gap: 20px;
}

.Frame7 div {
  color: white;
  font-size: 28px;
  font-family: 'BasicCommercial LT Roman';
  font-weight: 400;
  word-wrap: break-word;
}

.Group98 {
  width: 1544.09px;
  height: 437.31px;
  position: absolute;
  left: 235px;
  top: 357px;
}

.Group {
  position: absolute;
  width: 437.11px;
  height: 437.31px;
  left: 0px;
  top: 0px;
}

.Group-steam {
  position: absolute;
  width: 1040.30px;
  height: 302.65px;
  left: 503.79px;
  top: 48.67px;
}

.ManualDeMarca {
  position: absolute;
  left: 1555px;
  top: 113px;
  text-align: right;
  color: white;
  font-size: 64px;
  font-family: 'BasicCommercial LT Roman';
  font-weight: 400;
  line-height: 52.48px;
  word-wrap: break-word;
}
</style>

