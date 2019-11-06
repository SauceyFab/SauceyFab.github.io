# SauceyFab.github.io
<html>
<head>
<style>
body{
	background-image: url("https://as2.ftcdn.net/jpg/00/76/07/65/500_F_76076569_eEsgUUu3H6RspSs1Xi9NNvJ2ubHFOM4t.jpg");
        background-repeat:no-repeat;
       background-size:cover;
}
</style>
<script language="javascript">
function myFunction() {
input= document.getElementById("mySubmit").value
var randNumber = Math.ceil(Math.random()*10);
var integer = parseInt(input, 10);
if (Number.isInteger(integer)) {
	document.getElementById("__").innerHTML = 'The random number is '+randNumber ;
    if( input == randNumber) {
		document.getElementById("_").innerHTML = input+' = '+randNumber+" : Lucky Guess: You Got It!!";
}   else {
        document.getElementById("_").innerHTML = input +' != ' +randNumber +': Trashh! You suck at guessing.'
} 
} else {
    document.getElementById("_").innerHTML ='Wait!!Are you retarded?This is not a number!'
} 
}
</script>
</head>
<body>
<DIV style="position:absolute; TOP:35px; LEFT:510px"><font size ="6" color="skyblue4">GUESSING GAME</font></DIV>
<IMG STYLE="position:absolute; BOTTOM:35px; LEFT:380px; WIDTH:500px; HEIGHT:100px" 
	<img src="https://mathjokes4mathyfolks.files.wordpress.com/2015/01/dilbert_accurate_numbers.gif">
</IMG>
<IMG style="position:absolute; TOP:150px; LEFT:420px; WIDTH:460px; HEIGHT:200px" 
	<img src="https://www.publicdomainpictures.net/pictures/30000/velka/plain-white-background.jpg" alt=''/>
<DIV class="centered"style= "position: absolute; TOP:200px; LEFT:510px">
Choose Number 1-10:<br><input type="text" id="mySubmit" value="" maxlength="2" />
<br />
<button onclick="myFunction()">Submit</button>
<p id = "__"</p>
<p id = "_"</p></DIV>
</IMG>
</body>
</html>
