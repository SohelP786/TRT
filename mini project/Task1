<!DOCTYPE html>
<html>
<head>
 <title>SOHEL'S CALCULATOR</title>
 <style type="text/css">

.div{
    border: 5px solid black;
    width: 414px;
    margin-left: 500px;
    margin-top:80px;
    border-radius:25px;
    padding:20px;
}
.display-box {
 background-color: black;
 border: solid gray; 0.5px;
 color: black;
 font-size: 30px;
 width: 400px;
 margin-top:10px;
 height: 70px;
border-radius:6px;
background-color: lightyellow;
text-align: center;
}
.button {
    border-radius:30px;
 color:darkblack;
 border: solid red; 0.5px;
 width:100%;
background-color:yellow;
 height: 80px;
 margin-top: 20px;
 text-shadow: 2px;
 font-size: 20px;
}

.button:hover{
    cursor: pointer;
    background-color:white;
}

 </style>
</head>
<body bgcolor="gray">
    <div class="div">
<table>
 <tr>
 <td colspan = "4"> <input class = "display-box" type = "text" id = "result" disabled ></td>
 
 </tr>
  <tr>
 <td colspan="2"> <input class = "button" type = "button" value = " CLEAR" onclick = "clearScreen()" style="color:black; font-size: 20px; font-weight: bold;"></td>
 <td colspan="2"> <input class = "button" type = "button" value = "=" onclick = "calculate()" style = "background-color:green;"> </td>
 </tr>
 <tr>
 <td> <input class = "button" type = "button" value = "7" onclick = "display('7')"> </td>
 <td> <input class = "button" type = "button" value = "8" onclick = "display('8')"> </td>
 <td> <input class = "button" type = "button" value = "9" onclick = "display('9')"> </td>
 <td> <input class = "button" type = "button" value = "/" onclick = "display('/')"> </td>
 </tr>
 <tr>
 <td> <input class = "button" type = "button" value = "4" onclick = "display('4')"> </td>
 <td> <input class = "button" type = "button" value = "5" onclick = "display('5')"> </td>
 <td> <input class = "button" type = "button" value = "6" onclick = "display('6')"> </td>
 <td> <input class = "button" type = "button" value = "-" onclick = "display('-')"> </td>
 </tr>
 <tr>
 <td> <input class = "button" type = "button" value = "1" onclick = "display('1')"> </td>
 <td> <input class = "button" type = "button" value = "2" onclick = "display('2')"> </td>
 <td> <input class = "button" type = "button" value = "3" onclick = "display('3')"> </td>
 <td> <input class = "button" type = "button" value = "+" onclick = "display('+')"> </td>
 </tr>
 <tr>
 <td> <input class = "button" type = "button" value = "." onclick = "display('.')"> </td>
 <td> <input class = "button" type = "button" value = "0" onclick = "display('0')"> </td>
 <td> <input class = "button" type = "button" value = "%" onclick = "display('%')"> </td>
 <td> <input class = "button" type = "button" value = "*" onclick = "display('*')"> </td>
 </tr>

 </table>
</div>

<script type="text/javascript">

    function clearScreen() {
 document.getElementById("result").value = "";
}

function display(value) {
 document.getElementById("result").value += value;
}
function calculate() {
 var a = document.getElementById("result").value;
 var b = eval(a);
 document.getElementById("result").value = b;
}
</script>
</body>
</html>
