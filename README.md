# <html><meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/>
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@400;700&display=swap" rel="stylesheet"><script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script><script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script><link href="style.css" rel="stylesheet" type="text/css" /><script src="https://hbd.htmlku.repl.co/script.js"></script>
<head>

  <title>Love</title>
<!-- 
  Made with love by Somu!

-->
</head>
<style>
:root {
--warna-bg: rgba(0, 0, 0, .7); 
--warna-teks: white;
--bingkai: 14px;
--gaya-font: 'Josefin Sans', sans-serif;
}
</style>
<body><div id="bodyblur"><img id="wallpaper" src="" width="100%" height="100%"/><div id="beneranblur"></div></div>
<!-- <audio src="https://prodigits.co.uk/content/ringtones/tone/2020/various/aedilhaim_3bba60fe5304628.mp3" controls autoplay></audio> -->
<div id='Content'>

<div><marquee id="imglewat" direction="right"><img id="fotonimasi" src="" width="100px" height="100px"/></marquee></div>

<div><div id='pergeseran'>

<!-- Pesan -->
<p><b><img src="https://i.ibb.co/QdSLq11/Screenshot-20220701-134808.jpg"/><br>
	<span>Batak🦆</span>
</b></p>

<p><b><img src="https://i.ibb.co/37NSQCN/Screenshot-20220701-134916.jpg"/><br>
	<span>Cute Smile🙂</span>
</b></p>

<p><b><img src="https://i.ibb.co/0Yz6kcm/Screenshot-20220701-134952.jpg"/><br>
	<span>Attractive Looks😉</span>
</b></p>

<p><b><img src="https://i.ibb.co/y5mjKZX/Screenshot-20220701-135021.jpg"/><br>
	<span>Luscious Face🤪</span>
</b></p>

<p><b><img src="https://i.ibb.co/WHpcHsz/Screenshot-20220701-135240.jpg"/><br>
	<span>Beautiful Cheeks😊</span>
</b></p>

<!-- Tombol Akhir --><p><b><img id="fotolove" src="https://maafin.feeldream.repl.co/love.gif" onClick="akhiran();"/><br>
	<span>Touch My Heart❤️</span>
</b></p>

</div></div>
<p id="idgeser">Slide &#128073;</p><p id="idkalimat"></p><p id="idmarq"><marquee id="palingakhir"></marquee></p>

<!-- Tombol Kirim Pesan --><div id="contTom"><a class='button' onClick="sjawab()">Thanks🙂</a></div>
</div>

