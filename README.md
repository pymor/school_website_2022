# pyMOR School 2022 Website

## Building locally

```bash
python3 -m venv venv
source venv/bin/activate
python3 -m pip install -r requirements.txt
nikola auto --browser
```

## GitHub Pages deployment

- currently happens on every push via `.github/workflows/deploy.yml`
- live site reachable [here](https://2022.school.pymor.org)
