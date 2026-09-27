# R4 Systems website: plain English guide

## See the site on your computer

Open a terminal in this folder and run:

    npm run dev

Then open the address it prints in your browser.

## Add your photo

Put a square photo in the `public` folder and name it `portrait.jpg`.
Then tell me, and I will switch the R4 square over to your photo.

## Add your automation screenshots

Put the image files in the `public/work` folder.
Name each file with the project it belongs to, then a dash, then a number:

- `adm-1.png`, `adm-2.png` for ADM Home Services
- `acs-reporting-1.png` for the Alita weekly report build
- `acs-ads-1.png` for the Alita Google Ads build
- `ppia-1.png` for Pacific Premier Insurance
- `abakada-1.png` for ABAKADA

They appear automatically under the matching project, and clicking one opens it full size.

## Replace your CV

Overwrite `public/Renz-Rodney-Ramido-CV.pdf` with the new file. Keep the same name.

## Put it online, free

1. Create a free GitHub account and upload this folder to a new repository.
2. Go to Cloudflare Pages, connect that repository.
3. Build command: `npm run build`. Output folder: `dist`.
4. It gives you a free web address ending in `.pages.dev`.

## The contact form

It has no server behind it yet. When someone hits Submit, their email app opens with
the message already written, addressed to you. When you want real form submissions
saved somewhere, tell me and I will connect it.
