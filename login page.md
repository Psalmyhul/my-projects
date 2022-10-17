<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>login page</title>
    <link href="loginpage.css" rel="stylesheet" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
    />
    <link
      rel="termsandcondition"
      href=".../Login setup/terms and
    condition.html"
    />
  </head>
  <body>
    <section action="https://www.google.com/" class="login-box">
      <div>
        <h1>Log in</h1>
      </div>
      <div class="divider-md"></div>
      <div class="thumbnails">
        <a href="https://www.facebook.com" class="fa fa-facebook"></a>
        <a href="https://www.twitter.com/login" class="fa fa-twitter"></a
        ><a href="https://www.google.com" class="fa fa-google"></a>
      </div>
      <div>
        <p id="others">or login using email</p>
      </div>
      <div>
        <label class="info">Email</label>
        <input type="email" class="box" placeholder="xyz@gmail.com" required />
      </div>
      <div>
        <label class="info">Password</label>
        <input type="password" class="box" />
      </div>
      <div class="others2">
        <input type="checkbox" /><label
          >Remember Me
          <a class="remember" href="https://www.google.com"
            ><span class="right">Forget Password?</span></a
          ></label
        >
      </div>
      <div class="submit">
        <input id="submit" type="submit" value="Login" />
      </div>
      <div class="end-note">
        <p>
          <a href="terms and conditions.html">Privacy Policy</a
          ><span class="right"
            ><a href="terms and conditions.html">Terms and Conditions</a></span
          >
        </p>
      </div>
    </section>
  </body>
</html>

?* CSS Components*/
body{
    background-color:antiquewhite;
}
.login-box{
background-color: white;
border: 1px solid green;
width: 400px;
padding: 10px 7px;
margin: 100px auto;
border-radius: 35px;
box-shadow: 5px rgb(42, 236, 42);
font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
h1{
    text-align: center;
    color: green;
    font-weight: bolder;
}
#others{
    font-size: 13px;
    text-align: center;
    margin: 5px;
}
.others2{
   font-size: 13px; 
   margin: 10px 35px 30px 35px;
}
.box{
  width: 350px;
  border:  0px;
  border-radius: 12px;
height: 30px;
margin: 10px 15px;
background-color:rgb(184, 240, 184);
}
.right{
    float:right;
}
.end-note{
  font-size: 13px;
  text-align: left; 
  margin: 10px 35px 30px 35px; 
}
.info{
    text-align: left;
    margin: 15px;
}
#submit{
    margin: 9px 70px;
    height: 40px;
    width: 70%;
    border-radius: 20px;
    border: 0px;
    background-color: rgb(12, 175, 12);
    color: white;
    font-size: 15px;
}
#submit:hover{
    color:rgb(42, 236, 42);
}
.fa{
    padding: 18px 20px;
    font-size: 20px;
    width: 20px;
    text-align: center;
    text-decoration: none;
    border-radius: 50%;
    margin: 5px 10px;
}
.fa-facebook{
    border: 0.5px solid rgb(88, 83, 83);
    
}
.fa-twitter{
    border: 1px solid rgb(88, 83, 83);
    margin: 20px;
}
.fa-google{
    border: 1px solid rgb(88, 83, 83);
}
.divider-md{
height: 8px;
margin: 5px 100px;
width:50%;
background-color:rgb(154, 240, 154);
border-radius: 8px;

}
.thumbnails{
    margin: 5px 60px;
}
.fa-facebook:hover{
    background-color: blue;
    color:white;
}
.fa-twitter:hover{
    background-color: skyblue;
    color: white;
}
.fa-google:hover{
    background-color: #EA4335;
    color: white;
}
.remember:hover{
color:brown;
}

