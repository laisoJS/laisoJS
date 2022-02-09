<div id="header" align="center">
    <img src="https://media.giphy.com/media/tCnP4Xf98BWxZNdCmW/giphy.gif" alt="loic500" style="border-radius: 50%" width="150"/>
    <div id="badge">
        <a href="https://instagram.com/aloisleroy">
            <img src="https://img.shields.io/badge/Instagram-black?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram Badge">
        </a>
        <a href="https://twitter.com/loic500">
            <img src="https://img.shields.io/badge/Twitter-black?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge">
        </a>
        <a href="https://dev.to/loic500">
            <img src="https://img.shields.io/badge/dev.to-black?style=for-the-badge&logo=dev.to&logoColor=white" alt="Dev.to Badge">
        </a>
    </div>
    <img src="https://komarev.com/ghpvc/?username=loic500&label=Profile%20views&color=000000&style=flat" alt="loic500" width="120"/> 
</div>

---

### :hammer_and_wrench: Languages and Tools :

---

<!--START_SECTION:waka-->
name: Waka Readme
on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
          SHOW_OS: false
          SHOW_PROJECTS: false
          SHOW_TIMEZONE: false
          SHOW_EDITORS: false
          SHOW_LANGUAGE_PER_REPO: false
          SHOW_LOC_CHART: false
<!--END_SECTION:waka-->
