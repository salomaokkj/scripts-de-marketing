# 🥊 Código: “X” pessoas estão assistindo a esse vídeo agora! (X atualiza a cada 10s)

```javascript
<span id="number"></span> pessoas estão assistindo a esse vídeo agora!

<script>
function add(){number+=Math.floor((Math.random()*6)+1);document.getElementById("number").innerHTML=number;setTimeout("add()",10000);}        
function generate(){number=Math.floor(Math.random()*1143)+1578;document.getElementById("number").innerHTML=number;add();}
generate();</script>
```
