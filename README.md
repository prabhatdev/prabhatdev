<!--START_SECTION:waka-->
**I'm an early 🐤** 

```text
🌞 Morning    98 commits     ██████░░░░░░░░░░░░░░░░░░░   26.42% 
🌆 Daytime    90 commits     ██████░░░░░░░░░░░░░░░░░░░   24.26% 
🌃 Evening    165 commits    ███████████░░░░░░░░░░░░░░   44.47% 
🌙 Night      18 commits     █░░░░░░░░░░░░░░░░░░░░░░░░   4.85%

```


**I mostly code in Kotlin** 

```text
Kotlin       13 repos       ██████░░░░░░░░░░░░░░░░░░░   27.08% 
Dart         10 repos       █████░░░░░░░░░░░░░░░░░░░░   20.83% 
Python       8 repos        ████░░░░░░░░░░░░░░░░░░░░░   16.67% 
Java         8 repos        ████░░░░░░░░░░░░░░░░░░░░░   16.67% 
CSS          2 repos        █░░░░░░░░░░░░░░░░░░░░░░░░   4.17%

```


📊 **This week I spent my time on** 

```text
⌚︎ Timezone: Asia/Calcutta

💬 Languages: 
Python                   11 mins             ████████████████████████░   98.01% 
Text                     0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.99%

🔥 Editors: 
Sublime Text             11 mins             █████████████████████████   100.0%

🐱‍💻 Projects: 
waka-readme-stats        11 mins             █████████████████████████   100.0%

💻 Operating Systems: 
Linux                    11 mins             █████████████████████████   100.0%

```


<!--END_SECTION:waka-->

```html
<html>
<head>
  <style>
    .error {
        color: red;
    }
  </style>
  <script type="text/javascript" src="https://cdn.jsdelivr.net/npm//vega@5"></script>
  <script type="text/javascript" src="https://cdn.jsdelivr.net/npm//vega-lite@4.8.1"></script>
  <script type="text/javascript" src="https://cdn.jsdelivr.net/npm//vega-embed@6"></script>
</head>
<body>
  <div id="vis"></div>
  <script>
    (function(vegaEmbed) {
      var spec = {"config": {"view": {"continuousWidth": 400, "continuousHeight": 300, "strokeOpacity": 0}}, "data": {"name": "data-975da7271c06182142e556253ea10973"}, "mark": "bar", "encoding": {"color": {"type": "nominal", "field": "DF", "scale": {"range": ["#96ceb4", "#ffcc5c", "#ff6f69"]}}, "column": {"type": "nominal", "field": "c1", "title": null}, "x": {"type": "nominal", "field": "c2", "title": null}, "y": {"type": "quantitative", "aggregate": "sum", "axis": {"grid": false, "title": null}, "field": "values"}}, "$schema": "https://vega.github.io/schema/vega-lite/v4.8.1.json", "datasets": {"data-975da7271c06182142e556253ea10973": [{"c1": "A", "c2": "I", "values": 7.44286320527547, "DF": "DF1"}, {"c1": "A", "c2": "J", "values": 3.9411733729617424, "DF": "DF1"}, {"c1": "A", "c2": "K", "values": 2.8628371613949986, "DF": "DF1"}, {"c1": "B", "c2": "I", "values": 0.7148304319704146, "DF": "DF1"}, {"c1": "B", "c2": "J", "values": 5.711532833190397, "DF": "DF1"}, {"c1": "B", "c2": "K", "values": 2.8581135966485505, "DF": "DF1"}, {"c1": "C", "c2": "I", "values": 5.918387437281201, "DF": "DF1"}, {"c1": "C", "c2": "J", "values": 2.0586471273321982, "DF": "DF1"}, {"c1": "C", "c2": "K", "values": 0.624151829373365, "DF": "DF1"}, {"c1": "D", "c2": "I", "values": 8.676758633985477, "DF": "DF1"}, {"c1": "D", "c2": "J", "values": 6.987859481403499, "DF": "DF1"}, {"c1": "D", "c2": "K", "values": 5.0790112688260916, "DF": "DF1"}, {"c1": "A", "c2": "I", "values": 5.865148288734151, "DF": "DF2"}, {"c1": "A", "c2": "J", "values": 0.3993150400058243, "DF": "DF2"}, {"c1": "A", "c2": "K", "values": 2.2760884783768534, "DF": "DF2"}, {"c1": "B", "c2": "I", "values": 3.8970674691725526, "DF": "DF2"}, {"c1": "B", "c2": "J", "values": 9.540048526903522, "DF": "DF2"}, {"c1": "B", "c2": "K", "values": 9.9251843256174, "DF": "DF2"}, {"c1": "C", "c2": "I", "values": 2.3616220550445908, "DF": "DF2"}, {"c1": "C", "c2": "J", "values": 8.57082597044929, "DF": "DF2"}, {"c1": "C", "c2": "K", "values": 2.1042798262552753, "DF": "DF2"}, {"c1": "D", "c2": "I", "values": 8.95891638686839, "DF": "DF2"}, {"c1": "D", "c2": "J", "values": 5.31949134216246, "DF": "DF2"}, {"c1": "D", "c2": "K", "values": 4.1456782212439975, "DF": "DF2"}, {"c1": "A", "c2": "I", "values": 1.8772471074247843, "DF": "DF3"}, {"c1": "A", "c2": "J", "values": 1.9670407233332265, "DF": "DF3"}, {"c1": "A", "c2": "K", "values": 5.374572712435946, "DF": "DF3"}, {"c1": "B", "c2": "I", "values": 6.100242359561269, "DF": "DF3"}, {"c1": "B", "c2": "J", "values": 6.7039865118639055, "DF": "DF3"}, {"c1": "B", "c2": "K", "values": 3.13042134690219, "DF": "DF3"}, {"c1": "C", "c2": "I", "values": 2.712715498057542, "DF": "DF3"}, {"c1": "C", "c2": "J", "values": 7.071299070765281, "DF": "DF3"}, {"c1": "C", "c2": "K", "values": 4.173433055452289, "DF": "DF3"}, {"c1": "D", "c2": "I", "values": 7.613548089949994, "DF": "DF3"}, {"c1": "D", "c2": "J", "values": 8.557095456530817, "DF": "DF3"}, {"c1": "D", "c2": "K", "values": 4.382974217690071, "DF": "DF3"}]}};
      var embedOpt = {"mode": "vega-lite"};

      function showError(el, error){
          el.innerHTML = ('<div class="error" style="color:red;">'
                          + '<p>JavaScript Error: ' + error.message + '</p>'
                          + "<p>This usually means there's a typo in your chart specification. "
                          + "See the javascript console for the full traceback.</p>"
                          + '</div>');
          throw error;
      }
      const el = document.getElementById('vis');
      vegaEmbed("#vis", spec, embedOpt)
        .catch(error => showError(el, error));
    })(vegaEmbed);

  </script>
</body>
</html>

```
