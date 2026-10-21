# panoskolyvakis.github.io

Personal website of Dr Panos Kolyvakis, served by GitHub Pages at <https://panoskolyvakis.github.io/>.

Plain HTML, CSS and a little JavaScript: no framework and no build step.

```
index.html            home: intro, about, projects, experience summary, writing, contact
about.html            experience & education
blog.html             writing (MathJax for maths, highlight.js for code)
404.html              not-found page
assets/css/site.css   all styles (light and dark themes follow the system setting)
assets/js/site.js     mobile menu, scroll effects, table-of-contents highlight
assets/img/           images (resized for the web) and the favicon
assets/PanosKolyvakisCV.pdf  CV (assets/WebCVPK.pdf kept as a copy for old links)
LaTeX.mp4             demo video used in the blog
```

Preview locally with `python3 -m http.server 8000` and open <http://localhost:8000>.
To change the hero photo, replace `assets/img/panos.jpg` (portrait orientation works best).
