# 🕑 Código backredirect:

```javascript
<script>
var back_redirect_back_link = 'seusiteaqui';
history['pushState']({}, '', location['href']);
history['pushState']({}, '', location['href']);
window['onpopstate'] = function() {
setTimeout(function() {
	location['href'] = back_redirect_back_link
	}, 1)
}</script>
```

{% hint style="info" %}
Obs: troque o **"seusiteaqui"** para url do desconto/recuperação.
{% endhint %}

