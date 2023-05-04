<template>
    <div class="login-nav">
        <nav>
            <a href="">Food</a>
            <a href="">Exercise</a>
            <a href="">Community</a>
            <a href="">Premium</a>
            <a href="">App</a>
            <a href="">blog</a>
        </nav>
    </div>
    <div class="login">
        <div class="box">
        <form>
            <p>Members Login</p>
            <input type="text" required placeholder="Email Address">
            <input type="text" placeholder="password">

        </form>
        <button class="login-button">Log in</button>
        <p>or</p>
        <button>Log in With Facebook</button>    
    </div>
    <p class="member-info">Not A Member Yet <a class="signup-link" href="">Sign Up</a></p>

    </div>
</template>
<style scoped>
nav {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 30px;
    height: 8vh;
}
nav a {
    text-decoration: none;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #fff;
    font-weight: 700;
    font-size: 12px;
    height: 8vh;
    width: 15vh;
    text-transform: uppercase;
    font-family: 'Barlow', sans-serif, 'Inter', sans-serif, 'Lato', sans-serif, 'Noto Sans JP', sans-serif, 'Ubuntu', sans-serif;

    
}
nav a:hover {
    background: rgb(20, 20, 46);
    
}
form {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 10px;
}
input {
    width: 280px;
    height: 40px;
    padding-left: 10px;
    border-color: rgb(178, 178, 230);
    border-radius: 4px;
    
}
.login-button {
    width: 280px;
    height: 30px;
    background: rgb(64, 64, 193);
    color: #fff;
    border: none;
    cursor: pointer;
    border-radius: 4px;
    

}
button {
    width: 280px;
    height: 30px;
    background: rgb(121, 121, 230);
    color: #fff;
    border: none;
    cursor: pointer;
    border-radius: 4px;
}

.login-nav {
    display: flex;
    justify-content: center;
    align-items: center;
    background: rgb(64, 64, 193);
}
.login {
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    margin-top: 50px;
    gap: 20px;
    
}
.box {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 360px;
    height: 360px;
    border-radius: 10px;
    box-shadow: -2px 5px 5px 8px #eae7e7;
    gap: 10px;

}
.box p {
    font-family: 'Barlow', sans-serif, 'Inter', sans-serif, 'Lato', sans-serif, 'Noto Sans JP', sans-serif, 'Ubuntu', sans-serif;
    font-weight: 400;
    font-size: 19px;
    color: #000;

}

.signup-link {
    color: rgb(109, 109, 224);
    font-family: 'Barlow', sans-serif, 'Inter', sans-serif, 'Lato', sans-serif, 'Noto Sans JP', sans-serif, 'Ubuntu', sans-serif;
    font-weight: 600;
    font-size: 12px;
}
.member-info {
    font-size: 12px;
    font-family: 'Barlow', sans-serif, 'Inter', sans-serif, 'Lato', sans-serif, 'Noto Sans JP', sans-serif, 'Ubuntu', sans-serif;
    font-weight: 700;
    color: #000;
}
</style>