misty@mail.co.uk - 🌫️ - 2025

<script>
  document.addEventListener('DOMContentLoaded', function () {
    const headings = document.querySelectorAll('main h2, main h3, main h4');
    headings.forEach(function (heading) {
      heading.addEventListener('click', function () {
        window.location.hash = heading.id;
      });
    });
  });
</script>
