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


name: Work Stats Readme

on:
  workflow_dispatch:
  schedule:
    # Runs every 2 hours
    - cron: "0 */2 * * *"

jobs:
  update-readme:
    name: Update this repo's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          
<!--END_SECTION:waka-->
