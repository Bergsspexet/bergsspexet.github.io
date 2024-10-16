# Biljetter

Bergslussepremiären för det 81:a Bergsspexet äger rum på Teater3 den 14 december 2024.

### Spexpremiärens nedräkning
Vi räknar ned till Spexpremiären av det 81:a Bergsspexet: "Det stålta Järnälvsundshotellet; ...eller en skänk från ovan."

<table id="countdown-table" style="font-size: 1em; text-align: center; border-collapse: collapse; margin: 0 auto;">
  <tr>
    <th>Veckor</th>
    <th>Dagar</th>
    <th>Timmar</th>
    <th>Minuter</th>
    <th>Sekunder</th>
  </tr>
  <tr>
    <td id="weeks"></td>
    <td id="days"></td>
    <td id="hours"></td>
    <td id="minutes"></td>
    <td id="seconds"></td>
  </tr>
</table>

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
    document.getElementById("hours").innerHTML = hours;
    document.getElementById("minutes").innerHTML = minutes;
    document.getElementById("seconds").innerHTML = seconds;

    if (distance < 0) {
      clearInterval(countdownFunction);
      document.getElementById("countdown-table").innerHTML = "The countdown is over!";
    }
  }, 1000);
</script>