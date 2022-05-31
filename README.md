# Visit https://github.com/lowlighter/metrics/blob/master/action.yml for full reference
name: Metrics
on:
  # Schedule updates (each hour)
  schedule: [{cron: "0 * * * *"}]
  # Lines below let you run workflow manually and on each commit
  workflow_dispatch:
  push: {branches: ["master", "main"]}
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    steps:
      - uses: lowlighter/metrics@latest
        with:
          # Your GitHub token
          # The following scopes are required:
          #  - public_access (default scope)
          #  - public_repo
          #  - repo
          # The following additional scopes may be required:
          #  - read:org      (for organization related metrics)
          #  - read:user     (for user related data)
          #  - read:packages (for some packages related data)
          #  - repo          (optional, if you want to include private repositories)
          token: ${{ secrets.METRICS_TOKEN }}

          # Options
          user: ramdaniAli
          template: classic
          base: header, activity, community, repositories, metadata
          config_timezone: Africa/Lagos
          plugin_achievements: yes
          plugin_achievements_display: compact
          plugin_achievements_secrets: yes
          plugin_achievements_threshold: C
          plugin_calendar: yes
          plugin_calendar_limit: 2
          plugin_isocalendar: yes
          plugin_isocalendar_duration: full-year
          plugin_languages: yes
          plugin_languages_analysis_timeout: 15
          plugin_languages_categories: markup, programming
          plugin_languages_colors: github
          plugin_languages_limit: 8
          plugin_languages_recent_categories: markup, programming
          plugin_languages_recent_days: 14
          plugin_languages_recent_load: 300
          plugin_languages_sections: most-used
          plugin_languages_threshold: 0%
          plugin_projects: yes
          plugin_projects_limit: 4
          plugin_skyline: yes
          plugin_skyline_compatibility: yes
          plugin_skyline_frames: 60
          plugin_skyline_quality: 0.5
          plugin_skyline_year: current-year
          plugin_stargazers: yes
          plugin_stargazers_charts_type: classic
          plugin_stars: yes
          plugin_stars_limit: 4
          plugin_topics: yes
          plugin_topics_limit: 15
          plugin_topics_mode: starred
          plugin_topics_sort: stars
          plugin_traffic: yes




![](https://github.com/ramdaniAli/ramdaniAli/blob/main/ContactMe%20email%3Dzeali.ramdani%40gmail.com%20discord%3DAL%238446%20github%3DramdaniAli%20.png)

[![github](https://img.shields.io/badge/ramdaniAli-12100E.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ramdaniAli/)![](https://komarev.com/ghpvc/?username=ramdaniAli&label=PROFILE+VIEWS&style=for-the-badge&color=brightgreen)

<div>
 
 <h1 align="center" >Hi there 👋, my name is Ali</h1> 

  <p align="center" >
  I am a web developer with expertise in front-end development and exposure to back-end development. I design and develop web applications using the latest technologies to deliver the product with quality modular code.
  </p>

 <p align="center">
  <a href="https://skillicons.dev">
     <img src="https://skillicons.dev/icons?i=react,redux,js,jest,nextjs,gatsby,webpack,materialui,bootstrap,html,css,sass,git,docker,netlify,nginx,nodejs,express,firebase,mysql,py,unreal,arduino,figma,vscode" />
   </a>
 </p>
 
</div>

&nbsp;
&nbsp;
## 📊 Github stats


<details> 
 
 <summary>💻 GitHub Profile stats</summary>
 
![GitHub stats](https://github-readme-stats.vercel.app/api?username=ramdaniAli&show_icons=true&count_private=true&theme=aura)  
 
</details> 


<details> 
 
 <summary>💻 GitHub Profile trophies</summary>
 
![trophy](https://github-profile-trophy.vercel.app/?username=ramdaniAli&theme=onestar)
</details> 


<details> 
 
 <summary>💻 GitHub Profile langs</summary>
 
 ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ramdaniAli&langs_count=50&theme=aura)
 
</details> 


<details> 
 
 <summary>💻 GitHub Profile metrics</summary>
 
![GitHub metrics](https://metrics.lecoq.io/ramdaniAli)  
 
</details> 


![Metrics](https://metrics.lecoq.io/ramdaniAli?template=classic&isocalendar=1&languages=1&topics=1&stars=1&stargazers=1&projects=1&achievements=1&traffic=1&calendar=1&skyline=1&base.indepth=false&isocalendar.duration=full-year&languages.limit=8&languages.threshold=0%25&languages.other=false&languages.colors=github&languages.sections=most-used&languages.indepth=false&languages.analysis.timeout=15&languages.categories=markup%2C%20programming&languages.recent.categories=markup%2C%20programming&languages.recent.load=300&languages.recent.days=14&topics.mode=starred&topics.sort=stars&topics.limit=15&stars.limit=4&stargazers.charts.type=classic&projects.limit=4&projects.descriptions=false&achievements.threshold=C&achievements.secrets=true&achievements.display=compact&achievements.limit=0&calendar.limit=2&skyline.year=current-year&skyline.frames=60&skyline.quality=0.5&skyline.compatibility=true&config.timezone=Africa%2FLagos)


![GitHub Activity Graph](https://activity-graph.herokuapp.com/graph?username=ramdaniAli)  



![GitHub streak stats](https://github-readme-streak-stats.herokuapp.com/?user=ramdaniAli)  

 
