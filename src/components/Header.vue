<template>
  <div>
    <b-navbar toggleable type="dark" variant="dark">
      <b-navbar-brand href="#">Институты развития</b-navbar-brand>

      <div>
        <b-nav>
          <div class="number">
            <div class="number-content">
              <div class="number-img">
                <b-icon icon="telephone" style="color: white"></b-icon>
              </div>
              <div class="number-content">
                <span><strong>+7 (423) 280-98-70</strong></span>
              </div>
            </div>
            <div class="number-content">
              <div class="number-img">
                <b-icon icon="telephone" style="color: white"></b-icon>
              </div>
              <div class="number-content">
                <span><strong>+7 967 958 9870</strong></span>
              </div>
            </div>
          </div>
        </b-nav>
      </div>

      <b-collapse id="navbar-toggle-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#" style="color: white">+7 (423) 280-98-70</b-nav-item>
          <b-nav-item href="#" style="color: white">+7 967 958 9870</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <b-card title="Card Title" no-body>
      <b-card-header header-tag="nav">
        <b-nav card-header tabs>
          <b-nav-item to="/some/route/" exact exact-active-class="active">О компании</b-nav-item>
          <b-nav-item to="/some/route/foo" exact exact-active-class="active">Микрозаймы</b-nav-item>
          <b-nav-item to="/some/route/bar" exact exact-active-class="active">Новости</b-nav-item>
          <b-nav-item to="/some/route/bar" exact exact-active-class="active">Вопрос-ответ</b-nav-item>
          <b-nav-item to="/some/route/bar" exact exact-active-class="active">Документы</b-nav-item>
          <b-nav-item to="/some/route/bar" exact exact-active-class="active">Контакты</b-nav-item>
          <b-nav-item to="/some/route/bar" exact exact-active-class="active">Личный кабинет</b-nav-item>
        </b-nav>
      </b-card-header>
    </b-card>
  </div>
</template>

<script>

export default {
name: "Header"
}
</script>

<style scoped>
  .number{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
  }
  .number-content{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    color: white;
    font-size: 1.2rem;
    margin-left: .6rem;
  }
  .number-content:hover{
    color: lightgray;
    transition: .4s;
    cursor: pointer;
  }
</style>