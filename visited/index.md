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
<img src="../images/flags/kh.png"/> Cambodia <small>(Phnom Penh, Kep, Kampot, Koh Rong Samloem, Sihanoukville, Battambang, Siem Riep)</small><br>
<img src="../images/flags/in.png"/> India <small>(New Delhi, Amritsar, McLeod Ganj, Rishikesh, Pushkar, Jaipur, Varanasi)</small><br>
<img src="../images/flags/la.png"/> Lao <small>(4000 Islands, Pakse, Vientiane, Vang Vieng, Luang Prabang)</small><br>
<img src="../images/flags/mm.png"/> Myanmar <small>(Yangon, Inle Lake, Kalaw, Bagan, Mandalay)</small><br>
<img src="../images/flags/th.png"/> Thailand <small>(Bangkok 2x, Koh Samet)</small><br>
<img src="../images/flags/vn.png"/> Viet Nam <small>(Hanoi, Cat Ba, Tam Coc, Hue, Hoi An, Nha Trang, Dalat, Saigon)</small><br><br>