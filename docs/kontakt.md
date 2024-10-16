# Kontakt

Mejla vår <a href="_blank" id="email-link">e-post</a>!

Eller skicka brev till:

```markdown
Konglig Bergs Spectacle Sällskap

c/o KTH, Kårhuset THS 
Drottning Christinas Väg 15-19  
100 44 Stockholm  
```
<script>
    // The purpose of this: To counteract spam bots from scraping the email address, this solution makes it harder for them to find it. Compared to if the email address was written in plain text on the website.

    // What the script does: This script will open the default email client with a new email to the specified address. 
    document.getElementById('email-link').addEventListener('click', function(event) {
        event.preventDefault();
        var user = "bergsspexet"; // Replace with your email username
        var domain = "gmail.com"; // Replace with your email domain
        var email = user + "@" + domain;
        window.location.href = "mailto:" + email;
    });
</script>