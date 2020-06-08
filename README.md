# login-clone
<!DOCTYPE html>
<html> 
    <head>
     <meta charset="UTF-8">
        <title>Account</title>
    </head> 
    <body bg color="#E6E6FA">
        <h1 align="center">User login</h1>
        <input placeholder=" Enter Username" type="text"><br><br>
        <input placeholder="Enter Password" type="password"><br><br>
        <div class="login">
            <div class="first_page page">
              <div onclick="hidePage()" class="next"><button>login</button></div>
               </div> 
          <div class="second_page page">
             <div class="greet">welcome to priayatech </div>  
            
            <h5>Not have an account?<button onclick="b()" id="tap" id="#000080"><u>
            Register</u>
           
                 <div onclick="hidePage()" class="next"></div> </button>
            </h5>
               <div class="Application form">
            <div class="first_page page">
            <div class="form"> 
            <input placeholder="First name"type="text"><br><br> 
            <input placeholder="last  name"type="text"></div><br><br>
                     
         <div>   <input placeholder="Create username"type="text">
         </div><br>
             
         <div>   <input placeholder="Create password"type="password"></div><br>
        <br>
            
    <button onclick="c()"id="tap" id="#ADD8E6" align="right" >Submit</button>
    
     <style>body {
    background-color:#E6E6FA;
    font-family:Courier;
}
h1{
    font-size:40px;
    letter-spacing:7px;
    animation:h 2s ease in 2s infinite alternative;
}

@keyframes h{
    from{letter-spacing:7px;}
    to{
    letter-spacing:3px;
    color:#7F7F9A;
    }
}
input{
    font-size:20px;
    font-family:monospace;
    letter-spacing:2px;
    background-color:#3F3A4B;
    padding:3px;
    border:0px;
    border-radius:10px;
    box-shadow:inset -1px -1px 20px #0C0718;
    transition:width 0.3s ease-in;   
    width:40%;
}


button{
    font-size:20px;
    padding:25x;
    font-family:monospace;    
    border:0px;
    border-radius:10px;
    
color:#F0FFFF;
}

#2F4F4F{
background-color:#2F4F4F;
    box-shadow:inset -1px -1px 10px #040; 
    }
       
#000080{
 background-color:#000080;
    box-shadow:inset -1px -1px 10px #114; 
    }   

#a{
z-index:2;
    color:#FF69B4;
    font-family:sans-serif;
    font-variant:small-caps;
}
#b{
z-index:1;
    color:#FF1493;
    font-family:sans-serif;
    font-variant:small-caps;
}
#c{
    z-index:3;
    color:#ADD8E6;
    font-family:serif;
    font-variant:caps;
    align:right;
}

style{
    page{
    resolution:landscape;
    background-color:#E6E6FA;
    
}
input:hover{
    width:70%;
}
.page{
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    background:#FF69B4;
    height:70%;
    width:70%;
    padding:5px;  
    border-radius:9px;  
    box-shadow:  6px 6px 12px rgba(0,0,0,0.1), 
        -6px -6px 12px rgba(255,255,255,0.8);
    transition:0.5s;
}
.new_page{
    z-index:3;
    visibility:hidden;
}
.first_page{
  z-index:2;
     height:auto;
    /visibility:hidden;
}
.second_page{
    visibility:hidden;
    z-index:1;
}
.greet,.greeting{
    padding:10px 3%;
    width:94%;
    text-align:center;
    font-weight:bold;
    font-size:25px;
    letter-spacing:7px;
    text-shadow:  6px 6px 12px rgba(0,0,0,0.2), 
        -6px -6px 12px rgba(255,255,255,0.8);
    margin-top:20%;
}
.greet:first-letter{
    font-size:30px;
    box-shadow:  6px 6px 12px rgba(0,0,0,0.1), 
        -6px -6px 12px rgba(255,255,255,0.8);
    padding:10px 13px;
    margin:5px;
    border-radius:50%;
    
}
.greet:nth-child(1){
    text-align:left;
}
.greet:nth-child(3){
    text-align:right;
}
.next{
    width:60px;
    height:60px;
    margin-left:15px;
    box-shadow:  6px 6px 12px rgba(0,0,0,0.1), 
        -6px -6px 12px rgba(255,255,255,0.8);
    border-radius:50%;
    display:flex;
    justify-content:center;
    align-items:center;
    font-weight:bold;
    font-size:20px;
}

.greeting{
    margin-top:10%;
}
.greeting{
    border-radius:5px;
    font-size:30px;
    box-shadow:  6px 6px 12px rgba(0,0,0,0.1), 
        -6px -6px 12px rgba(255,255,255,0.8);
    margin:1px;
    margin-top:10%;
    width:33%;
    margin-left:30%;
    
}


.pic{
    width:96%;
    height:15%;
     box-shadow:  6px 6px 12px rgba(0,0,0,0.1), 
        -6px -6px 12px rgba(255,255,255,0.8);
    border-radius:0%;
    display:inline-block;
    margin-top:5px;
    margin-left:2%;
    display:flex;
    justify-content:center;
    align-items:center;
    font-weight:strong;
}
.pic:hover,.greeting:hover,.next:hover:;
</style>   
   <script>const hidePage = ()=>{
let fp = document.getElementsByClassName("page");
fp[0].style.left = "-50%"
fp[1].style.visibility = "visible";
setTimeout(()=>{
fp[0].style.visibility = "visible";
},1000)

};</script>    
 
     
     
    </div>
    </body>
</html>
