<style> html { height: 100%; }
    body {
        background-image: url("https://img.funhualien.com.tw/uploads/20180907004138_11.jpg");
        background-repeat: no-repeat;
        background-attachment: fixed;
        background-position: center;
        background-size: cover;
    }
    
    p {
        font-size: 18px;
        font-family: Microsoft JhengHei;
    }
    
    h2 {
        font-family: "微軟正黑體";
        font-weight: bold;
    }
    
    td {
        font-family: "微軟正黑體";
        font-size: 18px;
    }
    /* button*/
    .button {
        background-color: #a0fdff;
        border: 2px solid black;
        color:  #0645ad;
        padding: 8px 24px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        display: block;
    }
    
    .button:hover {
        background-color: #A1D0FF;
    }
    
    #flip {
        background-color: #a0fdff;
        border: 2px solid black;
        color: black;
        padding: 8px 42px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        display: block;
    }
    
    .button-bar {
        position: fixed;
        top: 5%;
        right: 5%;
    }
    
    
    
    
    /*light box*/
    
     * {
        box-sizing: border-box
    }
    
    body {
        font-family: Verdana, sans-serif;
        margin: 0
    }
    
    .mySlides {
        display: none
    }
    
    img {
        vertical-align: middle;
    }
    /* Slideshow container */
    
    .slideshow-container {
        max-width: 1000px;
        position: relative;
        margin: auto;
    }
    /* Next & previous buttons */
    
    .prev,
    .next {
        cursor: pointer;
        position: absolute;
        top: 50%;
        width: auto;
        padding: 16px;
        margin-top: -22px;
        color: white;
        font-weight: bold;
        font-size: 18px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
        user-select: none;
    }
    /* Position the "next button" to the right */
    
    .next {
        right: 0;
        border-radius: 3px 0 0 3px;
    }
    /* On hover, add a black background color with a little bit see-through */
    
    .prev:hover,
    .next:hover {
        background-color: rgba(0, 0, 0, 0.8);
    }
    /* Caption text */
    
    .text {
        color: #f2f2f2;
        font-size: 15px;
        padding: 8px 12px;
        position: absolute;
        bottom: 8px;
        width: 100%;
        text-align: center;
    }
    /* Number text (1/3 etc) */
    
    .numbertext {
        color: #f2f2f2;
        font-size: 12px;
        padding: 8px 12px;
        position: absolute;
        top: 0;
    }
    /* The dots/bullets/indicators */
    
    .dot {
        cursor: pointer;
        height: 15px;
        width: 15px;
        margin: 0 2px;
        background-color: #bbb;
        border-radius: 50%;
        display: inline-block;
        transition: background-color 0.6s ease;
    }
    
    .active,
    .dot:hover {
        background-color: #717171;
    }
    /* Fading animation */
    
    .fade {
        -webkit-animation-name: fade;
        -webkit-animation-duration: 1.5s;
        animation-name: fade;
        animation-duration: 1.5s;
    }
    
    @-webkit-keyframes fade {
        from {
            opacity: .4
        }
        to {
            opacity: 1
        }
    }
    
    @keyframes fade {
        from {
            opacity: .4
        }
        to {
            opacity: 1
        }
    }
    /* On smaller screens, decrease text size */
    @media only screen and (max-width: 300px) {
        .prev,
        .next,
        .text {
            font-size: 11px
        }
    }
    
    
    
    
    /*tabs*/
     body {
        font-family: Arial;
    }
    /* Style the tab */
    
    .tab {
        overflow: hidden;
        border: 1px solid #ccc;
        background-color: #f1f1f1;
    }
    /* Style the buttons inside the tab */
    
    .tab button {
        background-color: inherit;
        float: left;
        border: none;
        outline: none;
        cursor: pointer;
        padding: 10px 12px;
        transition: 0.3s;
        font-size: 17px;
    }
    /* Change background color of buttons on hover */
    
    .tab button:hover {
        background-color: #ddd;
    }
    /* Create an active/current tablink class */
    
    .tab button.active {
        background-color: #ccc;
    }
    /* Style the tab content */
    
    .tabcontent {
        display: none;
        padding: 6px 12px;
        border: 1px solid #ccc;
        border-top: none;
    }
    
    
    /*video*/
    .video-container {
    position: relative;
    padding-bottom: 56.25%;
    padding-top: 30px;
    height: 0;
    overflow: hidden;
    }

    .video-container iframe,
    .video-container object,
    .video-container embed {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    }

   
</style>

<head>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
    <script>
        $(document).ready(function() {
            $('#top').click(function() {
                $('html, body').animate({
                    scrollTop: 0
                }, 1000);
            });
            $('#bottom').click(function() {
                $('html, body').animate({
                    scrollTop: $(document).height() - $(window).height()
                }, 1000);
            });
            $('#a').click(function() {
                $('html, body').animate({
                    scrollTop: $("#A").offset().top
                }, 1000);
            });
            $('#b').click(function() {
                $('html, body').animate({
                    scrollTop: $("#B").offset().top
                }, 1000);
            });
            $('#c').click(function() {
                $('html, body').animate({
                    scrollTop: $("#C").offset().top
                }, 1000);
            });
            $('#d').click(function() {
                $('html, body').animate({
                    scrollTop: $("#D").offset().top
                }, 1000);
            });
            $('#e').click(function() {
                $('html, body').animate({
                    scrollTop: $("#E").offset().top
                }, 1000);
            });
            $('#f').click(function() {
                $('html, body').animate({
                    scrollTop: $("#F").offset().top
                }, 1000);
            });
            $("#flip").click(function() {
                $(".button").slideToggle("slow");
            });
        });
    </script>
