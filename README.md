<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anurag Sharma</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            font-family: 'Poppins',sans-serif;
            box-sizing: border-box;
        }


        .tile{
font-family:Verdana, Geneva, Tahoma, sans-serif;
margin-left: 50px;
margin-top: 10px;
        }
        body{
            background: #000000;
            color: #fff;
        }
        #header{
            margin-top: 20px;
            width: 100%;
            height: 10vh;
            background-size: cover;
            background-position: center;
            
        }
       .img{
        height: 100vh;
        width: 125vh;
        border-radius: 800px;
        margin-left: 593px;
       }
       .hj {
  font-size: 4rem;
  margin-top: 100px;
  margin-left: 20px;
}

span {
  color: rgb(142, 3, 3);
  display: inline-flex;
  align-items: center;
  font-size: 120px;
}

span::after {
    content: '';
    display: inline-block;
    width: 3px;
    background-color: brown;
    margin-left: 4px;
    
}

h1 span::after {
    height: 150px;
}
.head{
    
    padding: 10px;
    color: #000000;
    display: flex;
    justify-content:space-between;
    height: 60px;
    background-color: rgb(179, 175, 175);
}
.ul{
    display: flex;
    justify-content: space-between;
    list-style: none;
}
.li{
    height: 20px;
    width: 100px;
    background-color: rgb(179, 175, 175);;
    color: #ffffff;
    margin: 10px;
    font-size: large;
    font-family: Verdana, Geneva, Tahoma, sans-serif;

    font-weight: bolder;
text-decoration: none;
text-decoration-color: #fff;
}
.li:hover{
    color: red;
    cursor: pointer;
}
.immg{
    position: absolute;
    left: 35%;
    display: none;
    border: 5px solid black;
}
.resimg{
    z-index: 0;
}
.X{
    height: 33px;
    width: 51px;
    position: absolute;
    z-index: 1;
font-size:large;
    left: 62%;
    
}

.pg{
    display: flex;
    flex-wrap: wrap;
    margin-top: 30px;
    
}
.provid{
    height: 450px;
    width: 380px;
   background: linear-gradient(180deg,rgb(196, 177, 177),rgb(34, 192, 176));
    margin-left: 100px;
    border-radius: 50px;
    padding: 10px;
}
video{
    cursor: pointer;
}
.form{
    display: flex;
    flex-direction: column;
    
}
#name{
    width: 430px;
    height: 60px;
    border-radius: 8px;
    background-color: rgb(24, 255, 178);
    font-size: x-large;
    margin-bottom: 20px;
    padding: 10px;
    border: none;
    
}
#email{
    width: 430px;
    height: 60px;
    border-radius: 8px;
    background-color: rgb(24, 255, 178);
    font-size: x-large;
    margin-bottom: 20px;
    padding: 10px;
    border: none;
}
#mess{
    width: 430px;
    height: 80px;
    padding: 10px;
    border-radius: 8px;
    border: none;
    margin-bottom: 20px;
    background-color: rgb(24, 244, 171);
    font-size: x-large;
}
#button{
    width: 480px;
    height: 40px;
    color: #fff;
    border-radius: 8px;
    background-color: rgb(0, 0, 0);
    font-size: x-large;
    width: 100px;
    margin-left: 170px;
    
}
#button:hover{
    background-color: green;
}
.cwn{
    margin-top: 50px;
    margin-left: 480px;
    height: 390px;
    padding: 50px;
    margin-bottom: 150px;
    width: 520px;
    background-color: rgb(210, 245, 245);
    border-radius: 50px;
}
    
        .logo {
            display: flex;
            justify-content: space-around;
            margin: 20px 0;
        }
        .progall{
            margin-top: 350px; font-size: 80px; margin-left: 430px; color: rgb(142, 3, 3); font-family: Verdana, Geneva, Tahoma, sans-serif; margin-bottom: 50px;
        }
        .cont{
            margin-top: 40px; font-size: 70px; color: rgb(142, 3, 3); margin-left: 550px;
        }
        @media only screen and (max-width: 768px) {
            video{
                height:200px;
                width: 200px;
            }
            h1 span::after {
    height: 50px;
}
            .head {
                flex-direction: column;
                align-items: center;
                text-align: center;
            }
            .progall{
                margin-top: 10px;
            }
            .immg{
                height: 300px;
                width: 30px;
                left: 0%;
            }

            .ul {
                flex-direction: column;
                align-items: center;
            }

            .img {
                width: 100%;
                height: auto;
                margin-left: 0;
                border-radius: 0;
            }

            .hj {
                font-size: 2rem;
                margin-top: 250px;
                margin-left: 0;
                text-align: center;
            }
            span {
                font-size: 2.5rem;
            }
            #th1,#th2,#th3{
                font-size: small;
            }
            .resimg{
                width: 300px;
                height: 400px;
                top: 30%;
            }

            .pg {
                flex-direction: column;
                align-items: center;
            }

            .provid {
                width: 70%;
                margin: 20px 0;
              
            }

            .cwn {
                width: 90%;
                margin: 50px auto;
            }
            .tile{
                font-size: smaller;
            }
            .progall{
                margin-left: 0;
                font-size: 2rem;
            }
            .cont{
                margin-left: 0;
                font-size: 2rem;
            }
            #name,#email,#mess{
                width: 200px;
            }
        }

    </style>

