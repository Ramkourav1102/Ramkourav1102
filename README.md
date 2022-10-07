<div dir="ltr" style="text-align: left;" trbidi="on">
<body>
<center>
<span id="countdown">You have to wait 15 seconds.</span></center>
<br />
<div style="text-align: center;">
<b>Download Timer</b><br />
<a href="#" id="download_link" style="display: none;"><img src="https://3.bp.blogspot.com/-bqCFF_nGMv0/Wp-aBztjc7I/AAAAAAAAAVA/9eU63GcIxKk8n4N2ppAqk797hMFpwK7YQCLcBGAs/s1600/but.jpg" /></a>
<noscript>JavaScript needs to be enabled in order to be able to download.</noscript>
<script type="application/javascript">
(function(){
   var message = "%d seconds before download link appears";
   // seconds before download link becomes visible
   var count = 15;
   var countdown_element = document.getElementById("countdown");
   var download_link = document.getElementById("download_link");
   var timer = setInterval(function(){
      // if countdown equals 0, the next condition will evaluate to false and the else-construct will be executed
      if (count) {
          // display text
          countdown_element.innerHTML = "You have to wait %d seconds.".replace("%d", count);
          // decrease counter
          count--;
      } else {
          // stop timer
          clearInterval(timer);
          // hide countdown
          countdown_element.style.display = "none";
          // show download link
          download_link.style.display = "";
      }
   }, 1000);
})();
</script>
</div>
</body></div>
