# AZIL Healthcare

## Run locally

Use Node.js 22.12 or newer. Install the dependencies and start the development
server:

```sh
npm install --legacy-peer-deps
npm run dev
```

Vite prints the local address in the terminal. Open it in a browser to view the
site.

## Add the original images

Place the original JPGs in `public/images/` using the filenames listed in
`public/images/UPLOAD_IMAGES_HERE.txt`. The site loads images from this local
folder.

## Production build

```sh
npm run build
npm run preview
```
