# 🌎 Código Geolocalização:

```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script><script>$.get("https://ipinfo.io/json", function (response) {
$("#ip").html("IP: " + response.ip);
$("#address").html(response.city + ", em " + response.region);
$("#details").html(JSON.stringify(response, null, 4));
}, "jsonp");</script>
<center>Você e alguns homens de <span id="address"></span> foram selecionados para participar deste programa.</center>
```
