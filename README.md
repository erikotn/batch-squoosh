BatchSquoosh ⚡

BatchSquoosh is a secure, client-side batch image optimizer. It allows you to shrink multiple images at once directly in your browser without uploading them to any server.

Live Demo (Replace with your actual link after publishing)

Features

Batch Processing: Drag and drop 1 or 50 images at once.

Privacy First: 100% Client-side processing using HTML5 Canvas. No data leaves your device.

Universal Settings: Set output format (JPEG, PNG, WebP), quality, and max-width globally.

Smart Stats: See exact savings per file and total bandwidth saved.

Zip Download: Download all optimized images in a single ZIP archive.

How it Works

This application is built as a Single File Component using:

React 18 (via CDN)

Tailwind CSS (for styling)

JSZip & FileSaver (for bundling downloads)

The compression logic utilizes the browser's native <canvas> API to redraw images at target dimensions and quality settings, converting them to Blobs for download.

Installation / Usage

No installation is required.

Download index.html.

Open it in any modern web browser.

License

MIT
