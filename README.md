<html>
<body>

<button onclick="myFunction()">About the Visualization</button>

<p id="demo"></p>

<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Hello World";
}
</script>

echo "Before Read"
d3.tsv("data.tsv", function(data) {
  console.log(data[0].x);
});

echo "After Read"
</body>
</html>