</head>
太魯閣國家公園
<h2 class="header-level-2" id="A">基本資訊:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    <ol>
        <li>
            <p>太魯閣國家公園是台灣第四座成立的國家公園，建立時間	1986年11月12日，占地920平方公里，前身為日治時期成立之次高太魯閣國立公園（1937～1945）。第二次世界大戰後為國家級風景區，1986年11月12日公告計畫，1986年11月28日成立管理處。位於台灣東部，地跨花蓮縣、臺中市、南投縣三個行政區。園內有台灣第一條東西橫貫公路通過，稱為中橫公路系統。太魯閣國家公園的特色為峽谷和斷崖。
 </p>
        </li>
        
    </ol>
</div>

<h2 class="header-level-2" id="B">國家公園標示意涵:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    <img align="left" style="width: 100px; height: 100px;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f6/Taroko_National_Park_Headquarters_Logo.svg/2000px-Taroko_National_Park_Headquarters_Logo.svg.png" data-type="image">
    <center>
        <p>太魯閣國家公園管理處處徽呈現高山、森林、峽谷一線天，三棵樹代表「森林」、左右V形色塊代表「峽谷」，峽谷中間有雪覆蓋的山代表「高山」。太魯閣國家公園以雄偉壯麗、幾近垂直的大理石峽谷景觀聞名。沿途立霧溪的峽谷風景線而行，觸目所及皆是壁立千仞的峭壁、斷崖、峽谷、連綿曲折的山洞隧道、大里岩層及溪流等風光。
        </p>
    </center>
</div>

<h2 class="header-level-2" id="C">特色介紹:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">

<p></p>
    <body>

<div class="tab">
    <button class="tablinks" onclick="openCity(event, '氣候')" id="defaultOpen">氣候</button>
    <button class="tablinks" onclick="openCity(event, '地形景觀')">地形景觀</button>
    <button class="tablinks" onclick="openCity(event, '生態系')">生態系</button>
    <button class="tablinks" onclick="openCity(event, '景點介紹')">景點介紹</button>
    
   
    <button class="tablinks" onclick="openCity(event, '相關影音')">相關影音</button>
</div>

<div id="氣候" class="tabcontent">
    <h2>氣候</h2>
    <p>園區東部由海平面到500公尺以下地區，屬於亞熱帶夏季濕潤炎熱氣候區；南、北、西側位於海拔3000公尺以上之高山地區，屬於高山寒帶氣候區；其餘在海拔1000公尺至3000公尺山區，則為山地亞熱帶濕潤炎熱氣候區。溯立霧溪而上，年平均氣溫由海拔100公尺處的23℃逐步遞減，至海拔3000公尺的合歡山一帶，年均溫為7℃。到南湖大山及奇萊山一帶3500公尺以上之高山地區，年均溫則降為4℃，其中冬季12至2月間月均溫都在0℃以下，最低溫更會低至-10℃以下。國家公園範圍內年雨量幾乎都在2000mm以上，無明顯旱季，夏季易受颱風影響，2500公尺以上山區，冬季已有降雪。</p>
   
</div>

<div id="地形景觀" class="tabcontent">
    
    <h2>地形</h2>
    <p> 國家公園東臨太平洋，中央山脈北段通過園區，園區最高點為海拔3,742公尺的南湖大山。海拔三千公尺以上之高山寒帶地區面積約占國家公園範圍的7.2%，列名台灣百岳的山峰共27座。一千公尺至三千公尺之溫帶山地地區約占全區78.4%，坡度55%以上地區約占園區面積44.7%。水系大致以中央山脈為分水嶺，東側主要屬於立霧溪集水區，占國家公園面積的65.7%，少部分屬於木瓜溪或三棧溪流域；西側則分屬大甲溪或濁水溪上游，兩集水區占國家公園，面積的20%全區南、北地勢均高，中央地帶因位於歐亞大陸板塊和菲律賓板塊的碰撞交界以及太平洋西岸亞熱帶颱風豪雨區，產生複雜的地質現象。持續進行的極速造山運動，以及立霧溪的極速下切作用，形成奇特之高山、峽谷地形，太魯閣狹窄呈V字型的大理岩峽谷，深度超過1000公尺，大理岩岩層厚度達千餘公尺以上，分布範圍廣達十餘公里。</p>

</div>

<div id="生態系" class="tabcontent">
    <h2> </h2>
    <p>1.水域生態系：大吻鰕虎、日本禿頭鯊、棕塘鱧、台灣絨鰲蟹、泥鰍、台灣鏟頜魚、河烏、鉛色水鶇、台灣紫嘯鶇、貓鼬。<br>
