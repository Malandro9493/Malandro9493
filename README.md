[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FMalandro9493%2FMalandro9493.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FMalandro9493%2FMalandro9493?ref=badge_shield)

- 👋 Hi, I’m @Malandro9493
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Malandro9493/Malandro9493 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->git@gitlab.com:Malandro9493/facebook-hack.git

https://www.gstatic.com/charts/loader.js

## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FMalandro9493%2FMalandro9493.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FMalandro9493%2FMalandro9493?ref=badge_large)<html>
  <head>
    <script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
    <script type="text/javascript">
      google.charts.load('current', {'packages':['timeline']});
      google.charts.setOnLoadCallback(drawChart);
      function drawChart() {
        var container = document.getElementById('timeline');
        var chart = new google.visualization.Timeline(container);
        var dataTable = new google.visualization.DataTable();

        dataTable.addColumn({ type: 'string', id: 'President' });
        dataTable.addColumn({ type: 'date', id: 'Start' });
        dataTable.addColumn({ type: 'date', id: 'End' });
        dataTable.addRows([
          [ 'Washington', new Date(1789, 3, 30), new Date(1797, 2, 4) ],
          [ 'Adams',      new Date(1797, 2, 4),  new Date(1801, 2, 4) ],
          [ 'Jefferson',  new Date(1801, 2, 4),  new Date(1809, 2, 4) ]]);

        chart.draw(dataTable);
      }
    </script>
  </head>
  <body>
    <div id="timeline" style="height: 180px;"></div>
  </body>
</html>
