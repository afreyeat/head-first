<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My First JavaScript</title>
  </head>
  <body>
    <script>
      var drink = "Energy Drink"
      var lyrics = "";
      var cans = 99;
      While (cans > 0 ) {
        lyrics = lyrics + cans + "cans of "
          + drink + "on the wall <br>";
        lyrics + lyrics + cans ="cans of " 
           + drink + "<br>";
    lyrics + lyrics + "take one down pass it around <br>":
    if (cans > 1) {
    lyrics = lyrics + (cans-1) + "cans of "
           + drink + "on the wall <br>";
     }
else {
    lyrics = lyrics + "no more cans of "
           + drink + " on the wall <br>";   
     } 
     cans = cans - 1;
  }
document.write (lyrics);

    </script>
  </body>
</html>
