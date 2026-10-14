# D<sup>3</sup> Lab website

Source for the website of the **Dynamics, Data and Design (D<sup>3</sup>) Lab**, Department of Mechanical Engineering, Indian Institute of Science (IISc), Bengaluru.

Live site: <https://d3lab-iisc.github.io/>

Built with [Hugo](https://gohugo.io/) (extended) and the [Hugo Blox](https://hugoblox.com/) Bootstrap theme, deployed to GitHub Pages by [.github/workflows/publish.yaml](.github/workflows/publish.yaml) on every push to `main`.

## Editing the site

| What | Where |
| :--- | :--- |
| Homepage | `content/_index.md` |
| News posts | `content/post/<yy-mm-dd-name>/index.md` (+ `featured.jpg`) |
| Research | `content/research/_index.md` |
| Lab equipment | `content/equipments/_index.md` |
| People | `content/authors/<username>/_index.md` (+ `avatar.jpg`), former members in `content/people/index.md` |
| Publications | add BibTeX to `publications.bib`, or a folder in `content/publication/` |
| Courses | `content/courses/<code>/index.md` |
| Contact | `content/contact/index.md` |
| Menu | `config/_default/menus.yaml` |
| Site settings | `config/_default/params.yaml`, `config/_default/hugo.yaml` |
| PDFs / downloads | `static/uploads/` (linked as `uploads/<file>.pdf`) |

Pushing a change to `publications.bib` runs [import-publications.yml](.github/workflows/import-publications.yml), which opens a pull request with the generated publication pages.

## Preview locally

Install Hugo **extended** (same version as `WC_HUGO_VERSION` in `publish.yaml`) and Go, then run:

```sh
hugo server
```

and open <http://localhost:1313/>.
