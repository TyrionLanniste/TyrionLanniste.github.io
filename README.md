# wutv1-te16-7
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link href="main.css" rel="stylesheet" type="text/css">
  
    <title>Typografi för webben</title>
</head>
<body>
       
    <ul>
    <li><a href="index.html"> Hemsida </a>
        <li><a href="#Nyheter"> Nyheter </a>
          <li><a href="#Om">   Om </a>
            <li><a href="#Kontakta Oss"> Kontakta Oss </a>
        <li><a href= "font.html">Typsnitt</a></li>
    </ul>

    <h1>Typografi För Webben</h1>

    
    <script>
            document.write(Date());
        </script>
  
<!--Kommentar-->
    

        <script> src  = "script.js" </script>
        <button type ="button" onclick="MinFunktion()"> Ändra bakgrunden</button>
        <script>
    function MinFunktion(){
        document.body.style.backgroundColor = "#cdcdb1";
    }
    </script>
   
    <img class = "infinitywar" src  = "nti-gymnasiet-logotype-1.png" alt= "NTI"/>
    <img class = "thanos" src = "swedish.jpg" alt="SAB"/>
   
    <button onclick="myfunction()">Tryck Här</button>
<p id = "demo"<></p>
<script> 
function myfunction() {
    var txt;
    var person = prompt ("Skriv in ditt namn här:", "Fredrik Habib");
    if(person == null || person == ""){
    txt = "Användaren avbröt detta de misslyckades!";
} 
else{
    txt ="Hej"+ person + "! Hur mår du idag?";
}
document.getElementById("demo").innerHTML = txt;
}


</script>
</body>
</html>
