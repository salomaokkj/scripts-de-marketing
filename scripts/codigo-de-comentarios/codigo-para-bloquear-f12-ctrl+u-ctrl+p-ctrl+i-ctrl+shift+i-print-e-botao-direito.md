# 🚫 Código para bloquear F12, Ctrl+U, Ctrl+P, Ctrl+I, Ctrl+Shift+I, Print e Botão Direito:

```javascript
<script>
document.addEventListener("contextmenu", function (e){
    e.preventDefault();
}, false);
</script>

<script>
document.onkeypress = function (event) {
event = (event || window.event);
if (event.keyCode == 123) {return false;}
if (event.keyCode == 93) {return false;}
if (event.keyCode == 85) {return false;}
if (event.keyCode == 80) {return false;}
if (event.keyCode == 44) {return false;}
if (event.keyCode == 73) {return false;}
}
document.onmousedown = function (event) {
event = (event || window.event);
if (event.keyCode == 123) {return false;}
if (event.keyCode == 93) {return false;}
if (event.keyCode == 85) {return false;}
if (event.keyCode == 80) {return false;}
if (event.keyCode == 44) {return false;}
if (event.keyCode == 73) {return false;}
}
document.onkeydown = function (event) {
event = (event || window.event);
if (event.keyCode == 123) {return false;}
if (event.keyCode == 93) {return false;}
if (event.keyCode == 85) {return false;}
if (event.keyCode == 80) {return false;}
if (event.keyCode == 44) {return false;}
if (event.keyCode == 73) {return false;}
}
</script>
```
