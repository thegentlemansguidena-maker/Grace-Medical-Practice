# Grace Medical Practice

Website for Grace Medical Practice, a general medical practice in Windhoek, Namibia, led by Dr. Admire Nyamutamba.

A single static page with no build step. Open `index.html` in a browser, or host the folder on any static host (GitHub Pages, Netlify, and so on).

## Files

- `index.html`: the page, including its styles and a little script
- `scrollcraft.js`, `scrollcraft.css`: the scroll engine (from the scroll-craft skill, MIT)
- `assets/`: images (WebP)
- `grace-medical.vcf`: the contact card behind "Save to contacts"
- `BRIEF.md`: the original design brief (since revised: blue and white palette, breathing section removed, booking added)

## Booking

The "Book an appointment" form has no server behind it. When someone submits it, their email app opens with a ready-written request to gracemedical@hotmail.com, and the practice calls them back to confirm. Nothing is stored on the website.

To receive requests without the visitor's email app (for example through Formspree, Netlify Forms, or a booking system), replace the submit handler in `index.html`.

## Confirm before launch

- **Care list.** The four cards describe general GP work. Confirm the practice offers each of them.
- **Doctor photo.** The welcome section still shows a stethoscope still-life. To use a photo of Dr. Nyamutamba, save it as `assets/doctor.webp` (portrait, about 1400 x 1870) and change the `src` and `alt` of the image in the welcome section.
- **Other photos.** The landscape and aloe images are AI-generated and illustrative, not the real premises.
- **Details not on the page.** Opening hours, medical aid, and qualifications were not supplied. Add them if the practice wants them shown.
- **Booking email.** Make sure someone checks gracemedical@hotmail.com regularly, since booking requests arrive there.
- **Contact details.** Check the phone numbers, email, and address against current records.
