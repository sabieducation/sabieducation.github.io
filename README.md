"# sabieducation.github.io" 
"Biswadeep Sarkar"
<!DOCTYPE HTML>
<html>
<head>
  <script type="text/javascript">
  window.onload = function () {
    var chart = new CanvasJS.Chart("chartContainer",
    {
      title:{
        text: "Olympic Medals of all Times (till 2012 Olympics)"
      },
      axisY: {
        title: "Medals won",
        maximum: 1010
      },
      data: [
      {
        type: "bar",
        showInLegend: true,
        legendText: "Gold",
        color: "gold",
        dataPoints: [
        { y: 198, label: "Italy"},
        { y: 201, label: "China"},
        { y: 202, label: "France"},
        { y: 236, label: "Great Britain"},
        { y: 395, label: "Soviet Union"},
        { y: 957, label: "USA"}
        ]
      },
      {
        type: "bar",
        showInLegend: true,
        legendText: "Silver",
        color: "silver",
        dataPoints: [
        { y: 166, label: "Italy"},
        { y: 144, label: "China"},
        { y: 223, label: "France"},
        { y: 272, label: "Great Britain"},
        { y: 319, label: "Soviet Union"},
        { y: 759, label: "USA"}
        ]
      },
      {
        type: "bar",
        showInLegend: true,
        legendText: "Bronze",
        color: "#DCA978",
        dataPoints: [
        { y: 185, label: "Italy"},
        { y: 128, label: "China"},
        { y: 246, label: "France"},
        { y: 272, label: "Great Britain"},
        { y: 296, label: "Soviet Union"},
        { y: 666, label: "USA"}
        ]
      }
      ]
    });

chart.render();
}
</script>
<script type="text/javascript" src="https://canvasjs.com/assets/script/canvasjs.min.js"></script></head>
<body>
  <div id="chartContainer" style="height: 300px; width: 100%;">
  </div>
</body>
</html>
