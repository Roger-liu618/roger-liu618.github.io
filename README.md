# Wild Note

Personal site of **Roger Liu** — field notes, essays and research on wildlife and conservation.

Live site: https://roger-liu618.github.io/

Contact: liuyuxiu0618@qq.com

## Structure

```
index.html          home page (hero slideshow, about, themes, fieldwork, essays)
archive.html        full list of essays
essays/             individual essay pages (bilingual EN / 中文)
images/             hero photographs (AI generated, disclosed in the footer)
```

## Editing

Everything is plain static HTML — no build step.

- Bilingual text uses paired attributes: `data-en="..." data-cn="..."`
- Colours and fonts are CSS variables at the top of the `<style>` block in `index.html`
- `.nojekyll` disables Jekyll processing; keep it in place

## Deploying

Push to `main`. GitHub Pages publishes the repository root automatically.