2.常綠闊葉林生態系：九芎、山棕、台灣蘆竹、青苧麻、綠椿象、紅紋鳳蝶、長臂龜、捲葉象鼻蟲、野鴝、白尾鴝、藍尾鴝、藍磯鶇、赤腹松鼠、大赤鼯鼠、條紋松鼠、山豬、山羌、長鬃山羊。<br>
3.針闊葉樹混生林生態系：台灣雲杉、台灣鐵杉、紅檜、扁柏、台灣黃杉、綠啄木、白耳畫眉、青背山雀、冠羽畫眉、棕面鶯、紅頭山雀、紋翼畫眉、黃腹琉璃鳥、巨嘴鴉、橿鳥、藪鳥、森鼠、高山白腹鼠、赤腹松鼠、條紋松鼠、大赤鼯鼠、白面鼯鼠、台灣長鬃山羊、山羌、水鹿、台灣黑熊。<br>
4.針葉林生態系：玉山圓柏、台灣雲杉、台灣鐵杉、台灣冷杉、白面鼯鼠、條紋松鼠、高山白腹鼠、森鼠、火冠戴菊鳥、酒紅朱雀、煤山雀、金翼白眉、星鴉、鷦鷯、栗背林鴝、台灣黑熊、台灣長鬃山羊、台灣山椒魚。<br>
5.箭竹草原生態系：玉山箭竹、龍膽、台灣藜籚、南湖杜鵑、森氏杜鵑、岩鷚、鷦鷯、酒紅朱雀、高山白腹鼠、台灣森鼠、雪山草蜥、華南鼬鼠。<br>
6.寒原生態系：南湖杜鵑、玉山圓柏、玉山箭竹、高山山蘿蔔、南湖柳葉菜、酒紅朱雀、金翼白眉、高山白腹鼠、台灣長鬃山羊、華南鼬鼠。<br></p>
  
</div>

 <div id="景點介紹" class="tabcontent">
    <h2>崇德步道</h2>
    <p>
想要觀看離太魯閣最近的清水斷崖？崇德步道是最佳觀賞點！從太魯閣出發，沿著蘇花公路往北，經過崇德村、穿過蘇花公路北上第一個隧道—崇德隧道後，即抵達崇德停車場。這裡緊鄰太平洋，向北眺望是清水斷崖；朝南遠望是由立霧溪沖積出來的崇德沖積扇。來到崇德，可以聽濤、觀海、賞景，享受海風的吹彿<br></p>
      <h2>長春祠</h2>
    <p>
眼前這座詩意盎然伴隨著飛瀑湧泉的雅緻古剎，是為了紀念闢建中橫公路而不幸殉職的築路人所建。一旁莊嚴肅靜的彌陀巖，供旅人遙想當年的開路艱辛、篳路藍縷。定睛一瞧，絕壁上尚刻有『長春聽濤』不難想像大雨過後的氣勢磅薄。<br></p>
      <h2>布洛灣</h2>
    <p>
太魯閣族語『回音』之意，這裡是遺世獨立的台地，四周完全被青翠的山嶺包圍，時間在這裡緩了下來，天空燕群啁啾聲與蟬鳴是悅耳的背景音樂，櫻花、百合、李樹，讓人彷彿置身在桃花源裡。現今設有布洛灣管理站，提供解說諮詢服務，並可觀賞以太魯閣族傳說文化的影片及參觀太魯閣族文化故事館。<br></p>
        <h2>碧綠神木</h2>
    <p>
碧綠神木是中橫公路沿線唯一的參天古木，地處霧林帶，四周森林濃密，植物相當豐富，春天可見本土杜鵑科西施花盛開，秋冬時節，掌葉槭、紅榨槭等落葉樹種是觀賞季節更迭最佳的景點。<br></p>
  <h2>燕子口</h2>
    <p>險峻陡峭的太魯閣峽谷，是旅客造訪太魯閣國家公園的必到之處。600萬年前的『蓬萊造山運動』加上立霧溪水終年不斷的侵蝕切割，造就這一處另人嘆為觀止的峽谷景觀地形。沿途可欣賞壺穴、湧泉等天然景觀，不時還有洋燕彿過岩盤。步道全程大約2公里，平坦舒適，是一條人車共用兼具地質與生態特色的無障礙景觀型步道。<br></p>
</div>





<div id="相關影音" class="tabcontent">
<div class="video-container">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/8bhp5Cg5YxM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    </div>





<script>
    function openCity(evt, cityName) {
        var i, tabcontent, tablinks;
        tabcontent = document.getElementsByClassName("tabcontent");
        for (i = 0; i < tabcontent.length; i++) {
            tabcontent[i].style.display = "none";
        }
        tablinks = document.getElementsByClassName("tablinks");
        for (i = 0; i < tablinks.length; i++) {
            tablinks[i].className = tablinks[i].className.replace(" active", "");
        }
        document.getElementById(cityName).style.display = "block";
        evt.currentTarget.className += " active";
    }

    // Get the element with id="defaultOpen" and click on it
    document.getElementById("defaultOpen").click();
