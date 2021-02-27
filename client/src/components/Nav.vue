<template>
  <div class="heading">
    <a><i class="fas fa-bars open" onclick="openNav()"></i></a>
    <i class="fas fa-user-friends logo"></i>
    <button class="title">Close Friends</button> 
    <button class="login">Login</button>
    <button class="signUp">Sign Up</button> 
  
    <div id="nav">
        <ul>
            <li>@username</li>
            <li>+create</li>
            <li>Friends</li>
            <li>Interactions</li>
            <li>Settings</li>
        </ul>
    </div>

  </div>
</template>

<script>
    // import JS from "./components/JS"; *****DON'T KNOW HOW TO ADD JAVASCRIPT TO VUE FILES*****
export default {
    // JS
}
    
</script>

<style>

    .heading {
        width: 100%;
        height: 50px;
        background-color: #e5b102;
        color: #7A5E01;
    }
    .open  {
        font-size: 20px;
        padding: 15px;
        float: left;
        color: #7A5E01;
    }
    .logo {
        font-size: 40px;
        float: left;
        padding-top: 3px;
        padding-left: 100px;
        color: #7A5E01;
    }
    .title {
        border: none;
        background-color: #e5b102;
        padding-bottom: -10px;
        float: left;
        padding: 7px 50px 7px 5px;
        font-family: 'Ranchers', cursive;
        margin: 0;
    }
    button.title {
        color: #7A5E01;
        margin: 0;
    }
    .login, .signUp {
        background-color: #e5b102;
        border: none;
        float: right;
        padding-top: 11px;
        padding-left: 20px;
        padding-bottom: 11px;
        font-family: 'Ranchers', cursive;
        font-size: 20px;
        color: #7A5E01;
    }
    .login {
        padding-right: 80px; 
    }
    .nav {
        display: none;
    }

</style>