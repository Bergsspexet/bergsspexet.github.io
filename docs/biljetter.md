# Grande finale Biljetter

Föreställningen börjar om:

<div id="countdown" style="font-size: 1.2em; font-weight: bold; text-align: center; margin: 20px auto;">
  <span id="weeks"></span> veckor, 
  <span id="days"></span> dagar, 
  <span id="hours"></span> timmar, 
  <span id="minutes"></span> minuter och 
  <span id="seconds"></span> sekunder.
</div>

[Köp biljetter i detta formulär!](https://forms.gle/z2mCXafh2DVhxtZf9)

För frågor maila oss på [bergsspexet@gmail.com](mailto:bergsspexet@gmail.com)

### Konglig Bergs Spectacle Sellskapss Grande Finale av det 82:a Beregsspexet
Vi räknar ned till vår Petite och Grande Finale av det 82:a Bergsspexet

Petite Finale: Fredagen den 1 maj kl. 16:30 🕟

Grande finale: Lördagen den 2 maj kl. 13:30 🕜

Inklusive paus är tillställningen ungefär 3h lång.

<script>
  var targetDate = new Date("May 2, 2026 13:30:00").getTime();

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

![](https://docs.google.com/spreadsheets/d/e/2PACX-1vTlRd0nuGd5BP6teFZljuh_80VjGZaQbH5sTqDk14dPuQbXFtxWAxH9PGHBroXk_hXhK20MA-_jPuOs/pubchart?oid=1860846324&format=image)
