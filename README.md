# htmlex1
<!--1st assignment of creating a login page using html , css and javascript-->
<!-- HTML CODE -->
<!DOCTYPE html>
<html>
    <head>
        <title>Login Form</title>
        <link rel="stylesheet" type="text/css" href="./style.css">

    </head>
    <body>
          <div class="Login-Form">
              <h1>Login Form</h1>
              <form action="#" method="post">
                  <p>Username</p>
                  <input type="text" name="user" placeholder="User name">
                  <p>Password</p>
                  <input type="password" name="password" placeholder="Password">
                  <script src="./code.js"></script>
                  <p>
                  <button onclick="logind()">Login</button>
                  </p>
              </form>

          </div>
    </body>
</html>

<!--CSS CODE-->
*
{    
     font-family:'Times New Roman' ;
}

body{
    background: url("https://images.unsplash.com/photo-1604090898152-3003bd1ae6df?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80")no-repeat;
    background-size: cover;
} 

 .Login-Form{
  width: 400px;
  height: 500px;
  top: 30%;
  left: 40%;
  transform translate: (-50%,-50%);
  position: absolute;
  color:#fff;

}

.Login-Form h1{
    font-family:serif;
   font-size :70px; 
   text-align: center;
   margin: 40px 0;

}
.Login-Form p{
    font-family:sans-serif;
    font-size: 30px;
    padding:0;

   ]
}
.Login-Form input{
    padding: 12px 20px;
    font-family: Georgia;
    font-size: 25px;
    border-radius: 6px;
    
}
.Login-Form button{
    border-width: 20px;
    font-size: 30px;
}

 <!--Js Code-->
 function logind(){
    alert("Successful Login");
}


