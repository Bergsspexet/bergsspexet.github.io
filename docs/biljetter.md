# Biljetter

Bergslussepremiären för det 81:a Bergsspexet äger rum på Teater3 den 14 december 2024.

### Spexpremiärens nedräkning
Vi räknar ned till Spexpremiären av det 81:a Bergsspexet: "Det stålta Järnälvsundshotellet; ...eller en skänk från ovan."

<!-- <div id="countdown" style="font-size: 2em; color: #d9534f;"></div>

<script>
  // Set the target date
  var targetDate = new Date("Dec 31, 2024 23:59:59").getTime();

  // Update the countdown every 1 second
  var countdownFunction = setInterval(function() {
    // Get the current date and time
    var now = new Date().getTime();
    
    // Calculate the distance between now and the target date
    var distance = targetDate - now;
    
    // Time calculations for weeks, days, hours, minutes, and seconds
    var weeks = Math.floor(distance / (1000 * 60 * 60 * 24 * 7));
    var days = Math.floor((distance % (1000 * 60 * 60 * 24 * 7)) / (1000 * 60 * 60 * 24));
    var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    var seconds = Math.floor((distance % (1000 * 60)) / 1000);
    
    // Display the result in the "countdown" element
    document.getElementById("countdown").innerHTML = 
      weeks + " veckor\n" + days + " dagar " + hours + " timmar " + 
      minutes + " minuter " + seconds + " sekunder";
    
    // If the countdown is over, display a message
    if (distance < 0) {
      clearInterval(countdownFunction);
      document.getElementById("countdown").innerHTML = "The countdown is over!";
    }
  }, 1000);
</script> -->

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