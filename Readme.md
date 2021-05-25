- 👋 Hi, I’m @LAKSHITHA3

- 🌱 I’m currently learning responsive web design
 


<!---
LAKSHITHA3/LAKSHITHA3 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Technical Questionnaire. 
1) To create a navbar.
 code:
 
 
   <!DOCTYPE html>
             
    <html>
             
    <head>
       <style>    
         


 

     


.topnav {

             background-color: Skyblue;
  
             overflow: auto;

             display: flex;
            
             flex-direction:row;

             position: fixed;

             width: 100%;

             }

/* Style the links inside the navigation bar */

             .topnav a {

             color: black;

             text-align: center;

             padding: 18px 16px;

             text-decoration: none;

             font-size: 17px;

             display: inline block;

             }

/* Change the color of links on hover */

             .topnav a:hover {

             background-color: white;

             color: black;

             }

/* Add a color to the active/current link */

             .topnav a.active {

              background-color: Skyblue;

              color: white;

              font-size: 28px;

             }

/* makes logo to be at right and style it with desired width,height and padding*/

             .logo {

             float: left;

             width: 50px;

             height: 50px;

             padding: 10px;

            }

            .ul {

            float: right;

            text-align: right;

            }
            
            
       </style>
     
       
  </head>
       
 <body>


<div class="topnav">

 
<img class="logo" src="https://i.postimg.cc/FKgTrGCp/IMG-20210524-WA0001.jpg" alt="">

<a class="active" href="#IAR Student Council">IAR Student Council</a>

<ul>

    

<a href="#home">Home</a>

<a href="#teams">Teams</a>

<a href="#achievements">Achievements</a>

<a href="#contact us">Contact us</a>

<a href="#about us">About us</a>

</ul>

</div>
</html>
  
2)create a form 
 code:
 <html>
  <head>
   <style>
    

body {

  margin: 0px;

  background-color: #e6ffb3;

  color:#ff1ac6;

  font-family: Arial, Helvetica, sans-serif;

}

.main {

  width: 600px;

  height: auto;

  overflow: hidden;

  padding-bottom: 20px;

  margin-left: auto;

  margin-right: auto;

  border-radius: 5px;

  padding-left: 10px;

  margin-top: 100px;

  border-top: 3px double  #ff1ac6;

  border-bottom: 3px double  #ff1ac6;

  padding-top: 20px;

}

#main table {

  font-family: "Comic Sans MS", cursive;

}

/* css code for textbox */

#main .tb {

  height: 28px;

  width: 230px;

  border: 1px solid #ff1ac6;

  color:  #005ce6;

  font-weight: bold;

  border-left: 1px solid #ff1ac6;

  opacity: 0.9;

}

#main .tb:focus {

  height: 28px;

  border: 1px solid #f26724;

  outline: none;

  border-left: 1px solid ;

}

/* css code for button*/

#main .btn {

  width: 150px;

  height: 32px;

  outline: none;

  color:  #ff1ac6;

  font-weight: bold;

  border: 0px solid  #ff1ac6;

  text-shadow: 0px 0.5px 0.5px #fff;

  border-radius: 2px;

  font-weight: 600;

  color: black;

  letter-spacing: 1px;

  font-size: 14px;

  background-color:  white;

  -webkit-transition: 1s;

  -moz-transition: 1s;

  transition: 1s;

}

#main .btn:hover {

  background-color: violet;

  outline: none;

  border-radius: 2px;

  color:  white;

  border: 1px solid  #ff1ac6;

  -webkit-transition: 1s;

  -moz-transition: 1s;

  transition: 1s;

}

div.fixed {

  position: fixed;

  width:1000px;

}
    </style>
   </head>
   <body>
    <!-- Main div code -->

<div class="fixed">

<div id="main">

  <div class="h-tag">

    <h2>Create Your Account</h>

  </div>

  <!-- create account div -->

  <div class="login">

    <table cellspacing="4" align="center" cellpadding="28" border="0">

      <tr>

        <td align="right">Name :</td>

        <td><input type="text" placeholder="Enter your name here" id="t1" class="tb" /></td>

      </tr>

      <tr>

        <td align="right">Email ID :</td>

        <td><input type="text" placeholder="Enter your Email ID here" id="t2" class="tb" /></td>

      </tr>

      <tr>

        <td align="right">Mobile Number :</td>

        <td><input type="number" placeholder="Enter your Mobile Number here" id="t3" class="tb" required /></td>

      </tr>

      <tr>

        <td align ="right">Enter Password :</td>

        <td><input type="password" placeholder="Enter Password here" id="t4" class="tb" /></td>

      </tr>

      <tr>

        <td></td>

        <td>

          <input type="submit" value="Submit Form" class="btn" onclick="registration()" />

        </td>

      </tr>

    </table>

  </div>

  <!-- create account box ending here.. -->

</div>

</div>

<!-- Main div ending here... -->
 </body>
  </html>