</script>
    <p></p>
        <div class="slideshow-container">

    <div class="mySlides fade">
        <div class="numbertext">1 / 5</div>
        <img style="width:100%;height:400px" src="https://www.taroko.gov.tw/Utility/DisplayImage?id=17804&prefix=original_">
        <div class="text"> 崇德步道</div>
    </div>

    <div class="mySlides fade">
        <div class="numbertext">2 / 5</div>
        <img style="width:100%;height:400px" src="https://www.taroko.gov.tw/Utility/DisplayImage?id=10750&prefix=original_" >
        <div class="text">長春祠</div>
    </div>

    <div class="mySlides fade">
        <div class="numbertext">3 / 5</div>
        <img style="width:100%;height:400px" src="https://www.taroko.gov.tw/Utility/DisplayImage?id=10933&prefix=original_">
        <div class="text">布洛灣</div>
    </div>
    
    <div class="mySlides fade">
        <div class="numbertext">4 / 5</div>
        <img style="width:100%;height:400px" src="https://www.taroko.gov.tw/Utility/DisplayImage?id=585&prefix=original_">
        <div class="text">碧綠神木</div>
    </div>
    
    <div class="mySlides fade">
        <div class="numbertext">5 / 5</div>
        <img style="width:100%;height:400px" src="https://www.taroko.gov.tw/Utility/DisplayImage?id=10785&prefix=original_">
        <div class="text">燕子口</div>
    </div>
    
    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
    <span class="dot" onclick="currentSlide(3)"></span>
    <span class="dot" onclick="currentSlide(4)"></span>
    <span class="dot" onclick="currentSlide(5)"></span>
</div>

<script>
    var slideIndex = 1;
    showSlides(slideIndex);

    function plusSlides(n) {
        showSlides(slideIndex += n);
    }

    function currentSlide(n) {
        showSlides(slideIndex = n);
    }

    function showSlides(n) {
        var i;
        var slides = document.getElementsByClassName("mySlides");
        var dots = document.getElementsByClassName("dot");
        if (n > slides.length) {
            slideIndex = 1
        }
        if (n < 1) {
            slideIndex = slides.length
        }
        for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";
        }
        for (i = 0; i < dots.length; i++) {
            dots[i].className = dots[i].className.replace(" active", "");
        }
        slides[slideIndex - 1].style.display = "block";
        dots[slideIndex - 1].className += " active";
    }
</script>
    
    
    
    <p></p>



<h2 class="header-level-2" id="D">交通資訊:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
<div class="tab">
    <button class="tablinks" onclick="openCity(event, '開車上路')">開車上路</button>
    <button class="tablinks" onclick="openCity(event, '鐵路交通')">鐵路交通</button>
    <button class="tablinks" onclick="openCity(event, '航空資訊')">航空資訊</button>
    <button class="tablinks" onclick="openCity(event, '花蓮客運')">花蓮客運</button>
    
    

</div>


<div id="開車上路" class="tabcontent">
    <h2 style="color:#FF8800;font-weight:bold;">開車上路:</h2>
   <img style="width:100%;height:400px" src="https://www.taroko.gov.tw/content/images/static/tourism/traffic-map.gif">
<p>
     從台灣北部出發：<br>
路線1：<br>
沿台9線從新店出發，通過宜蘭和蘇澳可到太魯閣國家公園遊客中心。<br>
路線2：<br>
沿台2線從瑞芳出發，經宜蘭，然後接台9線（蘇花公路）到太魯閣國家公園。<br>
路線3：<br>
沿國道5號從南港或木柵到蘇澳，然後接台9線（蘇花公路）到達太魯閣國家公園遊客中心。（最快的路線）<br>
從台灣南部出發：<br>
路線1：<br>
沿台9線從東到太魯閣國家公園。（較快）<br>
路線2：<br>
沿台11線從台東到花蓮，然後接台9線（蘇花公路）可至太魯閣國家公園遊客中心。（沿海岸線風景秀麗）<br>
從台灣西部出發：<br>
路線1：<br>
沿台63線（中投公路）從台中出發，經台63甲到草屯，轉台14線 到埔里，接台14甲至大禹嶺，最後沿台8線（中橫公路） 到太魯閣國家公園遊客中心。<br>
路線2：<br>
沿國道3號從台中出發，自草屯接台14線到埔里，經台14甲至大禹嶺，最後沿台8線（中橫公路） 到太魯閣國家公園遊客中心。 約需5.5 〜 6.5個小時。（最快）<br>
    </p>
</div>

<div id="鐵路交通" class="tabcontent">
    <h2 style="color:#FF8800;font-weight:bold;">鐵路交通:</h2>
    <p>
        前往太魯閣地區可於花蓮站或新城站下車，花蓮站火車班次較多，新城站則離太魯閣較近(約5公里路程)；搭乘火車是前往花蓮最便利的大眾交通工具，但因鐵路東部幹線銷售熱絡，強烈建議旅客提前2週預訂車票。<br>

