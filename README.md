# bhyve-website

An open-source community website for the [bhyve](https://bhyve.org) BSD hypervisor project.

## Credit

- FreeBSD and bhyve project
- Bootstrap 4 template (Start Bootstrap Agency)
- Unsplash images
- Logo by me and TheVectorLab

## Changelog

- **Added** contact form HTML so the form JavaScript works correctly
- **Fixed** PHP email header injection vulnerability in `mail/contact_me.php`
- **Removed** stale duplicate `docs/index.html` (was a maintenance burden)

## Usage

### Basic Usage

Edit the HTML and CSS files directly. Open `index.html` in your browser to preview.

### Advanced Usage

```sh
npm install
npm start
```

Opens a live-reloading preview via BrowserSync.

#### Gulp Tasks

- `gulp` — builds everything
- `gulp watch` — opens browser with live reload on changes
- `gulp css` — compiles and minifies SCSS to CSS
- `gulp js` — minifies JS files
- `gulp vendor` — copies dependencies from `node_modules` to `vendor/`

