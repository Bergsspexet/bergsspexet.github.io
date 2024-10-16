# Kontakt

<a href="#" id="email-link">Mejla oss!</a>

<script>
    document.getElementById('email-link').addEventListener('click', function(event) {
        event.preventDefault();
        var user = "bergsspexet"; // Replace with your email username
        var domain = "gmail.com"; // Replace with your email domain
        var email = user + "@" + domain;
        window.location.href = "mailto:" + email;
    });
</script>