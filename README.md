# enroll_now
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Say Hello!</title>
    <link rel="stylesheet" href="./forms.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">
</head>
  <style>
    *{
    margin: 0;
    padding: 0;
    font-family: 'Poppins', 'Calibri';

}

body{
    display: flex;
    justify-content: center;
    background-image: linear-gradient(to bottom right, red, orange, yellow, green, blue, indigo, violet);
    
}
.mother{
    background-color: whitesmoke;
    width: 500px;
    border-radius: 15px;
    overflow: auto;
    display: flex;
    font-weight: 300;
    

}
.child{
    align-items: center;
    justify-content: center;
    padding: 50px;
    overflow: auto;
    width: 400px;
}


::placeholder, input,form{
    margin-top: 20px;
    color: #3306068c;
    font-size: large;
    
}
select{
    font-size: large;
}

form{
    font-weight:bold;
}

input, select{
    border-top: none;
    border-left: none;
    border-right: none;
    width: 400px;
    

}

button{
    margin-top: 50px;
    background-image: linear-gradient(to bottom right, red, orange, yellow, green, blue, indigo, violet);
    width: 390px;
    padding: 5px;
    height: 30px;
    font-size: large;
    border-radius: 15px;
    color: white;


}

input:focus{
    outline: none;
}

p{
    font-size: 40px;
    font-weight: 1000;
    text-align: center;
    font-family: Calibri;
}

@media(max-width:600px){
    .mother{
        width:90%;
    }
}
  </style>
<body>
   
   <div class="mother">
        
   <div class="child">
            <p>ENROLL NOW!</p>
            <form action="#" id="name">Your name</form> <br>
            <input type="text" id="name" placeholder="Enter Your name">

   <form action="#" id="email">Email</form> <br>
            <input type="email" id="email" placeholder="Enter Your email">

   <form action="#" id="needed">Needed services</form>
            <select name="#" id="needed">
                <option value="#">Choose services</option>
                <option value="htm">html</option>
                <option value="js">Javascript</option>
                <option value="css">CSS</option>
                <option value="Boot">Bootstrap</option>
                <option value="best">Best Practices</option>
            </select>

 <form action="#" id="budget">Budget</form>
            <select name="#" id="budget">
                <option value="#">Select budget</option>
                <option value="20k">#20,000</option>
                <option value="50k">#50,000</option>
                <option value="100k">#100,000</option>
            </select>
            
   <form action="#" id="messa">Message</form>
            <input type="message" id="messa" placeholder="Your message here...">

   <br>

   <button>Submit</button>



   </div>
    </div>
</body>
</html>
