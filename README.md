# 2022 MaRDI Workshop Website


## Building locally

```bash
python3 -m venv venv
source venv/bin/activate
python3 -m pip install -r requirements.txt
nikola auto --browser
```


## Github Pages deployment

- currently happens on every push via .github/workflows/deploy.yml
- Live site reachable at https://2022.school.pymor.org
