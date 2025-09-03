# user-gold
<!DOCTYPE html>
<html> **
<head><title>Calculator</title></head>
<body>
  <input id="num1" type="number">
  <input id="num2" type="number">
  <button onclick="add()">Add</button>
  <p id="result"></p>

  <script>
    function add() {
      const a = parseFloat(document.getElementById("num1").value);
      const b = parseFloat(document.getElementById("num2").value);
      document.getElementById("result").innerText = "Result: " + (a + b);
    }
  </script>
</body>
</html>
