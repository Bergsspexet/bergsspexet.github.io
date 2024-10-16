# Biljetter

Bergslussepremiären för det 81:a Bergsspexet äger rum på Teater3 den 14 december 2024. Räkna med biljettsläpp i november 2024.

### Spexpremiärens nedräkning
Vi räknar ned till Spexpremiären av det 81:a Bergsspexet: "Det stålta Järnälvsundshotellet; ...eller en skänk från ovan." Föreställningen börjar om:

<div id="countdown" style="font-size: 1.2em; font-weight: bold; text-align: center; margin: 20px auto;">
  <span id="weeks"></span> veckor, 
  <span id="days"></span> dagar, 
  <span id="hours"></span> timmar, 
  <span id="minutes"></span> minuter och 
  <span id="seconds"></span> sekunder.
</div>


<script>
  var targetDate = new Date("Dec 14, 2024 13:00:00").getTime();

  var countdownFunction = setInterval(function() {
    var now = new Date().getTime();
    var distance = targetDate - now;

    var weeks = Math.floor(distance / (1000 * 60 * 60 * 24 * 7));
    var days = Math.floor((distance % (1000 * 60 * 60 * 24 * 7)) / (1000 * 60 * 60 * 24));
    var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    var seconds = Math.floor((distance % (1000 * 60)) / 1000);
    
    document.getElementById("weeks").innerHTML = weeks;
    document.getElementById("days").innerHTML = days;
    // document.getElementById("time").innerHTML = hours + ":" + minutes + ":" + seconds;
    document.getElementById("hours").innerHTML = hours;
    document.getElementById("minutes").innerHTML = minutes;
    document.getElementById("seconds").innerHTML = seconds;

    if (distance < 0) {
      clearInterval(countdownFunction);
      document.getElementById("countdown").innerHTML = "Bergslusse nedräkningen klar!";
    }
  }, 1000);
</script>