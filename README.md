# Login_Cel_Phone
 Login_Cel_Phone

<!--- HTML CODE ---!>

<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital@0;1&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,400;0,500;1,400&display=swap"
        rel="stylesheet">
    <title>Signin</title>
</head>

<body>
    <div>
        <h1 class="login">Login</h1>
        <p class="paragraph">Enter your email address and password to access your acount </p>
        <input class="inputemail" placeholder="Email">
        <input class="inputpass" placeholder="Password">
        <a href="" class="ForgotPass">Forgot Password?</a>
        <button type="button">Login</button>
        <a class="DHA" href=""> Don't have account? <strong>SignUp</strong></a>
    </div>
</body>

<!--- CSS CODE ---!>

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Roboto', sans-serif;  
    background-color: #FFFFFF;
}

.login{

    display: block;
    margin: 128px 277px 12px 16px;
    font-style: normal;
    font-weight: 500;
    font-size: 32px;
    line-height: 41px;
    letter-spacing: 0.41px;
    color:#000000;
}

.paragraph {

    display: block;
    margin-top: 12px;
    margin-left: 16px;
    margin-right: 16px;
    font-weight: normal;
    font-size: 20px;
    line-height: 26px;
    letter-spacing: 0.41px;
    color:#989898;
}

.inputemail{
    
    height: 48px;
    width: 343px;
    left: 16px;
    top: 0px;
    border-radius: 6px;
    border:none;
    margin-top: 102px;
    margin-left:16px;
    background: #F2F2F7;
   
}

.inputpass{

    Width:343px;
    Height:48px;
    top: 60px;
    Left:16px;
    background: #F2F2F7;
    border-radius: 6px;
    border:none;
    margin-top: 12px;
    margin-left:16px;
    
}

input::placeholder{
    
    Height:22px;
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 22px;
    color: #929292;
    padding-left: 10px;
    padding-right: 291px;

}

.ForgotPass{

    display:block;
    Height:22px;
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 22px;
    color: #007AFF;
    margin-left:220px;
    margin-top: 17px;
    text-decoration: none;
   
}

button{
    
    display:block;
    Width:343px;
    Height:48px;
    background: #000000;
    border-radius: 10px;
    font-style: normal;
    font-weight: 500;
    font-size: 17px;
    line-height: 22px;
    text-align: center;
    color: #FFFFFF;
    margin-top:20px;
    margin-left: 16px;
}

.DHA{

    display:block;
    text-align: center;
    width: 375px;
    height: 812px;
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 19px;
    color: rgba(0, 0, 0, 0.51);
    position: absolute;
    width: 225px;
    height: 19px;
    left: 75px;
    top: 754px;
    text-decoration: none;
 
   }

strong{
    
    color: #007AFF;
}

<!--- PRINT-SCREEN----!>

![image](https://user-images.githubusercontent.com/98593048/155897221-bac1025d-e432-4d2a-8ad2-ff0194705605.png)

![image](https://user-images.githubusercontent.com/98593048/155897266-83deccad-8c1b-4a3b-8d8c-aa60ddbbee6a.png)
