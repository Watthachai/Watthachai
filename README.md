# Hi, I'm Watthachai <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Hi.gif" width="29px">

<table>
<tr>
  <td valign="center">
    🎓 I am currently pursuing my **Bachelor's in Computer Engineering**.
    🌱 I am currently learning **Java** and also interested in **AI & Pythom**.
    🎯 My Goal is to Contribute to as many **open source project** as possible.
    ✨ I love to create different types of **contents**.
<td >
    <a href="https://app.daily.dev/itswatthachai"><img src="https://api.daily.dev/devcards/af2270eb17304233863d27759e28400a.png?r=ayb" width="400" alt="Watthachai Taechalue's Dev Card"/></a>
  </td>

</tr>
</table>

![GitHub Activity Graph](https://activity-graph.herokuapp.com/graph?username=watthachai&theme=dracula&hide_border=true)


## Stats📈
<p align="center">
<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs?username=watthachai&show_icons=true&theme=dracula&title_color=ff8000&text_color=ffffff&bg_color=6a6a6a&locale=en&layout=compact&hide_border=true" alt="watthachai" /> 
<img width="48%" src="https://github-readme-stats.vercel.app/api?username=watthachai&show_icons=true&theme=dracula&title_color=ff8000&text_color=ffffff&bg_color=6a6a6a&locale=en&hide_border=true" alt="watthachai" />
<img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=watthachai&theme=highcontrast&hide_border=true" alt="watthachai" />
</p>

name: Update README

on:
  schedule:
    - cron: '*/30 * * * *'
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    name: Update this repo's README with recent activity

    steps:
      - uses: actions/checkout@v2
      - uses: watthachai/github-activity-readme@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
     
<!--START_SECTION:activity-->
<!--END_SECTION:activity-->
