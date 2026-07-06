# AJAY HARI KRISHNA

> This is the updated excerpt for the sections that were causing rendering issues.

## 📊 GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=BURLAGADDA-AJAY-HARI-KRISHNA-221FA04286&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&include_all_commits=true"/>

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BURLAGDA-AJAY-HARI-KRISHNA-221FA04286&layout=compact&theme=tokyonight&hide_border=true&langs_count=10"/>

<img src="https://streak-stats.demolab.com?user=BURLAGADDA-AJAY-HARI-KRISHNA-221FA04286&theme=tokyonight&hide_border=true"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=BURLAGADDA-AJAY-HARI-KRISHNA-221FA04286&theme=tokyo-night&hide_border=true&area=true"/>

<img src="https://github-profile-trophy.vercel.app/?username=BURLAGADDA-AJAY-HARI-KRISHNA-221FA04286&theme=algolia&no-frame=true&row=1&column=7"/>

</div>

---

## 🐍 Contribution Snake

> Create `.github/workflows/snake.yml` with the workflow below, then commit it. Do **not** place this YAML inside your README.

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: BURLAGADDA-AJAY-HARI-KRISHNA-221FA04286
          outputs: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

After the workflow succeeds, keep only this in your README:

```html
<div align="center">
<img src="https://raw.githubusercontent.com/BURLAGADDA-AJAY-HARI-KRISHNA-221FA04286/BURLAGADDA-AJAY-HARI-KRISHNA-221FA04286/output/github-contribution-grid-snake.svg" alt="Snake Animation"/>
</div>
```
