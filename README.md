# BLOUNCER MATH ACADEMY

Standalone, installable web app for a private mathematics tutoring workflow.


## Certificate Center (new)
- Upload your own certificate artwork as images (PNG/JPG/WebP) or PDF.
- Add a title, award/category, optional student association, and encouragement message.
- Browse certificates in a gallery; image previews are loaded from IndexedDB.
- Preview and download uploads; delete certificates from the gallery.
- Uploaded files are stored in IndexedDB on the current browser/device; certificate metadata is stored locally.

**Sharing limitation:** uploaded certificates are local to the browser/device. To publish them so students on other phones can see them on a shared website, cloud storage and a public/student-facing gallery with access controls must be added.

## Open locally
Extract the ZIP and open `index.html` in a browser. Some browser capabilities (PWA installation and IndexedDB behavior) are more reliable when hosted over HTTPS.

## Deploy
Upload the app folder contents to static hosting such as GitHub Pages, Cloudflare Pages, or Vercel.
