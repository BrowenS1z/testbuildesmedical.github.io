<template>
    <div class="container">
        <div class="wrapper">
            <form action="#" class="form">
                <h1 class="auth-title">Вход</h1>
                <nav>
                    <div class="nav nav-tabs" id="nav-tab" role="tablist">
                        <button class="nav-link active" id="nav-default-tab" data-bs-toggle="tab" data-bs-target="#nav-default" type="button" role="tab" aria-controls="nav-default" aria-selected="true">Имя и Пароль</button>
                        <button class="nav-link" id="nav-snils-tab" data-bs-toggle="tab" data-bs-target="#nav-snils" type="button" role="tab" aria-controls="nav-snils" aria-selected="false">СНИЛС</button>
                    </div>
                </nav>

                <div class="tab-content" id="nav-tabContent">
                    <!-- Авторизация через Имя пользователя и Пароль  -->
                    <LoginPage />
                    <!-- Авторизация через СНИЛС -->
                    <SnilsPage />
                </div>
            </form>
        </div>
    </div>
</template>

<script>
import LoginPage from './loginPage.vue'
import SnilsPage from './snilsPage.vue'


export default {
  name: 'App',
  components: {
    LoginPage,
    SnilsPage
  }
}

</script>

<style>
.auth-title{
    text-align: center;
    margin-bottom: 50px;
}

.wrapper{
    display: flex;
    justify-content: center;
}

.form{
    width: 500px;
}

.form nav{
    padding-bottom: 20px;
}

.user-actions{
    display: flex;
    justify-content: space-between;
}

.login-button{
    margin-top: 20px;
    display: flex;
    justify-content: center;
}

.login-button button{
    width: 220px;
}
</style>