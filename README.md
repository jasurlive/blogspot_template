# Minimal Blog Template

A simple, clean, and responsive blog template for Blogger/Blogspot.

<img width="60%" alt="image" src="https://github.com/user-attachments/assets/1320687b-9fcb-4f6d-8fa0-72c6d73e13ac" />

<img width="30%" alt="image" src="https://github.com/user-attachments/assets/12406737-d880-4c42-8def-1e5aeeee5e79" />


## Demo

Check the live demo: [jasurlive.uz](https://jasurlive.uz)

## Features

- Minimal, modern card-style layout
- Fully responsive and mobile-friendly
- Backdrop blur and gradient effects
- Easy copy-paste integration into Blogger/Blogspot
- Posts open in a reader modal: swipe down (phone) or drag the top bar down (mouse) to close, or X / Esc / Back
- 7 themes from [django-react](https://github.com/jasurlive/django-react): light, dark, linen, fjord, matte, charcoal, paper
- Sticky header and numbered pagination (1 2 3 … 10) instead of Newer/Older links

## How to Use

1. Copy the content of `sample.xml` from this repo.
2. Paste it into a new Blogger/Blogspot HTML page or edit an existing one.
3. Replace `<data:blog.title/>` with your blog title if needed.
4. Customize colors, fonts, and layout via the `<b:skin>` CSS section.
5. Publish and enjoy a minimal, responsive blog layout.

Pagination: page numbers are built from your blog feed. Posts per page follow Settings → Posts → "Max posts shown on main page". Blogger's own Newer/Older/Home buttons are always hidden; if the feed can't load, simple prev/next arrows are shown instead.

## Notes

- Theme sync when embedded in an iframe: the parent page can call `iframe.contentWindow.postMessage({ theme: "dark" }, "*")`.

- Designed to be copy-paste ready for Blogspot.
- IMPORTANT: Blogspot adds its trash xml and make it 1000 lines of code after saving (check full.xml, it has more than 1000 lines of trash code). It is okay. Save this xml somewhere and edit and paste and test according to your preferences.

## License

MIT License. Free to use and modify.
