FUNCION : 
javascript :(function(){var token=document.cookie.match(/popRunToken=([^;]+)/);if(token){prompt("Copy the token:", token[1]);}else{alert("Token not found");}})()
