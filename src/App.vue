<template>
  <div id="app">
    <div class="home-background"></div>
    <div class="home d-flex">
      <b-container class="d-flex align-items-center justify-content-center flex-column">
        <b-card class="text-center"
          bg-variant="light"
          text-variant="black"
          title="Уважаемые собственники помещений!"
        >
       
          <div>
             
            <b-card-text>
              Приглашаем Вас принять участие в общем собрании собственников
              помещений в форме очно-заочного голосования (совместного
              присутствия собственников помещений в данном доме для обсуждения
              вопросов повестки дня и принятия решений по вопросам, поставленным
              на голосование, опросным путем – передачи оформленных в письменной
              форме решений собственников по вопросам повестки дня в место или
              по адресу, указанному в сообщении)
            </b-card-text>
          </div>
          <div class="mt-4 mx-auto text-center">
            <b-button href="#" variant="primary">Корпус 1</b-button>
            <b-button href="#" variant="primary" class="mx-1">Корпус 2</b-button>
            <b-button href="#" variant="primary">Корпус 3</b-button>
          </div>
        </b-card>
      </b-container>
    </div>
  </div>
</template>

<script>
export default {
  name: "app",
  components: {},
};
</script>

<style lang="scss" >
@import url("https://fonts.googleapis.com/css?family=Lato:400,700");

body {
  font-family: "Lato", sans-serif !important;
}
.home {
  background-image: url("./assets/img/main_image.jpg");
  background-position: center;
  background-size: cover;
  height: 100vh;
  &-background {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: black;
    opacity: 50%;

  }
}

.nav-background {
  background: #353535;
}
</style>