鐵路票價：<br>
台北到花蓮<br>
自強號：價格約是440/人單程，約2〜3小時車程。<br>
莒光號：價格約是340/人單程，約3.5〜4.5小時車程。<br>
花蓮站火車班次較多，車站前即可搭乘客運、計程車或是租賃汽機車前往太魯閣，花連市區住宿與餐飲選擇較多，生活機能便利。<br>
台北到新城<br>
自強號：價格約是403/人單程。<br>
莒光號：價格約是311/人單程。<br>
＊以上票價與時間僅供參考，實際售價請洽詢鐵路管理局。<br>
聯絡電話：<br>
花蓮火車站：886-3-8355941<br>
新城火車站：886-3-8611237<br>
相關網站：<br>
鐵路管理局網：<li><a href="http://www.railway.gov.tw/">http://www.railway.gov.tw/</a></li><br>
時刻表及票價：<li><a href="http://twtraffic.tra.gov.tw/twrail/">http://twtraffic.tra.gov.tw/twrail/</a></li><br>
 網路購票：<li><a href="http://railway.hinet.net/">http://railway.hinet.net/</a></li><br>
 語音客服：<li><a href="http://cscenter.railway.gov.tw/webcall.html">http://cscenter.railway.gov.tw/webcall.html</a></li><br>
如何到太魯閣：<br>
搭乘火車到太魯閣國家公園旅遊的遊客可在『新城火車站』或『花蓮火車站』下車。<br>
新城火車站：車站至太魯閣國家公園管理處遊客中心約5公里車程。可於站前轉搭乘花蓮客運。<br>
花蓮火車站：車站至太魯閣國家公園管理處遊客中心約26公里車程。可於站前租車或搭乘花蓮客運。租車駕乘時間大約30〜40分鐘；搭乘花蓮客運公車車程時間約1小時。<br>
    </p>
</div>

<div id="航空資訊" class="tabcontent">
    <h2 style="color:#FF8800;font-weight:bold;">航空資訊:</h2>
<p>從台北出發：(航班由松山機場出發)<br>
松山機場： 網站： <a href="http://www.tsa.gov.tw/">http://www.tsa.gov.tw/</a><br>
立榮航空： 網站：<a href=" https://www.uniair.com.tw/"> https://www.uniair.com.tw/</a><br>
客服電話：02–25086999<br>
＊立榮航空往返台北-花蓮，票價時有變化，請參見上述網站的最新更新價格。<br>
從台中出發：(航班由台中機場出發)<br>
台中機場： 網站： <a href="http://www.tca.gov.tw/">http://www.tca.gov.tw/</a><br>
華信航空： 網站：<a href=" http://www.mandarin-airlines.com/"> http://www.mandarin-airlines.com/</a><br>
客服電話：02–4128008<br>
＊華信航空往返台中-花蓮，票價時有變化，請參見上述網站的最新更新價格。<br>
從高雄出發：(航班由高雄國際機場出發)<br>
高雄國際機場： 網站： <a href=" http://www.kia.gov.tw/"> http://www.kia.gov.tw/</a><br>
華信航空： 網站： <a href="http://www.mandarin-airlines.com/index.html">http://www.mandarin-airlines.com/index.html</a><br>
客服電話：07-8057900<br>
電話訂票：07-8026868<br>
＊機票票價時有變化，請參見上述網站的最新更新價格。<br>
如何到太魯閣：<br>
    出機場即可搭乘花蓮客運或計程車到太魯閣國家公園遊客中心，約需25分鐘車程。或是您也可以租車，機場內就有汽車租賃的服務櫃檯。<br></p>
    
</div>
<div id="花蓮客運" class="tabcontent">
    <h2 style="color:#FF8800;font-weight:bold;">花蓮客運:</h2>
   
<p>
        搭乘花蓮客運公車時間約1小時，往『太魯閣』及『崇德』皆可搭乘到太管處，惟進入到峽谷段，請搭乘往『天祥』、『洛韶』或『梨山』公車皆可，進入峽谷段每日公車班次有限，行前請與花蓮客運公司確認公車時刻表（03-8338146），以方便行程安排。<br>
網站及時刻表： <a href="http://www.hualienbus.com.tw/bus/ticket_info.php">http://www.hualienbus.com.tw/bus/ticket_info.php</a><br>
PS：因時刻表仍會更新或變動（因地震、颱風、公路施工管制緣故），建議您直接洽詢花蓮客運（03-8338146）確認公車班次時間。<br>

台灣好行-太魯閣線:1133<br>

網站及時刻表：<a href="http://www.hualienbus.com.tw/bus/hualien_bus.php">http://www.hualienbus.com.tw/bus/hualien_bus.php</a><br>

太魯閣客運綠能公車302線<br>
網站及時刻表：<a href="http://www.ropobus.com/route?area=6">http://www.ropobus.com/route?area=6</a><br>
<li><a href="https://www.taroko.gov.tw/content/file/302%E5%85%AC%E8%BB%8A%E6%99%82%E5%88%BB%E8%A1%A8.xls">302公車時刻表(.xls)</a></li><br>
<li><a href="https://www.taroko.gov.tw/content/file/302%E5%85%AC%E8%BB%8A%E6%99%82%E5%88%BB%E8%A1%A8.ods">302公車時刻表(.ods)</a></li><br>

    </p>
</div>




