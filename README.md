### Hi there, I'm Evan 👋

I'm a High School Senior who goes to the North Carolina School of Science and Mathematics 🏫.

**I 💗**:
  - 🌐 Web Development: 
    - Front End Languages: HTML, CSS, Javascript, React
    - Back End Languages: Django, Flask, SQL & Databases (PostgreSQL, Redis)
    - Main Interests: Websites, Convenience Web Applications
    - Soji Website: https://soji-website.herokuapp.com/ **||** https://github.com/IronicNinja/soji-website
    - Automatic Stock Scraper: https://stock-scraper-multi.herokuapp.com/ **||** https://github.com/IronicNinja/stock-scraper-multi
  - 📈 Data Science: 
    - Languages: Python, C++
    - Python Packages: Tensorflow (Neural Networks), Pandas, Scikit-learn
    - Interests: Neural Networks for Time Series Predictions, Reinforcement Learning, Intersection between CS and Economics
    - For my Data Science projects, visit my Kaggle Account: https://www.kaggle.com/ironicninja
  - 🤖 Software Development: 
    - Languages: Python, Java
    - Interests: Web Scraping Scripts, Bot Automation, Interactive GUIs
    - COVID-19 Information Web Scraper: https://github.com/IronicNinja/covid19api
    - Productivity Tracker with Clockify API: https://github.com/IronicNinja/ClockifyAPI
    - Automated Bots: https://github.com/IronicNinja/automation
    - An Among Us Maze?!?: https://github.com/IronicNinja/amongus-maze
  
**A bit more info**
- 🐍 My favorite (and most proficient) language is definitely Python: great community, excellent documentation, overall easy to work with.
- 👯 Feel free to reach out to me if you have any project you think I could help with! The best way to reach me is probably email at zhang21evan@ncssm.edu
- ⚡ In my free time, I: play ping pong, watch/play Minecraft, read books on business/entrepreneurship, relax!

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
<!--END_SECTION:waka-->
