<!-- [![Zongnan Bao's github stats](https://github-readme-stats.vercel.app/api?username=bznick98&hide=issues,prs&show_icons=true&theme=gruvbox)](https://github.com/bznick98)
[![Zongnan's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=nick19981122)](https://github.com/anuraghazra/github-readme-stats)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=bznick98&hide=html,jupyter%20notebook,Systemverilog,Verilog&layout=compact&langs_count=5&exclude_repo=malu_intern)](https://github.com/anuraghazra/github-readme-stats) -->

<h4 align="center"><samp> Hi there 👋  </samp></h4>

<p align="center">
  
  <a href="https://github.com/bznick98">
    <img align="center" src="https://github-readme-stats.vercel.app/api?username=bznick98&hide=issues,prs&show_icons=true&theme=gruvbox" />
  </a>
<!--   <a href="https://github.com/bznick98">
    <img align="center" src="https://github-readme-stats.vercel.app/api/wakatime?username=nick19981122" />
  </a> -->
 
</p>

<style>
    #stat{
        font-family:    'Trebuchet MS', sans-serif;
        font-size:      20px;
        font-weight:    bold;
    }
    #views, #downloads{
        color: gold;
        font-family:    'Courier New', monospace;
        font-size:      15px;
        font-weight:    bold;
    }
    #vtxt, #dtxt{
        font-family:    'Courier New', monospace;
        font-size:      15px;
        font-weight:    bold;
    }
 
</style>
<center>
<div id="stat"> Unsplash Stats </div>
<span id="views"></span> <span id="vtxt"> views</span> <br>
<span id="downloads"></span> <span id="dtxt"> downloads</span>
</center>

<script>
async function loadStats() {
  const url = "https://api.unsplash.com/users/nick19981122/statistics/?client_id=6t0qRfV_gaM3em6bzhVAZAg1PNl1vxOCTaqGWorNU5A"
  const response = await fetch(url);
  const stats = await response.json();
  // let my_stats = JSON.parse(stats);
  console.log(stats); 
  console.log("Displaying Views and Downloads");
  console.log(stats.views.total);
  console.log(stats.downloads.total);
  // write to html
  document.getElementById('views').innerHTML = stats.views.total;
  document.getElementById('downloads').innerHTML = stats.downloads.total;
};
loadStats();
</script>

![](https://visitor-badge.glitch.me/badge?page_id=bznick98.bznick98)

