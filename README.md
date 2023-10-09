<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <div class="mic">
  <i class="mic-icon"></i>
  <div class="mic-shadow"></div>
  <audio id="music">
      <source src = "https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3";>
  </audio>
</div>

<script>
   var music = document.getElementById("music")

  music.load();

  document.addEventListener("click", function() {

  music.play()

  }) 
</script>
    </body>
</html>
