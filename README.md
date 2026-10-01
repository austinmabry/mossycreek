# Mossy Creek Farmstand

Website for William & Charlotte's front-yard roasted pecan stand: **mossycreekfarmstand.com**

It's a plain HTML/CSS site with no build step. Everything the site serves is in `public/`.

## Making changes

- **Words, prices, hours, email:** edit `public/index.html`. Look for the `<!-- EDIT: ... -->` notes.
- **Colors and fonts:** edit `public/styles.css`. The colors are at the top.
- **Photos:** replace the files in `public/images/` but keep the same file names:
  - `hero-bag.jpg`: the big top photo
  - `william-charlotte.jpg`: the "Our Story" photo
  - `pecan-bowl.jpg`: the "Our Pecans" photo
  - `barn.jpg`: the "Find Us" background

Commit and push to `main` and Cloudflare will publish the change in about a minute.

## Preview locally

```
cd public && python3 -m http.server 8000
```
Then open http://localhost:8000
