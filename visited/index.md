---
layout: page
title: Visited Countries
excerpt: "All my visited countries."
image:
---
<script src="https://www.amcharts.com/lib/3/ammap.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/maps/js/worldHigh.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/themes/dark.js" type="text/javascript"></script>
<div id="mapdiv" style="width: 1000px; height: 450px;"></div>
<script type="text/javascript">
var map = AmCharts.makeChart("mapdiv",{
type: "map",
theme: "dark",
projection: "mercator",
panEventsEnabled : true,
backgroundColor : "#535364",
backgroundAlpha : 1,
zoomControl: {
zoomControlEnabled : true
},
dataProvider : {
map : "worldHigh",
getAreasFromMap : true,
areas :
[
  {
    "id": "AT",
    "showAsSelected": true
  },
  {
    "id": "CZ",
    "showAsSelected": true
  },
  {
    "id": "FR",
    "showAsSelected": true
  },
  {
    "id": "IT",
    "showAsSelected": true
  },
  {
    "id": "PT",
    "showAsSelected": true
  },
  {
    "id": "RO",
    "showAsSelected": true
  },
  {
    "id": "ES",
    "showAsSelected": true
  },
  {
    "id": "TR",
    "showAsSelected": true
  },
  {
    "id": "GB",
    "showAsSelected": true
  },
  {
    "id": "KH",
    "showAsSelected": true
  },
  {
    "id": "IN",
    "showAsSelected": true
  },
  {
    "id": "LA",
    "showAsSelected": true
  },
  {
    "id": "MM",
    "showAsSelected": true
  },
  {
    "id": "TH",
    "showAsSelected": true
  },
  {
    "id": "VN",
    "showAsSelected": true
  },
  {
    "id": "EG",
    "showAsSelected": true
  }
]
},
areasSettings : {
autoZoom : true,
color : "#B4B4B7",
colorSolid : "#3605FC",
selectedColor : "#3605FC",
outlineColor : "#666666",
rollOverColor : "#9EC2F7",
rollOverOutlineColor : "#000000"
}
});
</script>
<br>
<br>
<h1>Europe</h1>
<img src="../images/flags/at.png"/> Austria <small>(Vienna)</small><br>
<img src="../images/flags/cz.png"/> Czech Republic <small>(Prague)</small><br>
<img src="../images/flags/fr.png"/> France <small>(Marseille, Cassis)</small><br>
<img src="../images/flags/it.png"/> Italy <small>(Milan)</small><br>
<img src="../images/flags/pt.png"/> Portugal <small>(too many...)</small><br>
<img src="../images/flags/ro.png"/> Romania <small>(Cluj Napoca)</small><br>
<img src="../images/flags/es.png"/> Spain <small>(Madrid, Santiago, Vigo)</small><br>
<img src="../images/flags/tr.png"/> Turkey <small>(Istambul, Cappadocia, Olimpos, Kaş, Fethiye, Pamukkale)</small><br>
<img src="../images/flags/gb.png"/> United Kingdom <small>(London)</small><br><br>

<h1>Africa</h1>
<img src="../images/flags/eg.png"/> Egypt <small>(Cairo, Luxor, Aswan)</small><br><br>

<h1>Asia</h1>
<img src="../images/flags/kh.png"/> Cambodia <small>(<a href="{{site.url}}/PhnomPenh" target="_blank">Phnom Penh</a>,
  <a href="{{site.url}}/KepKampot" target="_blank">Kep</a>, 
  <a href="{{site.url}}/KepKampot" target="_blank">Kampot</a>,
  <a href="{{site.url}}/Samloem" target="_blank">Koh Rong Samloem</a>,
  <a href="{{site.url}}/Samloem" target="_blank">Sihanoukville</a>,
  <a href="{{site.url}}/Battambang" target="_blank">Battambang</a>,
  <a href="{{site.url}}/SiemReap" target="_blank">Siem Reap</a>)</small><br>
<img src="../images/flags/in.png"/> India 
<small>(<a href="{{site.url}}/Delhi" target="_blank">New Delhi</a>, 
  <a href="{{site.url}}/Amritsar" target="_blank">Amritsar</a>, 
  <a href="{{site.url}}/McLeodGanj" target="_blank">McLeod Ganj</a>, 
  <a href="{{site.url}}/Rishikesh" target="_blank">Rishikesh</a>, 
  <a href="{{site.url}}/Pushkar" target="_blank">Pushkar</a>, 
  <a href="{{site.url}}/Jaipur" target="_blank">Jaipur</a>, 
  <a href="{{site.url}}/Varanasi" target="_blank">Varanasi</a>)</small><br>
<img src="../images/flags/la.png"/> Lao 
<small>(<a href="{{site.url}}/4000Islands" target="_blank">4000 Islands</a>, 
  <a href="{{site.url}}/Pakse" target="_blank">Pakse</a>, 
  <a href="{{site.url}}/Vientiane" target="_blank">Vientiane</a>, Vang Vieng, Luang Prabang</small><br>
<img src="../images/flags/mm.png"/> Myanmar 
<small>(<a href="{{site.url}}/Land-of-Smiles-1" target="_blank">Yangon</a>, 
  <a href="{{site.url}}/Land-of-Smiles-2" target="_blank">Inle Lake</a>, 
  <a href="{{site.url}}/Land-of-Smiles-3" target="_blank">Kalaw</a>, 
  <a href="{{site.url}}/Land-of-Smiles-4" target="_blank">Bagan</a>, 
  <a href="{{site.url}}/Land-of-Smiles-7" target="_blank">Mandalay</a>)</small><br>
<img src="../images/flags/th.png"/> Thailand <small>(Bangkok 2x, Koh Samet)</small><br>
<img src="../images/flags/vn.png"/> Viet Nam 
<small>(<a href="{{site.url}}/Hanoi" target="_blank">Hanói</a>, 
  <a href="{{site.url}}/CatBa" target="_blank">Cát Bà</a>, 
  <a href="{{site.url}}/TamCoc" target="_blank">Tam Coc</a>, 
  <a href="{{site.url}}/Hue" target="_blank">Hué</a>,
  <a href="{{site.url}}/HoiAn" target="_blank">Hội An</a>,
  <a href="{{site.url}}/Dalat" target="_blank">Nha Trang</a>,
  <a href="{{site.url}}/Dalat" target="_blank">Đà Lạt</a>, 
  <a href="{{site.url}}/HCMC" target="_blank">Saigon</a>)</small><br><br>