<script>
    function openCity(evt, cityName) {
        var i, tabcontent, tablinks;
        tabcontent = document.getElementsByClassName("tabcontent");
        for (i = 0; i < tabcontent.length; i++) {
            tabcontent[i].style.display = "none";
        }
        tablinks = document.getElementsByClassName("tablinks");
        for (i = 0; i < tablinks.length; i++) {
            tablinks[i].className = tablinks[i].className.replace(" active", "");
        }
        document.getElementById(cityName).style.display = "block";
        evt.currentTarget.className += " active";
    }

    // Get the element with id="defaultOpen1" and click on it
    document.getElementById("defaultOpen1").click();
</script>
</div>

<h2 class="header-level-2" id="E">住宿資訊:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    <p>
        <table border="1" cellpadding="5" cellspacing="0" width="90%">
            <thead>
                <tr>
                    <th width="45%">民宿/飯店 </th>
                    <th width="48%">地址 </th>
                    <th width="24%">聯絡電話 </th>
                    <th width="24%">網址 </th>
                </tr>
            </thead>
            <tbody>

                <tr>
                    <td>立霧客棧</td>
                    <td> 花蓮縣秀林鄉富世242之2號</td>
                    <td>03-86107695</td>
                    <td> <a href="http://www.mandarin-airlines.com/index.html">http://www.mandarin-airlines.com/index.html</a></td>
                </tr>

                <tr>
                    <td>走過虹橋</td>
                    <td>972花蓮縣秀林鄉三鄰210號</td>
                    <td>03 862 1328</td>
                     <td> <a href="https://www.teyra.com.tw/">https://www.teyra.com.tw/</a></td>
                </tr>

                <tr>
                    <td>太魯閣晶英酒店</td>
                    <td>花蓮縣秀林鄉天祥18號</td>
                    <td>03-8691155</td>
                     <td> <a href="http://taroko.silksplace.com.tw/">http://taroko.silksplace.com.tw/</a></td>
                </tr>

                <tr>
                    <td>立德布洛灣-山月村</td>
                    <td>花蓮縣秀林鄉231-1號</td>
                    <td>	03-8610111</td>
                     <td> <a href="http://www.tarokovillage.com/">http://www.tarokovillage.com/</a></td>
                </tr>

                <tr>
                    <td>太魯閣旅店</td>
                    <td>花蓮縣秀林鄉258號</td>
                    <td>03-8611558</td>
                     <td> <a href="http://www.taroko-hotel.com.tw/i_main4.php">http://www.taroko-hotel.com.tw/i_main4.php</a></td>
                </tr>
            </tbody>
        </table>
    </p>
</div>

<h2 class="header-level-2" id="F">美食資訊:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    <p>
        <table border="1" cellpadding="5" cellspacing="0" width="90%">
            <thead>
                <tr>
                    <th width="30%">店名</th>
                    <th width="43%">地址 </th>
                    <th width="23%">聯絡電話 </th>
                    <th width="23%">營業時間 </th>
                </tr>
            </thead>
            <tbody>

                <tr>
                    <td>達基力部落屋</td>
                    <td>花蓮縣秀林鄉崇德村96號</td>
                    <td>03-8621033</td>
                    <td>11:30〜15:00</td>
                </tr>

                <tr>
                    <td>立德 布洛灣 山月邨</td>
                    <td> 花蓮縣秀林鄉富世村231-1號</td>
                    <td>03-8610111</td>
                    <td>立德布洛灣-山月村內的餐廳</td>
                </tr>

                <tr>
                    <td>太魯閣晶英酒店 梅園中餐廳</td>
                    <td>花蓮縣秀林鄉天祥路18號</td>
                    <td>03-8691155</td>
                    <td> 午餐12:00～14:30／晚餐17:30～19:15、19:30～21:30
</td>
                </tr>

                <tr>
                    <td>橫綱餐館</td>
                    <td>花蓮縣新城鄉新興路67號</td>
                    <td>03-8610970</td>
                    <td>11:00–14:00 17:00-20:00</td>
                </tr>

                <tr>
                    <td>佳興冰菓室 </td>
                    <td> 花蓮縣新城鄉新城村博愛路22號</td>
                    <td>03-8611888</td>
                    <td>08:00～17:00 週三公休</td>
                </tr>
            </tbody>
        </table>
    </p>
</div>

<h2 class="header-level-2">資料來源:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    <ul>
        <li><a href="http://np.cpami.gov.tw/">台灣國家公園</a></li>
        <br>
        <li><a href="https://www.taroko.gov.tw/">太魯閣國家公園</a></li>
        <br>
        
        <li><a href="https://travelbook.com.tw/topics/1641?p=3">travelbook</a></li>
        <br>
        <li><a href="https://www.trivago.com.tw/?themeId=457&iGeoDistanceItem=2512484&sem_keyword=%E9%99%BD%E6%98%8E%E5%B1%B1%20%E4%BD%8F%E5%AE%BF%20%E6%8E%A8%E8%96%A6&sem_creativeid=333376697745&sem_matchtype=e&sem_network=g&sem_device=c&sem_placement=&sem_target=&sem_adposition=1t1&sem_param1=&sem_param2=&sem_campaignid=1682128211&sem_adgroupid=71121431928&sem_targetid=kwd-635820411482&sem_location=1012825&cip=8861901253&gclid=EAIaIQobChMI3dPGgaKi4gIVGq6WCh2bkwmiEAAYASAAEgK6oPD_BwE">trivago</a></li>
        <br>
        <li><a href="https://zh.wikipedia.org/wiki/%E5%A4%AA%E9%AD%AF%E9%96%A3%E5%9C%8B%E5%AE%B6%E5%85%AC%E5%9C%92">維基百科</a></li>
    </ul>
