# Bradley Emerson website and image upload application

Both applications are included in this folder and run together.

## Start locally

Open a terminal in this folder and run:

```powershell
node build.mjs
node preview.mjs
```

Node.js is required; no package installation is needed.

- Website: http://127.0.0.1:8780/
- Image upload application: http://127.0.0.1:8780/studio

Keep the terminal open while using the local applications. Local uploads are saved in .local-data and appear only in the local website. Use the live gallery studio to update the published website.

## Published applications

- Website: https://beyond-the-finish-line-bradley.gro4celk.chatgpt.site/
- Gallery studio: https://beyond-the-finish-line-bradley.gro4celk.chatgpt.site/studio

The live studio requires the configured owner account. Its uploaded content lives in the hosted storage; this folder contains the complete application code, bundled images and build output, not an export of hosted uploads.

## Files

- public/index.html: website source
- public/assets: photographs, book covers, logos, video thumbnails and fonts
- server/studio.html: image upload application page
- public/studio.js and public/studio.css: uploader behavior and styling
- server/worker.mjs: gallery, upload authorization, storage and email backend
- dist: built website and server
- README.md: full setup, gallery management and email configuration instructions

The latest footer includes Powered by ICORENIC PVT LTD. Header, hero, page sections and footer share consistent side margins.

The contact form currently prepares an email draft. Direct email delivery requires the provider settings described in README.md.