</head>
<body style="padding: 0; margin: 0;">
    
    <div class="immg">
        <button class="X" style="margin-left: 50px; cursor: pointer; background-color: red;">Close</button>

        <img src="assets/anures.png" alt="" height="700px" width="500px" class="resimg">
    </div>
    <div class="head" style="width: 100%; height: 80px; background-color: black; color: rgb(142, 3, 3);; font-size: 40px;" ><h1 class="tile">Anurag Sharma</h1>
    
    </div>
    
    <div id="header">
         <img src="assets/anuport.jpg" alt="" class="img">
    </div>
    <div>    <h1 class="hj">I am <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="span"></span></h1>
    </div>
    <br><br><br><br>
    <button id="res" style="height: 50px; width: 180px; background-color: aqua; font-size: 20px; font-family: Verdana, Geneva, Tahoma, sans-serif; margin-left: 80px; border-radius: 20px; cursor: pointer;">View Resume</button>
   <div class="skill">
<div class="outer">
    <div class="inner">
        <div id="number">
          
        </div>
    </div>
</div>

   </div>
   <h1 class="progall">Project Gallery</h1>

   <div class="pg">
    <div class="provid">
        <video src="assets/Document and 3 more pages - Personal - Microsoft_ Edge 2024-10-18 22-11-27.mp4" controls height="250px" width="350px" style="border-radius: 50px;" autoplay loop id="vid"></video>
        <h2 style="color: rgb(0, 0, 0); text-align: center;" id="th1">This project is based on expense tracking. In which you can easily add your daily expense. Skills that i have used is HTML,CSS,JS and Json</h2>
    </div>
    <div class="provid">
        <video src="assets/Document - Google Chrome 2024-05-16 12-31-11 (1).mp4" controls height="250px" width="350px" style="border-radius: 50px;" id="vid" autoplay loop></video>
        <h2 style="color: rgb(0, 0, 0); text-align: center;" id="th2">This project is based on weather forecating in which you can easily check weather of your city. Skills that i have use is HTML,CSS, JS, use web api to fetch data.</h2>
    </div>
    <div class="provid">
        <video src="assets/phonebook python - GDB online Debugger _ Code, Compile, Run, Debug online C, C and 4 more pages - Personal - Microsoft_ Edge 2024-09-21 17-28-48.mp4"id="vid" controls height="250px" width="350px" style="border-radius: 50px;" autoplay loop></video>
        <h2 style="color: rgb(0, 0, 0); text-align: center;" id="th3">This project is phonebook. In which you can add, delete, search contacts. I use Python skills in this project.</h2>
    </div>
   </div>
   <h1 class="cont">Contact Me</h1>
   <div class="cwn">
    <form action="https://api.web3forms.com/submit" method="post" class="form">
        <input type="hidden" name="access_key" value="7b6d95ff-4552-450f-a86c-dacafe74e37e">

        <input type="text" name="name"  placeholder="Your Name" required id="name">
        <input type="email" name="email"  placeholder="Enter your E-mail" required id="email">
        <textarea name="message" id="mess" cols="30" rows="10" placeholder="Your message" required></textarea>
        <button id="button">Submit</button>

    </form>
   </div>
   <div class="logo" style="display: flex; justify-content: space-around;">
   <a href="https://www.linkedin.com/feed/" target="_blank"><img src="assets/inlogo2.jpeg" alt="" class="inlogo" height="50px" ></a>
   <a href="https://github.com/" target="_blank"><img src="assets/git1.jpeg" alt="" class="inlogo" height="50px" ></a>
   <a href="https://www.instagram.com/anu.sharma2006/?next=%2F"><img src="assets/iglogo.webp" alt="" class="inlogo" height="50px"></a>
   </div>
</body>
<script>
    const x=document.querySelector(".X");
    const rs=document.querySelector("#res");
    const immg=document.querySelector(".immg");
rs.addEventListener('click',()=>{
   immg.style.display='block';   
})
x.addEventListener('click',()=>{
    immg.style.display='none';
})
    const span=document.querySelector('.span');
    let arr=['Developer.','Student.','Coder.'];
    let i=0;
    let j=0;
    let count=0;
    let k=setInterval(()=>{
      
        if(i===arr.length)
        {
            return
        }
        if(arr[i].length>=count+1){
        span.innerText=span.innerText+arr[i][j];
        j++;
        count++;
        }
        else{
        i++;
        j=0;
        count=0;
        span.innerText='';
        }
        if(i===3)
        {
            i=0;
            
        }
    },400)
    var y = document.getElementById("vid").autoplay;
</script>
</html>
