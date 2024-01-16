# twitter

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>calculator</title>
     <style>
.addition{
    margin:150px 80px 100px 90px ;
}
body{
    background-image: url('https://media.istockphoto.com/id/1463226706/photo/orange-basketball-ball-on-hardwood-court-floor-horizontal-sport-theme-poster-greeting-cards.jpg?s=1024x1024&w=is&k=20&c=w-N9N7HRpbsrHEINo4CAPQvppFaAo3BZqGF_Iwyfc7U=');
}
.button{
    background-color: #0096ff;
    height: 35px;
    width: 180px;
    margin-top: 20px;
    border-radius: 30px;
    color: white;
}
button{
    height: 34px;
    width: 180px;
    margin-top: 2px;
    margin-bottom: 2px;
    background-color: aliceblue;
}

     </style>
</head>
<body> 
<h1 style="text-align: center; ">calculator</h1>
    <div class="addition">
        <button style="border: none;"><p id="result" class="result"></p> </button><br>  


    <label> enter a number :</label><br>
     <input type="text" id="n1"><br>
     <label>enter second number :</label><br>
     <input type="text" id="n2"><br>
     
            

       
      <div>
        <button  class="button" type="button" value="addition" onclick="add()"> ADD</button>
        <button   class="button" value="addition" onclick="subtract()"> SUBTRACT</button><br>
        <button   class="button" value="addition" onclick="multi()">  MULTIPLY</button>
        <button  class="button" value="addition" onclick="div()">DIVIDE</button>
   
    </div>
    </div>

     <script>
        function add(){
            var messageElement = document.getElementById('result');
            var n1=document.getElementById("n1").value;
            var n2=document.getElementById("n2").value;
           
            messageElement.textContent = parseInt(n1)+parseFloat(n2);


        }

        function subtract(){
            
            var messageElement = document.getElementById('result');
            var n1=document.getElementById("n1").value;
            var n2=document.getElementById("n2").value;
           
            messageElement.textContent = parseInt(n1)-parseFloat(n2);

        }

        function multi(){
            
            var messageElement = document.getElementById('result');
            var n1=document.getElementById("n1").value;
            var n2=document.getElementById("n2").value;
           
            messageElement.textContent = n1*n2;
        }

        function div(){
            
            var messageElement = document.getElementById('result');
            var n1=document.getElementById("n1").value;
            var n2=document.getElementById("n2").value;
           
            messageElement.textContent = n1/n2;
        }
     </script>

</body>
</html>
