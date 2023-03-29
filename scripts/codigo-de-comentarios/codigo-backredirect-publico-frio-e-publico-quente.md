# 🏳 Código backredirect público frio e público quente:

```javascript
<script>
function backfrio(){
    var back_redirect_back_link = 'www.google.com/link_back_frio_aqui';
    history['pushState']({}, '', location['href']);
    history['pushState']({}, '', location['href']);
    window['onpopstate'] = function() {
    setTimeout(function() {
        location['href'] = back_redirect_back_link
    }, 1)
    }
}
setTimeout("backfrio()", 60000); //1 minuto em ms


function backquente(){
    var back_redirect_back_link = 'www.google.com/link_back_quente_aqui';
    history['pushState']({}, '', location['href']);
    history['pushState']({}, '', location['href']);
    window['onpopstate'] = function() {
    setTimeout(function() {
        location['href'] = back_redirect_back_link
    }, 1)
    }
}
setTimeout("backquente()", 600000); //10 minutos em ms
</script>
```

{% hint style="info" %}
Obs: troque o **"www.google.com/link\_back\_frio\_aqui"** para url do desconto/recuperação.
{% endhint %}

{% hint style="info" %}
Obs: troque o **"www.google.com/link\_back\_quente\_aqui"** para url do desconto/recuperação.
{% endhint %}