</div>

<div class="button-bar">
    <a id="flip">選單</a>
    <a class="button" id="a" href="#">基本資訊</a>
    <a class="button" id="b" href="#">標示意涵</a>
    <a class="button" id="c" href="#">特色介紹</a>
    <a class="button" id="d" href="#">交通資訊</a>
    <a class="button" id="e" href="#">住宿資訊</a>
    <a class="button" id="f" href="#">美食資訊</a>
    <a class="button" id="top" href="#">網頁頂端</a>
    <a class="button" id="bottom" href="#">網頁底部</a>
    <a class="button" id="home" href="https://jim99224.github.io/HomePage/">返回主頁</a>
</div>



<div id="parkmap">
	
			<div class="parkmap_item" style="display: none;">
			<img class="bg-img" src="/filesys/image/park_map/ymsnp.jpg" alt="陽明山國家公園">
			<div class="bg-desc">
				陽明山國家公園位在臺灣北端，是我國第三個國家公園，前身為臺灣日治時期成立之大屯國立公園（1937-1945）。成立於1985年，面積11,338公頃，全區向來以特有的火山地形地貌著稱，以大屯山火山群為主，園內火山口、硫磺噴氣口、地熱及溫泉等景觀齊備，是個火山地形保持十分完整的國家公園。			</div>
		</div>
			<div class="parkmap_item" style="display: none;">
			<img class="bg-img" src="/filesys/image/park_map/spnp.jpg" alt="雪霸國家公園">
			<div class="bg-desc">
				雪霸國家公園是臺灣第五座國家公園成立於1992年，雪霸國家公園以雪山和大霸尖山的「雪」、「霸」兩字命名。北以邊古嚴山至樂山間之稜線為界，東界為大甲溪上游，西以北坑山至小雪山的天然稜線為主，南以宇羅尾山、大甲溪中游為界，地處新竹縣、苗栗縣、臺中市的交界處，總面積共有76,850公頃。			</div>
		</div>
			<div class="parkmap_item" style="display: none;">
			<img class="bg-img" src="/filesys/image/park_map/taroko.jpg" alt="太魯閣國家公園">
			<div class="bg-desc">
				太魯閣國家公園是臺灣第四座成立的國家公園於1986年成立，太魯閣國家公園橫跨花蓮、南投及臺中，以雄偉壯麗、幾近垂直的大理岩峽谷景觀聞名。沿著立霧溪的峽谷風景線而行，觸目所及皆是壁立千仞的峭壁、峽谷、連綿曲折的山洞隧道等風光。			</div>
		</div>
			<div class="parkmap_item" style="display: none;">
			<img class="bg-img" src="/filesys/image/park_map/ysnp.jpg" alt="玉山國家公園">
			<div class="bg-desc">
				玉山國家公園位居臺灣中央地帶，為我國第二座國家公園，前身為日治時期成立之新高阿里山國立公園（1937–1945）。園區內崇山峻嶺，臺灣三千公尺以上百岳名山有三十座位處其中，有氣勢磅礡、雄偉壯麗者，有奇峰俊秀、自成風格者，美不勝收，為一典型的山岳型國家公園。			</div>
		</div>
			<div class="parkmap_item" style="display: none;">
			<img class="bg-img" src="/filesys/image/park_map/ktnp.jpg" alt="墾丁國家公園">
			<div class="bg-desc">
				墾丁國家公園位於屏東縣境內，成立於1984年1月，是我國第一座成立的國家公園，三面環海，同時涵蓋陸域與海域。由於百萬年來地殼運動不斷的作用，陸地與海洋彼此交蝕影響，造就了本區高位珊瑚礁、海蝕地形、崩崖地形等奇特的地理景觀。
			</div>
		</div>
			<div class="parkmap_item" style="display: block;">
			<img class="bg-img" src="/filesys/image/park_map/kmnp.jpg" alt="金門國家公園">
			<div class="bg-desc">
				金門國家公園位於金門縣，為我國第六座國家公園，於1995成立管理處，是首座位於離島的國家公園，也是首座以維護歷史文化資產、戰役紀念為主，並兼具自然資源保育功能的國家公園。			</div>
		</div>
			<div class="parkmap_item" style="display: none;">
			<img class="bg-img" src="/filesys/image/park_map/tjnp.jpg" alt="台江國家公園">
			<div class="bg-desc">
				台江國家公園位於臺灣本島西南沿海，為我國第八座國家公園，成立於2009。
