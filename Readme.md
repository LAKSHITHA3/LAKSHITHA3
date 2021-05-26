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



             
    
   <link rel=“stylesheet” type=“text/css” href=“styles.css”>.
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
 <!DOCTYPE html>
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
 
 4) Short note on absolute,sticky,fixed position values of position property.
 
 The position property specifies the type of positioning method used for an element.

 An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled.
 An element with position: sticky; is positioned based on the user's scroll position.

A sticky element toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed).
 
 An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).
 
 Example:1

 <!DOCTYPE html>

<html>

<head>

<style>

div.fixed {

  position: fixed;

  bottom: 0;

  right: 0;

  width: 300px;

  border: 3px solid #73AD21;

}

</style>

</head>

<body>

<h>flowers</h>

<p>They are responsible for bringing happiness in our lives and making our surrounding environment a prettier place to live in. Thus, we must all plant flowers at homes and in our neighbourhood to beautify the place and bring happiness and joy for everyone passing by.</p>

<div class="fixed">

This div element has position: fixed;

</div>

</body>

</html>
 
 Example:2
 
 
 <!DOCTYPE html>

<html>

<head>

<style>

div.sticky {

  position: -webkit-sticky;

  position: sticky;

  top: 0;

  padding: 5px;

  background-color: #cae8ca;

  border: 2px solid #4CAF50;

}

</style>

</head>

<body>

<p><b>scrollEssay on Happiness.</p>

<div class="sticky">Be Happy!</div>

<div style="padding-bottom:2000px">

  <p>Happiness is subjective. There is no one way in which the term can be defined. For different people, Happiness holds different connotations. For some, it implies a state of mind; for others, it might mean a standard of lifestyle. Each human being is an independent, free-thinking individual. Everyone has an outlook on life that is different from the other. Hence, the definition of Happiness is also variable for people. However, whatever may be the definition of Happiness, there is no denying that Happiness is an integral part of our lives. Without it, there is no point in living or going about in life.

There is a common phrase that goes: “Money cannot buy happiness.” To some extent, it can be heralded as being valid. However, some people may find it to be false. For a specific section of society, Happiness is defined by wealth. These people tend to consider wealth as the measuring rod for their joys in life. For them, Happiness in life comes from material possession and well-being. Riches, money, jewels, gold, and wealth make them happy; they remain content with these in their lives.

 

For another section of society, wealth does not act as the agent for Happiness in their lives. Many consider Happiness to be a peaceful and calm sense of joy that occurs within one’s mind. For them, it cannot be measured in terms of worldly things. Happiness tends to become a feeling, that can be grasped through the satisfaction of the mind and soul, and not through the pleasure of the body. Happiness, for some, can also imply success. Being ambitious, hardworking, and successful often become ways in which a person obtains Happiness in life.

Whatever be our modes and methods of becoming happy, it tends to keep changing over time. No feeling is absolute. It might happen that the things used to make us comfortable during our childhood, no longer hold the same significance in our lives. This happens because our priorities and our goals change over time. As we grow up, our outlook and vision in life mature, and we no longer base our Happiness on things we used to love previously.

 

Thus the state of being happy largely depends upon what a particular person wants from life. It depends upon a person’s desires and goals in life. Above all and in most cases, indulging in the things that one loves the most becomes the key to a happy life. Hence, love and Happiness are directly linked. Without love, Happiness does not persist. Likewise, without Happiness, love does not persist.

As mentioned, a variety of things make a variety of people happy. There is no right or wrong way to obtain Happiness. Different people have different methods by which they can derive Happiness. All of them are valid; none of them are false or incorrect. Judging people based on what they love and what they hate is not justifiable. We all have different priorities in life, and not all of those are similar. They can be different, but that doesn’t mean they are wrong. Doing anything that makes one feel happy inside out should be considered as valid and rightful.

