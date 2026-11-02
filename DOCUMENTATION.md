# Project Documentation

**Project Title:** Discover Cebu City: A Multi-Page Tourism Website Using HTML
**Student:** [Your Full Name] | BSIT First Year
**Course:** Introduction to Computing / Web Development
**Instructor:** Ms. Bethel B. Tisuela, MSCS
**Selected Category:** Category 3, Tourism and Travel Information Website

## Purpose
To promote Cebu City by giving visitors organized information on attractions, heritage, food, festivals, lodging, and transportation, while showing correct use of HTML.

## Target Audience
Local and foreign tourists, students doing research, and first-time visitors planning a trip to Cebu City.

## List of Webpages (12)
| # | File | Content |
|---|------|---------|
| 1 | index.html | Home page, hero banner, quick facts, cards |
| 2 | about.html | Overview, history (ordered list), fast facts table |
| 3 | attractions.html | Attractions cards and table, visitor tips |
| 4 | heritage.html | Churches, forts, culture |
| 5 | food.html | Food table, pasalubong list |
| 6 | festivals.html | Festival calendar table, Sinulog tips |
| 7 | accommodation.html | Lodging types table, areas to stay |
| 8 | transportation.html | Getting there and around, travel tips |
| 9 | gallery.html | Image gallery |
| 10 | contact.html | Offices table, practice form |
| 11 | sitemap.html | Page structure and links |
| 12 | references.html | Sources and about the author |

## HTML Elements Used
`<!DOCTYPE html>`, `<html lang>`, `<head>`, `<meta>`, `<title>`, `<link>`, `<body>`, `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<h1>` to `<h3>`, `<p>`, `<a>` (internal and external), `<img>` with `src` and `alt`, `<figure>` and `<figcaption>`, `<ul>`, `<ol>`, `<li>`, `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`, `<form>`, `<label>`, `<input>`, `<textarea>`, `<button>`, `<strong>`, `<br>`, `<pre>`.

## Design
CSS (styles.css) gives the site a National University-inspired look: navy blue and gold colors, a top utility bar, a sticky navigation bar with dropdown menus, a hero banner, hover effects on cards and buttons, and a responsive layout.

## Folder Structure
```
CebuCityWebsite/
  index.html, about.html, attractions.html, heritage.html, food.html,
  festivals.html, accommodation.html, transportation.html, gallery.html,
  contact.html, sitemap.html, references.html, styles.css
  images/ (10 image files)
```

## Challenges Encountered (edit to match your experience)
1. Keeping navigation identical on all 12 pages. Solved by copying the same nav block and changing only the active link.
2. Broken image paths. Solved by keeping all images in the images folder and using relative paths.
3. Table layout on small screens. Solved with CSS width and responsive rules.
4. Making the dropdown menu work without JavaScript. Solved with CSS `:hover` and `:focus-within`.

## Testing
Opened every page in a browser, clicked every link and menu item, checked that every image loads, and ran a script that checked all internal links and image paths (0 broken).

## Sources
Cebu City Government, Department of Tourism, Philippine Statistics Authority, National Museum of the Philippines. Design inspiration: nu.edu.ph. Images are original illustrations.
