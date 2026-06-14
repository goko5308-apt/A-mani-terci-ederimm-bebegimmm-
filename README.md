<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bir Mesajım Var ❤️</title>
<style>
body{
    background: linear-gradient(135deg,#ff9a9e,#fad0c4);
    font-family: Arial,sans-serif;
    text-align:center;
    color:white;
    padding-top:100px;
}
button{
    padding:15px 30px;
    font-size:20px;
    border:none;
    border-radius:20px;
    cursor:pointer;
}
#mesaj{
    display:none;
    margin-top:30px;
    font-size:24px;
}
</style>
</head>
<body>

<h1>❤️ Sana Bir Mesajım Var ❤️</h1>

<button onclick="goster()">Tıkla</button>

<div id="mesaj">
    Sen benim için çok değerlisin. 🌹<br><br>
    Eğer seni üzdüysem özür dilerim. 💖<br>
    Gülüşünü özledim. 😊❤️
</div>

<script>
function goster(){
    document.getElementById("mesaj").style.display="block";
}
</script>

</body>
</html>
