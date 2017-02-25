<html>
  <header>
    <script>
      function genereUrl() {
        window.location.href = 'http://bit.ly/'+document.getElementById('code').value;
      }
    </script>
  </header>
  <body>
    <input type="text" id="code" />
    <input type="button" value="Entrer" onclick="genereUrl()">
  </body>
</html>
