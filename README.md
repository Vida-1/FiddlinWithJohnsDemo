# FiddlinWithJohnsDemo - This code written by John Cokos
sandbox

<!DOCTYPE html>
<html>

<head>
  <title>JS Demo</title>

</head>

<body>
  <main>
    <ul>
      <script>
        let name = prompt("What is your name?");
        document.write("<li>Nice to meet you " + name + "</li>");
        let year = prompt("What year were you born?");
        let age = 2022 - year;
        document.write("<li>Wow " + age + " is pretty old</li>");
      </script>
    </ul>
  </main>
</body>

</html>
