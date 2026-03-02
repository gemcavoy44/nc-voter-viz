# NC Voter Visualization

Precinct-level early voting turnout maps for North Carolina elections.

## Setup — GitHub Pages (5 minutes)

### 1. Create the repo

```bash
mkdir nc-voter-viz
cd nc-voter-viz
mkdir images
```

### 2. Add your files

Copy into the repo:
- `index.html` (the website)
- `images/Orange_early_turnout_20260303.png` (your map)

Your folder should look like:
```
nc-voter-viz/
├── index.html
├── images/
│   └── Orange_early_turnout_20260303.png
└── README.md
```

### 3. Push to GitHub

```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/nc-voter-viz.git
git push -u origin main
```

### 4. Enable GitHub Pages

1. Go to your repo on GitHub
2. **Settings** → **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Branch: **main**, folder: **/ (root)**
5. Click **Save**

Your site will be live in ~1 minute at:

```
https://YOUR_USERNAME.github.io/nc-voter-viz/
```

## Adding more maps

1. Save new map PNGs into `images/`
2. Duplicate the `<article>` block in `index.html`
3. Update the heading, text, and `<img src="...">`
4. Commit and push — GitHub Pages updates automatically

## Data Sources

- [NCSBE Absentee & Provisional Data](https://www.ncsbe.gov/results-data/absentee-and-provisional-data)
- [NCSBE Voter Registration Data](https://www.ncsbe.gov/results-data/voter-registration-data)
- [NCSBE Precinct Maps](https://dl.ncsbe.gov/?prefix=PrecinctMaps/)