<script>
  function nongeser() {idgeser.style = "transform: scale(.1);opacity:0";fotolove.style="opacity:1;visibility:visible";} function showDiv() {setTimeout(kpemb,100);setTimeout(nongeser,2500);document.getElementById('Content').style = "opacity:1;margin-top:10vh;animation:none 3s infinite;";document.getElementById("pergeseran").style = "opacity:1;visibility:visible;";}
  function showAkhir() {setInterval(createHeart,200);document.getElementById('k2').style = "opacity:1;transform:scale(1);margin:0;";document.getElementById('Content').style.display = "none";} function mulaiakhir() {nonDiv();setTimeout(showAkhir,500);setTimeout(finalis,600);}
  function tombol(){contTom.style="margin-top:20px;opacity:1;transform: scale(1);";ftom=1;} ftom=0; function sjawab(){if(ftom==1){jawab();}} var aa=0,pemb;pemb = "";var i=0,halo;halo = "";var u=0,text2;text2 = "";var o=0,text3;text3 = "";var a=0,final1;final1 = "";var ab=0,final2;final2 = ""; function kpemb() {document.getElementById('bodyblur').style = "opacity:.7;";}
  function finalis() {document.getElementById("bq").style = "opacity:1;visibility:visible;margin-top:0";setTimeout(showTom,4000);} const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040',}); const swalsy = Swal.mixin({confirmButtonText: 'Iya', allowOutsideClick: false,}); const swalst = Swal.mixin({allowOutsideClick: false, showConfirmButton: false, timer: 1000, timerProgressBar: true, didOpen: () => {Swal.showLoading();const b = Swal.getHtmlContainer().querySelector('b');timerInterval = setInterval(() => {Swal.getTimerLeft()}, 100)},willClose: () => {clearInterval(timerInterval)}}); const style = document.createElement('style');
  
  function play() {var audio = new Audio('' + linkmp3);audio.play();} const body = document.querySelector("body");function createHeart() {const heart = document.createElement("div"); heart.className = "fas fa-heart"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-heart"); if (heartArr.length > 100) {heartArr[0].remove()}},100); function StartMarqueeL(){imglewat.style="opacity:1;height:100px;";var marquee = document.getElementById ("imglewat");marquee.start();}function StopMarqueeL(){var marquee = document.getElementById ("imglewat");marquee.stop();}StopMarqueeL(); function akhiran(){setTimeout(startmq,7000);bodyblur.style="opacity:.4;animation:none";beneranblur.style="-webkit-backdrop-filter:blur(5px); backdrop-filter:blur(5px)";wallpaper.style="transform: scale(1.6)";pergeseran.style="display:none";StartMarqueeL();idgeser.innerHTML = "";idkalimat.innerHTML = akhirkata2;idgeser.style = "opacity:1;transform: scale(1);font-size:16px;font-weight:400;margin:0 30px;margin-top:15px;";setTimeout(aksiakhir,800);}
  function startmq(){var marquee = document.getElementById ("palingakhir");marquee.start();}function stopmq(){var marquee = document.getElementById ("palingakhir");marquee.stop();}stopmq(); async function menuju(){await swals.fire('OK!', 'Send Message to Whastapp', 'success');
  window.location = "https://api.whatsapp.com/send?phone=&text=" + pesanwhatsapp;} var aa=0,akhirkata;akhirkata = "";function aksiakhir() {if(aa<akhirkata.length){idgeser.innerHTML += akhirkata.charAt(aa);aa++;setTimeout(aksiakhir,65);} if(aa==akhirkata.length){idkalimat.style = "opacity:1;transform: scale(1);font-size:16px;margin-top:20px";setTimeout(showpalingakhir,1100);}} function showpalingakhir(){palingakhir.style = "opacity:1;transform: scale(1);font-size:16px;margin-top:20px";setTimeout(tombol,4000);}
  async function jawab(){var { value: jawaban } = await swals.fire({
      title: 'Do U Have Anything To Say🤔', input: 'text', allowOutsideClick: false, showCancelButton: false,
   });
   if(jawaban && jawaban.length < 21){window.jawaban = jawaban;pesanwhatsapp = jawaban;menuju();} else {await swals.fire('Ups!', 'Message Cannot be empty or more than 20 characters..');}
   }
   async function lanjut() {
      await swals.fire('Hello🙃', 'Beautiful :)');showDiv();audio.play();
   }
</script>

<script type="text/javascript">
       async function pertama(){
       	 wallpaper.src = "LINKWP";
            fotonimasi.src = "https://feeldreams.github.io/nimasi.gif";
       	 audio = new Audio('https://prodigits.co.uk/content/ringtones/tone/2020/various/aedilhaim_3bba60fe5304628.mp3'); audio.play();
  audio.loop=true;audio.addEventListener('ended', function() {this.currentTime = 0;this.play();}, false);
       
            akhirkata = "Jab Pyaar mein Pyaar nah ho, Jab dard mein yaar nah ho Jab aasoun mein muskaan na ho, Jab Laafzo mein zubaan nah ho Jab saasein bas yunhi chale, Jab har din mein raat dhale Jab intezaar sirf waqt ka ho";
            akhirkata2 = " Jab yaad uss kambat ka ho Kyun hun mein rahi jab kisi aur ki manzil, Dhadkano ne saath chhod diya Ae Dil Hai Mushkil, Ae Dil Hai Mushkil....";
            palingakhir.innerHTML = "My Heart Beats Only For U ";
            
            lanjut();
        }
        pertama();
</script>
</body>
</html>
