# Bergsspexets 83:e premiär - Biljetter

<a href="https://docs.google.com/forms/d/e/1FAIpQLSetPb7UAxCNKGYo4vORZqrnLqoE-PebXAShJJkDRwkCkX8nQg/viewform?usp=header"
   style="display:inline-block; padding:14px 18px; background:#e11d48; color:white; font-weight:700; border-radius:10px; text-decoration:none;">
  Köp biljetter (tar ca 1 min)
</a>

<div style="margin-top:8px; opacity:0.9;">
  Boka i formuläret och få orderbekräftelse och faktura via e-post. Frågor: <a href="mailto:bergsspexet@gmail.com">bergsspexet@gmail.com</a>
</div>

<div style="margin-top:10px; opacity:0.9;">
  Begränsat antal platser - boka i tid.
</div>

---

## Det viktigaste

**Bergsspexets 83:e premiär**  

**Datum:** Lördag 5 december 2026  
**Start:** kl. 13:00  
**Dörrarna öppnas:** kl. 12:30  

**Plats:** [CONFIDENCEN, Slottsallén, 170 79 Solna](https://www.google.com/maps/search/?api=1&query=CONFIDENCEN%2C%20Slottsall%C3%A9n%2C%20170%2079%20Solna)  
**Kollektivtrafik:** Närmaste hållplats är Ulriksdals wärdshus.  
**Parkering:** Det finns parkering mitt emot teatern.  

**Pris:** 180 kr student, 280 kr ordinarie.

---

## Bokning och betalning

Fyll i bokningsformuläret före föreställningen. Du får en orderbekräftelse och en faktura via e-post med dina biljetter och eventuella tillval.

Betala gärna så snart som möjligt via Swish eller bankgiro. Ange betalningsreferensen på fakturan, eller skanna fakturans Swish-QR-kod.

**Betalningsfrist:** normalt 7 dagar från fakturadatum, dock senast 4 december 2026. Vid sena bokningar blir fristen kortare. Det förfallodatum som står på din faktura gäller.

Betalningen kontrolleras manuellt, vilket kan ta några dagar. Biljetten skickas via e-post när betalningen har bekräftats. Om du redan har betalat ska du inte betala igen.

---

## Om Bergsspexet

Bergsspexet är ett studentspex: musik, humor och publikinteraktion.  
Du behöver inte kunna något om handlingen för att ha kul - kom som du är.

---

## Nedräkning till premiären

<div id="countdown" style="font-size: 1.2em; font-weight: bold; text-align: center; margin: 20px auto;">
  <div id="countdownTitle" style="margin-bottom: 6px;"></div>
  <span id="weeks"></span> veckor,
  <span id="days"></span> dagar,
  <span id="hours"></span> timmar,
  <span id="minutes"></span> minuter och
  <span id="seconds"></span> sekunder.
</div>

<script>
  const premiereTime = new Date("2026-12-05T13:00:00+01:00").getTime();

  function pickTarget(now) {
    if (now < premiereTime) return { date: premiereTime, title: "Premiär: lördag 5 december 2026 kl. 13:00" };
    return { date: null, title: "Premiären har börjat. Tack för ditt intresse!" };
  }

  var countdownFunction = setInterval(function() {
    var now = new Date().getTime();
    var target = pickTarget(now);

    var titleEl = document.getElementById("countdownTitle");
    var boxEl = document.getElementById("countdown");

    if (!target.date) {
      clearInterval(countdownFunction);
      titleEl.innerHTML = target.title;
      boxEl.innerHTML = "<div style='font-weight:bold; text-align:center;'>" + target.title + "</div>";
      return;
    }

    titleEl.innerHTML = target.title;

    var distance = target.date - now;

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
      document.getElementById("weeks").innerHTML = 0;
      document.getElementById("days").innerHTML = 0;
      document.getElementById("hours").innerHTML = 0;
      document.getElementById("minutes").innerHTML = 0;
      document.getElementById("seconds").innerHTML = 0;
    }
  }, 1000);
</script>

---

## Köp biljetter

<a href="https://docs.google.com/forms/d/e/1FAIpQLSetPb7UAxCNKGYo4vORZqrnLqoE-PebXAShJJkDRwkCkX8nQg/viewform?usp=header"
   style="display:inline-block; padding:14px 18px; background:#e11d48; color:white; font-weight:700; border-radius:10px; text-decoration:none;">
  Köp biljetter i formuläret
</a>

<div style="margin-top:8px; opacity:0.9;">
  Du får en orderbekräftelse och faktura via e-post efter bokningen.
</div>

---

## FAQ

**Hur funkar anmälan och betalning?**  
Fyll i formuläret före föreställningen. Orderbekräftelse och faktura skickas via e-post. När vi har kontrollerat betalningen skickar vi biljetten. Förfallodatum och betalningsreferens finns på fakturan.

**Var är det?**  
[CONFIDENCEN, Slottsallén, 170 79 Solna](https://www.google.com/maps/search/?api=1&query=CONFIDENCEN%2C%20Slottsall%C3%A9n%2C%20170%2079%20Solna)

**När ska jag vara där?**  
Dörrarna öppnas kl. 12:30 och föreställningen börjar kl. 13:00 lördagen den 5 december 2026.

**Hur tar jag mig dit?**  
Närmaste hållplats är Ulriksdals wärdshus. Parkering finns mitt emot teatern.

**Jag har betalat men inte fått någon biljett.**  
Betalningar kontrolleras manuellt och det kan ta några dagar. Kontakta oss om du saknar din biljett inför föreställningen. Ange gärna ordernummer eller biljett-ID, och betala inte igen.

**Jag har frågor eller tekniska problem.**  
Maila oss på [bergsspexet@gmail.com](mailto:bergsspexet@gmail.com)

---

## QR-kod

Skanna QR-koden för att öppna den här sidan i mobilen:

[![QR-kod till biljettsidan](./qr-code_bergsspexet-com-biljetter.png)](./biljetter.html)
