### Hi there 👋

<!--
**IronicNinja/IronicNinja** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!--START_SECTION:waka-->
  name: Waka Readme

  on:
    schedule:
      # Runs at 12am IST
      - cron: '30 18 * * *'

  jobs:
    update-readme:
      name: Update Readme with Metrics
      runs-on: ubuntu-latest
      steps:
        - uses: IronicNinja/IronicNinja@master
          with:
            WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
            GH_TOKEN: ${{ secrets.GH_TOKEN }}
            SHOW_LINES_OF_CODE: "True"
<!--END_SECTION:waka-->