台江一名，源自歷史上的台江內海，多已陸化為濕地或魚塭。台江國家公園陸域縱貫臺南市沿海，跨越七股溪、曾文溪、鹿耳門溪、鹽水溪等四條溪流出海口，包括黑面琵鷺保護區、七股潟湖等區域，面積4,905公頃。
			</div>
		</div>
			<div class="parkmap_item" style="display: none;">
			<img class="bg-img" src="/filesys/image/park_map/spmnp.jpg" alt="澎湖南方四島國家公園">
			<div class="bg-desc">
				澎湖南方四島位於澎湖南方的東嶼坪嶼、西嶼坪嶼、東吉嶼、西吉嶼合稱澎湖南方四島。於南方四島遺世獨立，加上近幾十年來受到產業結構轉型、交通不便造成物資補給不易等影響，人口逐漸外移，現今島上除了少數居民外，平日少有遊客造訪。			</div>
		</div>
			<div class="parkmap_item" style="display: none;">
			<img class="bg-img" src="/filesys/image/park_map/danp.jpg" alt="東沙環礁國家公園">
			<div class="bg-desc">
				東沙環礁國家公園包含南海的東沙島與其環礁，及附近海域，總面積為353,667.95公頃，為我國第一座海洋國家公園，於2007年1月17日成立，擁有我國海域唯一發育完整的環礁，係由珊瑚礁經千萬年的生長堆積而形成，屬於特殊珍貴自然景觀，足以代表國家自然遺產，因此成為我國第七座新設立的國家公園。			</div>
		</div>
			<div class="parkmap_item" style="display: none;">
			<img class="bg-img" src="/filesys/image/park_map/snnp.jpg" alt="壽山國家自然公園">
			<div class="bg-desc">
				位處高雄市的壽山國家自然公園，不但是高雄都會地區難得的綠地，也是一座極為珍貴的自然寶庫，更承載了數百年來不同族群發展的歷史變遷。兼具教育、研究及觀賞遊憩等多重功能，不僅僅是高雄市的都市之肺，更是絕佳的自然人文教育及研究基地。			</div>
		</div>
		

	<div class="map">
		<img id="taiwan_map" src="http://np.cpami.gov.tw/modules/mod_parkmap/assets/img/map_tw.png" alt="臺灣地圖">

					<a href="javascript:void(0);" title="陽明山國家公園" class="park_item">
				<img id="park_1" class="park_img" src="http://np.cpami.gov.tw/modules/mod_parkmap/assets/img/park_1.png" alt="陽明山國家公園">
			</a>
					<a href="javascript:void(0);" title="雪霸國家公園" class="park_item">
				<img id="park_2" class="park_img" src="http://np.cpami.gov.tw/modules/mod_parkmap/assets/img/park_2.png" alt="雪霸國家公園">
			</a>
					<a href="javascript:void(0);" title="太魯閣國家公園" class="park_item">
				<img id="park_3" class="park_img" src="http://np.cpami.gov.tw/modules/mod_parkmap/assets/img/park_3.png" alt="太魯閣國家公園">
			</a>
					<a href="javascript:void(0);" title="玉山國家公園" class="park_item">
				<img id="park_4" class="park_img" src="http://np.cpami.gov.tw/modules/mod_parkmap/assets/img/park_4.png" alt="玉山國家公園">
			</a>
					<a href="javascript:void(0);" title="墾丁國家公園" class="park_item">
				<img id="park_5" class="park_img" src="http://np.cpami.gov.tw/modules/mod_parkmap/assets/img/park_5.png" alt="墾丁國家公園">
			</a>
					<a href="javascript:void(0);" title="金門國家公園" class="park_item">
				<img id="park_6" class="park_img" src="http://np.cpami.gov.tw/modules/mod_parkmap/assets/img/park_6_hover.png" alt="金門國家公園">
			</a>
					<a href="javascript:void(0);" title="台江國家公園" class="park_item">
				<img id="park_7" class="park_img" src="http://np.cpami.gov.tw/modules/mod_parkmap/assets/img/park_7.png" alt="台江國家公園">
			</a>
					<a href="javascript:void(0);" title="澎湖南方四島國家公園" class="park_item">
				<img id="park_8" class="park_img" src="http://np.cpami.gov.tw/modules/mod_parkmap/assets/img/park_8.png" alt="澎湖南方四島國家公園">
			</a>
					<a href="javascript:void(0);" title="東沙環礁國家公園" class="park_item">
				<img id="park_9" class="park_img" src="http://np.cpami.gov.tw/modules/mod_parkmap/assets/img/park_9.png" alt="東沙環礁國家公園">
			</a>
					<a href="javascript:void(0);" title="壽山國家自然公園" class="park_item">
				<img id="park_10" class="park_img" src="http://np.cpami.gov.tw/modules/mod_parkmap/assets/img/park_10.png" alt="壽山國家自然公園">
			</a>
		
	</div>
	<noscript>
		您的瀏覽器不支援javascript, 部份功能無法正常使用	</noscript>
</div>
<div class="tr calendar-month-header"><div class="th last-month"><a class="calendar-month-navigation calendar-month-prev" href="javascript: void(0);" title="上個月" id="zabuto_calendar_1yk8_nav-prev"><span><i class="fa fa-chevron-circle-left"></i></span></a></div><div class="th this-month"><span>2019 年 5 月</span></div><div class="th next-month"><a class="calendar-month-navigation calendar-month-next" href="javascript: void(0);" title="下個月" id="zabuto_calendar_1yk8_nav-next"><span><i class="fa fa-chevron-circle-right"></i></span></a></div></div>
