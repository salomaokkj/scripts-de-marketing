# 🤩 Código Dia de Hoje” Automático - ex: "Promoção Até Hoje 26/03/2022":

```html
Promoção Imperdível Até o Dia <div id="descounttime"></div>!!!
<script language="javascript">
var getdayNames = new Array("Domingo", "Segunda-Feira", "Terça-Feira", "Quarta-Feira","Quinta-Feira", "Sexta-Feira", "Sábado");
var getdayMonth = new Array("Janeiro", "Fevereiro", "Março", "Abril", "Maio", "Junho", "Julho","Agosto", "Setembro", "Outubro", "Novembro", "Dezembro");
var getNow = new Date();
var dayOfTheWeek = getNow.getDay();
getNow.setTime(getNow.getTime() - 0 * 24 * 60 * 60 * 1000);
document.getElementById("descounttime").innerHTML = getdayNames[(getNow.getDay())] + ", " + getdayMonth[(getNow.getMonth())] + " " + getNow.getDate() + ", " + getNow.getFullYear();
</script>
```
