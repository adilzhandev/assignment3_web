# Discover Kazakhstan — Travel Website

**Author:** Adilzhan Kuandykov  
**Group:** SE-2526

**Topic:** A travel agency website that presents tours across Kazakhstan (canyons, mountain lakes, Silk Road cities).

**Live demo:** https://adilzhandev.github.io/assignment3/

## Pages
| Page | File | What it shows |
|------|------|---------------|
| Home | `index.html` | Hero banner, "Why us" features (Flexbox), popular destinations (Bootstrap grid cards) |
| About | `about.html` | Our story, values (list), trip steps (ordered list), team with photos |
| Tours | `tours.html` | Tour cards and a **pricing/schedule table** |
| Gallery | `gallery.html` | Photo gallery built with **CSS Grid** |
| Contact | `contact.html` | Booking page: 3 steps, **booking form**, contacts and a map |

## Features implemented
- **Semantic HTML5:** `header`, `nav`, `main`, `section`, `article`, `figure`, `figcaption`, `aside`, `footer`
- **HTML elements:** headings, paragraphs, ordered/unordered lists, links, images, table, form, `div` and `span`
- **CSS:** element, class, ID, descendant and `:hover` selectors; one color theme (blue, yellow, dark); Google Font *Poppins*
- **Flexbox:** hero text in the center, "Why us" boxes in one row
- **Grid:** gallery with `grid-template-columns: repeat(3, 1fr)`
- **Positioning:** `fixed` navbar and back-to-top button; `relative` + `absolute` for the hero text, card labels and gallery captions
- **Media queries:** 992px (tablet) and 576px (mobile)
- **Bootstrap 5:** responsive navbar, grid (`container`, `row`, `col-md-6`, `col-lg-4`), cards, table, form controls, utility classes (`my-5`, `mb-4`, `text-center`, `btn`, `w-100`, ...)

## Project structure
```
assignment3/
├── index.html
├── about.html
├── tours.html
├── gallery.html
├── contact.html
├── css/
│   └── style.css
├── images/        # photos of Kazakhstan
│   └── team/      # team photos
└── README.md
```

## How to run
Open `index.html` in a browser. Bootstrap is loaded from a CDN, so an internet connection is needed.

## Deployment (GitHub Pages)
1. Create a new public repository on GitHub and upload all files.
2. Go to **Settings → Pages**, choose branch `main` and folder `/ (root)`, then Save.
3. After a minute the site is available at `https://<username>.github.io/<repo-name>/`.

## Photo credits
All photos are from [Wikimedia Commons](https://commons.wikimedia.org/) and are used under their free licenses.

| File | Author | License |
|------|--------|---------|
| [`images/hero.jpg`](https://commons.wikimedia.org/wiki/File:Edrey_Mountains,_Karaganda_region,_Kazakhstan._May_2025_01.jpg) | Astrobond | CC BY-SA 4.0 |
| [`images/charyn.jpg`](https://commons.wikimedia.org/wiki/File:Charyn_Canyon,_Kazakhstan_01.jpg) | Bgag | CC0 |
| [`images/charyn-2.jpg`](https://commons.wikimedia.org/wiki/File:Charyn_Canyon,_Kazakhstan_03.jpg) | Bgag | CC0 |
| [`images/kolsai.jpg`](https://commons.wikimedia.org/wiki/File:Kolsai_lake.jpg) | Katariyakartikey | CC0 |
| [`images/kolsai-2.jpg`](https://commons.wikimedia.org/wiki/File:Kolsai_lakes.Mountains.jpg) | Dimash Kenesbek | CC BY-SA 4.0 |
| [`images/kaindy.jpg`](https://commons.wikimedia.org/wiki/File:Kaindy_lake.jpg) | Katariyakartikey | CC0 |
| [`images/burabay.jpg`](https://commons.wikimedia.org/wiki/File:%D0%9E%D0%B7%D0%B5%D1%80%D0%BE_%D0%91%D0%BE%D1%80%D0%BE%D0%B2%D0%BE%D0%B5,_%D0%91%D1%83%D1%80%D0%B0%D0%B1%D0%B0%D0%B9.jpg) | Alter-Ego9312 | CC BY-SA 4.0 |
| [`images/almaty.jpg`](https://commons.wikimedia.org/wiki/File:Sunset_over_the_Almaty_seen_from_Kok_Tobe_mountain,_pic_1.jpg) | Vmenkov | CC BY-SA 3.0 |
| [`images/big-almaty-lake.jpg`](https://commons.wikimedia.org/wiki/File:Big_Almaty_Lake_(Bolshaya_Almatinka)_in_June.jpg) | Ds02006 | Public domain |
| [`images/baiterek.jpg`](https://commons.wikimedia.org/wiki/File:Baiterek_August.jpg) | Quarot | CC0 |
| [`images/turkistan.jpg`](https://commons.wikimedia.org/wiki/File:Mausoleum_of_Khoja_Ahmed_Yasavi_in_Turkestan,_Kazakhstan.jpg) | Petar Milošević | CC BY-SA 4.0 |
| [`images/yurt.jpg`](https://commons.wikimedia.org/wiki/File:Yurt_at_the_Foot_of_the_Cliffs,_Aktobe_Region,_Kazakhstan.jpg) | Danatleg122 | CC BY 4.0 |
| [`images/altyn-emel.jpg`](https://commons.wikimedia.org/wiki/File:210723_Altyn_Emel_Singing_Dune_top.jpg) | Jjm2311 | CC BY-SA 4.0 |
| [`images/medeu.jpg`](https://commons.wikimedia.org/wiki/File:Medeobanen1.jpg) | Kefi | CC0 |

Team photos (`images/team/`) are stock portraits from [randomuser.me](https://randomuser.me/). The team members are fictional.
