# HT Van Jekyll Scaffold

Bo khung du an Jekyll nay duoc tao theo structure trong tai lieu theme-first:

- `_layouts/`: layout cho page, single, archive, auth, ecom, my-account
- `_includes/`: header, footer, sidebar, template-parts, widgets
- `_data/`: du lieu mau cho menu, page meta, products, theme tokens
- `pages/`: cac page entry co permalink ro rang
- `assets/`: SCSS, JS, image assets

## Chay local

```bash
bundle install
bundle exec jekyll serve
```

## Ghi chu

- Phan UI hien tai la scaffold sach, chua do design tu Figma.
- `pages/index.md` da map ve `/`.
- Cac layout ecom va auth da co san de lap ghep tiep theo.
- `assets/css/main.scss` la source theo huong SCSS; `assets/css/main.css` duoc commit san de Jekyll build on dinh trong moi truong Windows sandbox.
