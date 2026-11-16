# أوراق | AWRAQ

**حكايات على شط المتوسط · Stories by the Mediterranean**

AWRAQ is a bilingual static bookstore concept inspired by Alexandria. Books remain the focus; local photographs of the Bibliotheca Alexandrina, Corniche, and Qaitbay Citadel connect the shelves to the city. The ancient Library, Pharos lighthouse, and Mediterranean are used as historical and editorial motifs. AWRAQ is an independent academic concept and is not affiliated with the Bibliotheca Alexandrina.

## Preview on macOS

**Quick preview:** in Finder, open this folder and double-click `index.html` (or right-click and choose a browser). No build step, npm install, or backend is required. Google Fonts are optional; system fallbacks are defined.

**Local HTTP preview:** open Terminal, run `cd "/Users/dinaaljabber/Documents/ChatGPT/awraq-alexandria"`, then `python3 -m http.server 8000`. Visit [http://localhost:8000](http://localhost:8000) and stop the server with Control-C.

## Features

- Vanilla HTML, CSS, and JavaScript; responsive single-page layout.
- English and Arabic, including `lang` and `dir`, persisted independently from the theme.
- Light/dark themes with saved preference and system preference on first visit.
- Dynamic book catalog, live search, combined category filters, visible result count, and empty state.
- Keyboard-accessible book detail modal with synopsis, editorial recommendation, source links, price, and add-to-bag action.
- Deterministic “choose a book” feature cycles through matching catalog entries; it is not AI.
- Persistent cart with quantity controls, removal, subtotal, accessible drawer, and demo-only checkout notice.
- Local newsletter validation and a demo success message. No email is sent or saved.
- Reduced-motion support, scroll reveals, and original AWRAQ alternative covers with edition-specific retailer cover links.

## Book data, sources, and prices

Product and price details below were checked on **16 November 2026**. Store prices and availability can change. The displayed amounts are source-listed EGP prices for an academic demonstration; this website cannot process orders. An English title for an Arabic-edition product may be a clear AWRAQ rendering, not a claim that the cited edition is published in English. See each source page for the listed edition/ISBN, synopsis, and stock status. The in-site synopsis text is an original, spoiler-light paraphrase of the source description.

| Book shown | Author | EGP | Product and price source |
| --- | --- | ---: | --- |
| Palace Walk / بين القصرين | Naguib Mahfouz | 450 | [Diwan product listing](https://diwanegypt.com/product/%D8%A8%D9%8A%D9%86-%D8%A7%D9%84%D9%82%D8%B5%D8%B1%D9%8A%D9%86/) |
| Miramar / ميرامار | Naguib Mahfouz | 300 | [Diwan product listing](https://diwanegypt.com/product/%D9%85%D9%8A%D8%B1%D8%A7%D9%85%D8%A7%D8%B1/) |
| The Sin / الحرام | Yusuf Idris | 63 | [Shorouk Bookstores listing](https://www.shoroukbookstores.com/books/view.aspx?id=eb6cce75-0b97-47fb-8b7e-a8baa38f6fba) · reduced from EGP 70; shown out of stock when checked |
| The Blue Elephant / الفيل الأزرق | Ahmed Mourad | 170 | [Diwan product listing](https://diwanegypt.com/product/%D8%A7%D9%84%D9%81%D9%8A%D9%84-%D8%A7%D9%84%D8%A7%D8%B2%D8%B1%D9%82/) |
| The Granada Trilogy / ثلاثية غرناطة | Radwa Ashour | 475 | [Diwan product listing](https://diwanegypt.com/product/%D8%AB%D9%84%D8%A7%D8%AB%D9%8A%D8%A9-%D8%BA%D8%B1%D9%86%D8%A7%D8%B7%D8%A9/) |
| The Thief and the Dogs / اللص والكلاب | Naguib Mahfouz | 185 | [Diwan product listing](https://diwanegypt.com/product/%D8%A7%D9%84%D9%84%D8%B5-%D9%88%D8%A7%D9%84%D9%83%D9%84%D8%A7%D8%A8-2/) |
| Adrift on the Nile / ثرثرة فوق النيل | Naguib Mahfouz | 230 | [Diwan product listing](https://diwanegypt.com/product/%D8%AB%D8%B1%D8%AB%D8%B1%D8%A9-%D9%81%D9%88%D9%82-%D8%A7%D9%84%D9%86%D9%8A%D9%84-2/) |
| Morning and Evening Talk / حديث الصباح والمساء | Naguib Mahfouz | 230 | [Diwan product listing](https://diwanegypt.com/product/%D8%AD%D8%AF%D9%8A%D8%AB-%D8%A7%D9%84%D8%B5%D8%A8%D8%A7%D8%AD-%D9%88-%D8%A7%D9%84%D9%85%D8%B3%D8%A7%D8%A1/) · English is a translated title |
| Atomic Habits | James Clear | 1,565 | [Diwan product listing](https://diwanegypt.com/product/atomic-habits/) · English edition; shown out of stock when checked |
| Step Outside the Script, Again / الخروج عن النص من جديد | Mohamed Taha | 240 | [Diwan product listing](https://diwanegypt.com/product/%D8%A7%D9%84%D8%AE%D8%B1%D9%88%D8%AC-%D8%B9%D9%86-%D8%A7%D9%84%D9%86%D8%B5-%D9%85%D9%86-%D8%AC%D8%AF%D9%8A%D8%AF/) · English is a translated title |
| Fizo in the Wardrobe / فيزو فى الدولاب | Walid Taher | 48 | [Diwan product listing](https://diwanegypt.com/product/%D9%81%D9%8A%D8%B2%D9%88-%D9%81%D9%89-%D8%A7%D9%84%D8%AF%D9%88%D9%84%D8%A7%D8%A8/) · English is a translated title |
| Mimi the Duck’s Story / حكاية البطة ميمي | Amina Mujahid | 250 | [Diwan product listing](https://diwanegypt.com/product/%D8%AD%D9%83%D8%A7%D9%8A%D8%A9-%D8%A7%D9%84%D8%A8%D8%B7%D9%87-%D9%85%D9%8A%D9%85%D9%8A/) · English is a translated title |
| The Very Hungry Caterpillar / الدودة الشديدة الجوع | Eric Carle | 230 | [Diwan product listing](https://diwanegypt.com/product/%D8%A7%D9%84%D8%AF%D9%88%D8%AF%D8%A9-%D8%A7%D9%84%D8%B4%D8%AF%D9%8A%D8%AF%D8%A9-%D8%A7%D9%84%D8%AC%D9%88%D8%B9/) · Arabic-language edition |

Publisher or ISBN details are exposed on the linked product pages. Book-cover copyright does not follow automatically from a bookstore listing. AWRAQ therefore uses **original typographic artwork**, clearly identified on each cover and detail panel as not being the publisher’s cover.

## Book-cover research, edition matches, and reuse status

The 13 displayed jackets remain the clearly labeled original AWRAQ typographic alternatives. I matched each item to the retailer listing for the catalog ISBN below; those listings display the corresponding edition cover so visitors can inspect it there. **0 of 13 authentic cover files are included locally.** The Diwan and Shorouk product pages expose cover images but do not grant an image license in the listing. I did not copy or hotlink those images. The listed cover credit is therefore the publisher/cover artist as identified on the physical jacket; the retailer metadata does not provide a distinct artist credit for reproduction. No license or direct permission was established for these cover images. For the Penguin Random House edition, the publisher directs image/cover reproduction requests through its [permissions portal](https://permissions.penguinrandomhouse.com/faqs.php). Academic/non-commercial intent alone was not treated as permission.

| Catalog book | Matched listing edition | Listing to view the authentic jacket | Reuse status and credit |
| --- | --- | --- | --- |
| Palace Walk / بين القصرين · Naguib Mahfouz | Diwan Arabic edition · ISBN 9789778616224 | [Diwan listing](https://diwanegypt.com/product/%D8%A8%D9%8A%D9%86-%D8%A7%D9%84%D9%82%D8%B5%D8%B1%D9%8A%D9%86/) | Not licensed for reuse; not copied. Cover credit remains with publisher/cover artist as printed on jacket. |
| Miramar / ميرامار · Naguib Mahfouz | Diwan Arabic edition · ISBN 9789778639728 | [Diwan listing](https://diwanegypt.com/product/%D9%85%D9%8A%D8%B1%D8%A7%D9%85%D8%A7%D8%B1/) | Not licensed for reuse; not copied. Cover credit remains with publisher/cover artist as printed on jacket. |
| The Sin / الحرام · Yusuf Idris | Nahdet Misr, 2018 · ISBN 6221133337496 | [Shorouk Bookstores listing](https://www.shoroukbookstores.com/books/view.aspx?id=eb6cce75-0b97-47fb-8b7e-a8baa38f6fba) | Not licensed for reuse; not copied. Jacket credit is not identified in retailer metadata. |
| The Blue Elephant / الفيل الأزرق · Ahmed Mourad | Dar El Shorouk Arabic edition · ISBN 9789770932278 | [Diwan listing](https://diwanegypt.com/product/%D8%A7%D9%84%D9%81%D9%8A%D9%84-%D8%A7%D9%84%D8%A7%D8%B2%D8%B1%D9%82/) | Not licensed for reuse; not copied. Cover credit remains with publisher/cover artist as printed on jacket. |
| The Granada Trilogy / ثلاثية غرناطة · Radwa Ashour | Dar El Shorouk Arabic edition · ISBN 9789770907375 | [Diwan listing](https://diwanegypt.com/product/%D8%AB%D9%84%D8%A7%D8%AB%D9%8A%D8%A9-%D8%BA%D8%B1%D9%86%D8%A7%D8%B7%D8%A9/) · [Shorouk edition record](https://www.shoroukbookstores.com/books/view.aspx?id=f80e0786-0102-4e21-9181-7ef9746594a0) | Not licensed for reuse; not copied. Jacket credit is not identified in retailer metadata. |
| The Thief and the Dogs / اللص والكلاب · Naguib Mahfouz | Diwan Arabic edition · ISBN 9789778616170 | [Diwan listing](https://diwanegypt.com/product/%D8%A7%D9%84%D9%84%D8%B5-%D9%88%D8%A7%D9%84%D9%83%D9%84%D8%A7%D8%A8-2/) | Not licensed for reuse; not copied. Cover credit remains with publisher/cover artist as printed on jacket. |
| Adrift on the Nile / ثرثرة فوق النيل · Naguib Mahfouz | Diwan Arabic edition · ISBN 9789778616194 | [Diwan listing](https://diwanegypt.com/product/%D8%AB%D8%B1%D8%AB%D8%B1%D8%A9-%D9%81%D9%88%D9%82-%D8%A7%D9%84%D9%86%D9%8A%D9%84-2/) | Not licensed for reuse; not copied. Cover credit remains with publisher/cover artist as printed on jacket. |
| Morning and Evening Talk / حديث الصباح والمساء · Naguib Mahfouz | Diwan Arabic edition · ISBN 9789778616231 | [Diwan listing](https://diwanegypt.com/product/%D8%AD%D8%AF%D9%8A%D8%AB-%D8%A7%D9%84%D8%B5%D8%A8%D8%A7%D8%AD-%D9%88-%D8%A7%D9%84%D9%85%D8%B3%D8%A7%D8%A1/) | Not licensed for reuse; not copied. Cover credit remains with publisher/cover artist as printed on jacket. |
| Step Outside the Script, Again / الخروج عن النص من جديد · Mohamed Taha | Dar El Shorouk Arabic edition · ISBN 9789770937396 | [Diwan listing](https://diwanegypt.com/product/%D8%A7%D9%84%D8%AE%D8%B1%D9%88%D8%AC-%D8%B9%D9%86-%D8%A7%D9%84%D9%86%D8%B5-%D9%85%D9%86-%D8%AC%D8%AF%D9%8A%D8%AF/) | Not licensed for reuse; not copied. Jacket credit is not identified in retailer metadata. |
| Atomic Habits · James Clear | Penguin Random House USA edition · ISBN 9780593189641 | [Diwan listing](https://diwanegypt.com/product/atomic-habits/) | Not licensed for reuse; not copied. PRH directs cover/image reproduction requests to its permissions portal; cover artist not identified in listing metadata. |
| Fizo in the Wardrobe / فيزو فى الدولاب · Walid Taher | Dar El Shorouk Arabic edition · ISBN 9789770925003 | [Diwan listing](https://diwanegypt.com/product/%D9%81%D9%8A%D8%B2%D9%88-%D9%81%D9%89-%D8%A7%D9%84%D8%AF%D9%88%D9%84%D8%A7%D8%A8/) | Not licensed for reuse; not copied. Jacket credit is not identified in retailer metadata. |
| Mimi the Duck’s Story / حكاية البطة ميمي · Amina Mujahid | Arabic edition · publisher shown as Al-Sharq by Diwan · ISBN 9789779404301 | [Diwan listing](https://diwanegypt.com/product/%D8%AD%D9%83%D8%A7%D9%8A%D8%A9-%D8%A7%D9%84%D8%A8%D8%B7%D9%87-%D9%85%D9%8A%D9%85%D9%8A/) | Not licensed for reuse; not copied. Jacket credit is not identified in retailer metadata. |
| The Very Hungry Caterpillar / الدودة الشديدة الجوع · Eric Carle | Dar Al Balsam Arabic edition · ISBN 9789776171039 | [Diwan listing](https://diwanegypt.com/product/%D8%A7%D9%84%D8%AF%D9%88%D8%AF%D8%A9-%D8%A7%D9%84%D8%B4%D8%AF%D9%8A%D8%AF%D8%A9-%D8%A7%D9%84%D8%AC%D9%88%D8%B9/) | Not licensed for reuse; not copied. Cover credit remains with rights holder as printed on jacket. |

The JavaScript catalog records each cover listing, ISBN, listed publisher/edition, and the “not cleared” status. The existing catalog source links and the book-detail modal’s **View this edition and its cover** link lead to the relevant retailer page. If a publisher later grants permission, add the optimized local image under `assets/book-covers/` and set that book’s `coverImage` to the relative path; cards, spotlight, modal, and reader recommendation already support a licensed local image with `object-fit: contain`. Until then, all 13 use the labeled AWRAQ original-art alternative.

## Alexandria photography and licenses

The images are local assets to avoid unreliable hotlinks. Names and links are also shown beside image sections in the page. Retain these credits and license links when reusing the photographs.

| Local asset | Depiction / creator | Source and license |
| --- | --- | --- |
| `assets/bibliotheca-interior.jpg` | Bibliotheca Alexandrina reading hall · Carsten Whimster | [Commons file page](https://commons.wikimedia.org/wiki/File:CW_BibliotechaAlexandrina_Inside.jpg) · CC BY 3.0 |
| `assets/bibliotheca-exterior.jpg` | Bibliotheca Alexandrina exterior · Mahmoud Saaid | [Commons file page](https://commons.wikimedia.org/wiki/File:BA_outside_view.jpg) · CC BY 2.5 |
| `assets/qaitbay-corniche.jpg` | Qaitbay Citadel from the Corniche · Daniel Mayer | [Commons file page](https://commons.wikimedia.org/wiki/File:Alexandria_-_Citadel_of_Qaitbay_from_the_Corniche.JPG) · CC BY-SA 4.0 (also GFDL) |
| `assets/alexandria-street.jpg` | Alexandria buildings / street · Ibrahim El-Mezayen | [Commons file page](https://commons.wikimedia.org/wiki/File:Alexandria_buildings.jpg) · CC BY-SA 4.0 |
| `assets/corniche-licensed.jpg` | Alexandria Corniche · Wing045 | [Commons file page](https://commons.wikimedia.org/wiki/File:Alexandria_Corniche.jpeg) · CC BY-SA 3.0 |
| `assets/corniche.jpg` | Alexandria Corniche view · Mahmoud Saaid | [Commons file page](https://commons.wikimedia.org/wiki/File:Corniche.jpg) · CC BY 2.5 |

The local copies are resized for web delivery where noted by their dimensions. No endorsement by the photographers, Wikimedia Commons, or Bibliotheca Alexandrina is implied. The Pharos and ancient Library references in the story are historical context, while AWRAQ’s lighthouse motif and contemporary bookstore story are brand storytelling.

Historical reference links: [UCL’s Digital Egypt page on the Library of Alexandria](https://www.ucl.ac.uk/museums-static/digitalegypt/writing/library/alexandria.html) dates the Library and Museum to the third century BCE; the [Egyptian Museum’s Pharos overview](https://egyptianmuseum.org/explore/greco-and-roman-period-lighthouse-alexandria) locates the lighthouse on Pharos Island; and the [Bibliotheca Alexandrina overview](https://www.bibalex.org/en/page/overview) describes the modern institution’s relationship to the ancient library’s spirit. These are concise contextual references, not claims of institutional endorsement.

## Final browser and submission audit

Executed 16 November 2026 against the local HTTP preview (`python3 -m http.server 8000`) in Chrome:

- [x] Viewed the English and Arabic hero compositions; found and fixed a grid placement issue that had hidden the desktop hero photo.
- [x] Checked viewport widths 320, 375, 430, 768, 1024, and 1440 px; the page document width matched each viewport (no horizontal overflow).
- [x] Confirmed the three lazy-loaded photo essay images loaded at their local paths; no broken image was found.
- [x] Browser console error log was empty during the interaction pass.
- [x] Switched English/Arabic and verified `lang` and `dir` update (`en/ltr`, `ar/rtl`). Switched light/dark themes.
- [x] Combined “Mahfouz” live search with the Novels filter; it returned the five matching Mahfouz novels.
- [x] Opened and keyboard-closed a book detail dialog.
- [x] Added a book, increased quantity, confirmed the total changed from EGP 450 to EGP 900, refreshed, confirmed the quantity persisted, then removed it.
- [x] Submitted the newsletter empty to confirm inline errors, then with valid demo data to confirm in-page success without navigation.
- [x] Opened the mobile navigation at 375 px and followed a link; it closed and the document remained within viewport width.
- [x] Static audit: HTML parsed, IDs unique, local asset references exist, `git diff --check` clean, and JavaScript parses with `vm.Script`.

**Not verified:** assistive-technology/screen-reader behavior, automated contrast scoring, real email delivery or checkout (intentionally absent), and price/stock changes after the stated check date. Reduced-motion is implemented in CSS, but was not separately emulated in the browser.

**Book-cover regression check (16 November 2026):** all 13 catalog entries have distinct ISBNs and matched retailer cover-listing links. An initial reload after editing exposed a JavaScript syntax error; it was corrected before the final reload. The corrected page rendered all 13 cards, featured cover, cover-linked detail modal, and a reader recommendation cover tile; subsequent interactions produced no new JavaScript errors. Checked 320, 375, 430, 768, 1024, and 1440 px again with no horizontal overflow. There are zero local authentic cover images because no reuse license or direct permission was established; the source pages remain linked so the matching jackets can be viewed there.

## GitHub Pages

1. Put `index.html`, `style.css`, `script.js`, `README.md`, and the `assets/` folder at the repository root.
2. Push the files to the repository’s default branch.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, select the default branch and `/ (root)`, then save.
5. Visit the published URL shown in Pages settings after deployment completes.

All local image and stylesheet paths are relative; there is no build output to configure. To publish: create a GitHub repository, upload `index.html`, `style.css`, `script.js`, `README.md`, and the complete `assets/` folder at its root, then commit the upload. In **Settings → Pages**, select **Deploy from a branch**, choose the default branch and `/ (root)`, and save. GitHub will show the Pages URL when deployment completes. No public repository or deployment has been created from this workspace.

## Compliance checklist

- [x] Vanilla HTML5, CSS3, and ES6+ only; no framework, dependency, build tool, or backend.
- [x] Required project files are present and the site can be opened locally or hosted on GitHub Pages.
- [x] Every book card and modal is rendered from the JavaScript catalog.
- [x] 13 real published books cover novels, self-development, and children’s reading; Egyptian authors include Mahfouz, Mourad, Idris, and Ashour.
- [x] Source-listed prices, ISBNs, stock notes, original spoiler-free synopses, recommendations, and individual source links are stored with product data.
- [x] Each product has a cover listing and ISBN edition record; covers link to the matching retailer listing.
- [x] Cover images are not embedded without reuse permission; all 13 current jackets remain labeled AWRAQ alternatives.
- [x] Locally stored Alexandria photographs include author and reuse-license credits.
- [x] Detail modal, deterministic recommendation, light/dark theme, search/filter, cart persistence, and newsletter validation are implemented.
- [x] Language and theme persist independently; Arabic uses RTL and English uses LTR.
- [x] Historical references are distinguished from brand storytelling; Bibliotheca Alexandrina non-affiliation is explicit.
- [x] Responsive layout, keyboard controls, Escape closing, focus handling, and reduced-motion support are included.
- [x] Local browser and static checks are recorded in the final audit above.
- [x] No checkout, order processing, email transmission, or server storage is claimed.

## Project files

- `index.html` — semantic page structure and local asset references.
- `style.css` — light/dark visual systems, photo composition, original covers, responsive layout, and motion.
- `script.js` — catalog and sources, bilingual UI, theme, modal, recommendation, search, cart, and validation.
- `assets/` — locally stored, attributed Alexandria photographs. No `assets/book-covers/` folder is included because none of the 13 retailer cover images had a confirmed reuse license.
