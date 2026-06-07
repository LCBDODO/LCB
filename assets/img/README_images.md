# LCB image asset map

The active Lab of Cancer Biology pages use local images from these folders:

- `assets/img/home/` — home hero/background images
- `assets/img/gallery/` — gallery and home slider photos
- `assets/img/members/` — current member and alumni portraits
- `assets/img/professor/` — professor portrait
- `assets/img/projects/` — research and previous project figures

To replace an image without editing page code, keep the same filename and replace the file in the matching folder. The gallery frames are fixed to one size in CSS and use `object-fit: contain`, so photos should show without cutting off heads. Member portraits use square frames; 고다연 has a separate focus rule in `_includes/lcb_style.html`.
