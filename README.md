# TECHSTAR-PROJECT (project HAZE)

CANDIDATE LOGIN
---------------
 SIGN IN.html 
 ------------
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,200;0,300;0,400;0,600;1,200;1,600&display=swap" rel="stylesheet">
    <title>SignIn form</title>
    <link rel="stylesheet" href="signIn.css">


</head>
<body>

    <div class="sign-up-form">
        <img src="images/TECHSTAR-GROUP.jpg" alt="Logo">
        <h1>LOG IN</h1>
        <form>
            <input type="email" class="input-box" placeholder="Enter your email">
            <input type="password" class="input-box" placeholder="Enter your password">
            <p><span><input type="checkbox"></span> I agree to the terms and condition</p>
            <button type="button" class="sign-btn" value="submit">SignIn</button>
    
           <button type="button" class="sign-in-button" value="Register"> <a href="signup.html" >Sign up</a></button> 
            <hr>
        </form>
    </div>
    
</body>
</html>


Sign-in.css
-------------


body
{
    margin: 0;
    padding: 0;
    font-family: sans-serif;
    background-image:url(images/techstar\ office.jpg);
    background-size: cover;
    background-position: center;
}
.sign-up-form
{
    width: 400px;
    box-shadow: 0 0 3px 0 rgba(0, 0, 0, 4);
    background: #fff;
    padding: 20px;
    margin: 8% auto 0;
    text-align: center;
    border-radius: 20%;
}
.sign-up-form h1
{
    color: #1c8adb;
    margin-bottom: 30px;
}
.input-box
{
    border-radius: 20px;
    padding: 10px;
    padding-right: 2px;
    padding-left: 2px;
    margin: 10px 0;
    width: 100%;
    border: 1px solid #999;
    outline: none;
    text-align: center

}
button{
    color: #fff;
    width: 100%;
    padding: 10px;
    padding-right: 2px;
    padding-left: 2px;
    border-radius: 20px;
    font-size: 15px;
    margin: 10px 0;
    border: none;
    outline: none;
    cursor: pointer;
}
.sign-btn {
    background-color: #1c8adb;
}

.twitter-btn{
    background-color: #21afde;
}
a{
    text-decoration: none;
}
hr{
    margin-top: 20px;
    width: 80%;
}
.or {
    background: #fff;
    width: 30px;
    margin: -19px auto 10px;
}
img{
    width: 100px;
    margin-top: -50px ;
    border-radius: 20%;

}
.sign-in-button{
    background-color: #68ff96;
}
a{
    color: seashell;
}
@media(max-width:700px){
    .text-box{
        font-size: 20px;
    }
}



sign-up.html
------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,200;0,300;0,400;0,600;1,200;1,600&display=swap" rel="stylesheet">
    <title>sign-up-form</title>
    <link rel="stylesheet" href="signupcss.css">

</head>
<body>
    <div class="form-body">
        <img src="images/TECHSTAR-GROUP.jpg" alt="Logo">
        <h1>Register</h1>
    <form action="register" method="post" enctype="multipart/form-data">
        <label for="Username">Enter the Username</label> <br>
        <input type="text" class="input-box" name="Username"> <br>
        <label for="email">Enter the Email</label> <br>
        <input type="email" class="input-box" name="email"> <br>
        <label for="password">Enter the password</label> <br>
        <input type="password" class="input-box" name="password"> <br>
        <label for="password">Enter the password again</label> <br>
        <input type="password" class="input-box" name="re-password"> <br>
    
        <label for="file">Upload your Resume</label> <br><br>

        <input type="file" name="file" > <br>
    

        <button type="button" class="sign-in-button" value="Register" >SignUp</button> 

        <hr>
        <p class="or">OR</p>
        
        <p>Do you have an account?  <a href="signIn.html">Sign In</a></p>

    </form>
</div>
</body>
</html>


Sign-up.css
-----------
body{
    
    margin: 0;
    padding: 0;
    font-family: sans-serif;
    background-image:url(images/signupimage.jpg);
    background-size: cover;
    background-position: center;
}
.form-body{
    width: 400px;
    box-shadow: 0 0 3px 0 rgba(0, 0, 0, 4);
    background: #fff;
    padding: 20px;
    margin: 8% auto 0;
    text-align: center;
    border-radius: 20%;
}
.form-body h1 {
    color: #1c8adb;
    margin-bottom: 30px;
}



button{
    color: #fff;
    width: 100%;
    padding: 10px;
    border-radius: 20px;
    font-size: 15px;
    margin: 10px 0;
    border: none;
    outline: none;
    cursor: pointer;
}


.sign-in-button{
    background-color: #1c8adb;
}


.twitter-btn{
    background-color: #21afde;
}
.input-box
{
    border-radius: 20px;
    padding: 10px;
    padding-right: 2px;
    padding-left: 2px;
    margin: 9px 0;
    width: 100%;
    border: 1px solid rgb(62, 217, 245);
    outline: none;
}
img{
    width: 100px;
    margin-top: -50px ;
    border-radius: 20%;

}
@media(max-width:700px){
    .form-body{
        font-size: 20px;
    }
}
