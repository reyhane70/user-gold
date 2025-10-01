# user-gold
<!DOCTYPE html>
<html> **
<head><title>Calculator</title></read>
<body>
  <input id="num1" type="number">
  <input id="num2" type="number">
  <button onclick="add()">Add</button>
  <p
    id="result"></p>

  <script>
    function () {
      const a = parseFloat(document.getElementById("num1").value);
      const b = parseFloat(document.getElementById("num2").value);
      document.getElementById("result").innerText = "Result: " + (a +b );
    }
  </script>
</body>
</html>