Essay about HappinessHappiness is subjective. There is no one way in which the term can be defined. For different people, Happiness holds different connotations. For some, it implies a state of mind; for others, it might mean a standard of lifestyle. Each human being is an independent, free-thinking individual. Everyone has an outlook on life that is different from the other. Hence, the definition of Happiness is also variable for people. However, whatever may be the definition of Happiness, there is no denying that Happiness is an integral part of our lives. Without it, there is no point in living or going about in life.

There is a common phrase that goes: “Money cannot buy happiness.” To some extent, it can be heralded as being valid. However, some people may find it to be false. For a specific section of society, Happiness is defined by wealth. These people tend to consider wealth as the measuring rod for their joys in life. For them, Happiness in life comes from material possession and well-being. Riches, money, jewels, gold, and wealth make them happy; they remain content with these in their lives.

 

For another section of society, wealth does not act as the agent for Happiness in their lives. Many consider Happiness to be a peaceful and calm sense of joy that occurs within one’s mind. For them, it cannot be measured in terms of worldly things. Happiness tends to become a feeling, that can be grasped through the satisfaction of the mind and soul, and not through the pleasure of the body. Happiness, for some, can also imply success. Being ambitious, hardworking, and successful often become ways in which a person obtains Happiness in life.

Whatever be our modes and methods of becoming happy, it tends to keep changing over time. No feeling is absolute. It might happen that the things used to make us comfortable during our childhood, no longer hold the same significance in our lives. This happens because our priorities and our goals change over time. As we grow up, our outlook and vision in life mature, and we no longer base our Happiness on things we used to love previously.

 

Thus the state of being happy largely depends upon what a particular person wants from life. It depends upon a person’s desires and goals in life. Above all and in most cases, indulging in the things that one loves the most becomes the key to a happy life. Hence, love and Happiness are directly linked. Without love, Happiness does not persist. Likewise, without Happiness, love does not persist.

As mentioned, a variety of things make a variety of people happy. There is no right or wrong way to obtain Happiness. Different people have different methods by which they can derive Happiness. All of them are valid; none of them are false or incorrect. Judging people based on what they love and what they hate is not justifiable. We all have different priorities in life, and not all of those are similar. They can be different, but that doesn’t mean they are wrong. Doing anything that makes one feel happy inside out should be considered as valid and rightful.

</p>

</div>

</body>

</html>
 
 
 5)create flexboxes.
 <!DOCTYPE html>

<html>

<head>

<style>

.flex-container {

  display: flex;

  justify-content: space-around;

  background-color: lightcoral;

  align-list:center;

}

.flex-container > div {

  background-color:khaki;

  width: 10%;

  margin: 10px;

  text-align: center;

  line-height: 75px;

  font-size: 30px;

}

</style>

</head>

<body>

<div class="flex-container">

  <div style="opacity:0.3">1</div>

  <div style="opacity:0.5">2</div>

  <div>3</div>  

  <div>4</div>

  <div>5</div>

  

</div>

</body>

</html>
 
 
//** part 2 **//
 1)animation of "loading".
 
 <!DOCTYPE html/>
 <html>
  <head>
  <syle>
   
  
  lds-ripple {

   display: inline-block;

   position: relative;

   width: 80px;

   height: 80px;

}

.lds-ripple div {

  position: absolute;

  border: 4px solid red;

  opacity: 1;

  border-radius: 50%;

  animation: lds-ripple 1s cubic-bezier(0, 0.2, 0.8, 1) infinite;

}

.lds-ripple div:nth-child(2) {

  animation-delay: -0.5s;

}

@keyframes lds-ripple {

  0% {

    top: 36px;

    left: 36px;

    width: 0;

    height: 0;

    opacity: 1;

  }

  100% {

    top: 0px;

    left: 0px;

    width: 72px;

    height: 72px;

    opacity: 0;

  }

}
   </style>
   
  </head>
  
  <body>
 <div class="lds-ripple"><div>
  </div><div></div></div>
   </body>
  </html>
 
 
 2)
 
 
 
 
 
