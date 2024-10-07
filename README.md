HTML 

<!DOCTYPE HTML>
<html lang="en">
<meta charset="utf-8">  
</html>
<link rel="stylesheet"href="styles.css">
<h1> 
  Register
</h1>
<h2> 
UserName
<input type="text " >
</h2>
<h3>
Password
<input type="text " >
<form action= "pups.html" target="_blank">
    <button>Register</button>
</form>
</h3>

JS

function showTime() {
	document.getElementById('currentTime').innerHTML = new Date().toUTCString();
}
showTime();
setInterval(function () {
	showTime();
}, 1000);
