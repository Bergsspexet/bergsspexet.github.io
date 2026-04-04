# Grande finale Biljetter

<a href="https://forms.gle/z2mCXafh2DVhxtZf9"
   style="display:inline-block; padding:14px 18px; background:#e11d48; color:white; font-weight:700; border-radius:10px; text-decoration:none;">
  Köp biljetter (tar ca 1 min)
</a>

<div style="margin-top:8px; opacity:0.9;">
  Snabbt formulär • Betalning + formulär = anmälan • Frågor/teknik: <a href="mailto:bergsspexet@gmail.com">bergsspexet@gmail.com</a>
</div>

<div style="margin-top:10px; opacity:0.9;">
  Begränsat antal platser – säkra din plats i tid.
</div>

---

## Det viktigaste

**Det 82:a Bergsspexets Vårföreställningar**  

**Petite Finale:** Fredag 1 maj 2026 kl. 16:30 🕟  
**Grande Finale:** Lördag 2 maj 2026 kl. 13:30 🕜  

**Plats:** [Tibble Teatern, Attundavägen 1, Täby](https://maps.app.goo.gl/MnNGC1f8hirJ9DsbA)  
**Längd:** ca 3 timmar  

**Pris:** 180 kr student • 280 kr ordinarie  

---

## Vad är det här? (kort)

Bergsspexet är ett studentspex: musik, humor och publikinteraktion.  
Du behöver inte kunna något om handlingen för att ha kul – kom som du är.

---

## Nedräkning till nästa föreställning

<div id="countdown" style="font-size: 1.2em; font-weight: bold; text-align: center; margin: 20px auto;">
  <div id="countdownTitle" style="margin-bottom: 6px;"></div>
  <span id="weeks"></span> veckor,
  <span id="days"></span> dagar,
  <span id="hours"></span> timmar,
  <span id="minutes"></span> minuter och
  <span id="seconds"></span> sekunder.
</div>

<script>
  // Väljer automatiskt "nästa" föreställning att räkna ner till:
  // - innan 1 maj: räknar ner till Petite Finale
  // - mellan 1 maj och 2 maj: räknar ner till Grande Finale
  // - efter 2 maj: visar avslutad text
  var show1 = new Date("May 1, 2026 16:30:00").getTime(); // Petite Finale
  var show2 = new Date("May 2, 2026 13:30:00").getTime(); // Grande Finale

  function pickTarget(now) {
    if (now < show1) return { date: show1, title: "Nästa: Petite Finale (1 maj 2026 16:30 🕟)" };
    if (now < show2) return { date: show2, title: "Nästa: Grande Finale (2 maj 2026 13:30 🕜)" };
    return { date: null, title: "Föreställningarna är över – håll utkik efter nästa!" };
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

<a href="https://forms.gle/z2mCXafh2DVhxtZf9"
   style="display:inline-block; padding:14px 18px; background:#e11d48; color:white; font-weight:700; border-radius:10px; text-decoration:none;">
  Köp biljetter i formuläret
</a>

<div style="margin-top:8px; opacity:0.9;">
  Betalningen + svar på formuläret är tillsammans din anmälan.
</div>

---

## FAQ

**Hur anmäler jag mig?**  
Du är anmäld när du både har betalat och skickat in formuläret.

**Var är det?**  
[Tibble Teatern, Attundavägen 1, Täby](https://maps.app.goo.gl/MnNGC1f8hirJ9DsbA)

**Hur lång är föreställningen?**  
Ungefär 3 timmar.

**Jag har frågor eller tekniska problem.**  
Maila oss på [bergsspexet@gmail.com](mailto:bergsspexet@gmail.com)

**Grande Finale Gasque?**  
(Formulär för Grande Finale Gasque tillkommer senare.)
