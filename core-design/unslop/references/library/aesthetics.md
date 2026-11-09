# Aesthetic library

The art director's sampling pool: 63 visual directions, each with lineage, real references, fit, signature moves, a token sketch, slop risk, saturation and repo resources. Nothing here is a default. The brief chooses, and the 20 rules in `core-design/unslop/SKILL.md` override any move listed below.

## Contents

- How the art director uses this file
- Catalog (63 entries, one `###` heading each)
- Saturation notes
- Sources

Families, for sampling across lineages (names match the `###` headings):

- Print and art history: Constructivism, Bauhaus, Art Deco, Swiss International, Mid-century modern, Retro 70s, Memphis, Postmodern new wave
- Hand-made and counterculture: Risograph zine, Collage, Hand-drawn, Craft heritage
- Publishing: Editorial magazine, Newspaper, Warm editorial minimal, Document-like, Academic
- Luxury, film and photo: Luxury fashion, Quiet luxury, Cinematic, Documentary photo-led
- Interface eras: Retro computing, Pixel, Skeuomorphic, Frutiger Aero, Y2K, Vaporwave, Flat, Material, Corporate Memphis, Glassmorphism, Neumorphism, Claymorphism, Gradient mesh, Bento product, Brutalist web, Neo-brutalism, Dark SaaS precision, Soft premium SaaS, AI-native assistant
- Screens and futures: Data-dense terminal, HUD sci-fi, Cyberpunk, Solarpunk, Immersive 3D, Kinetic type, Dithered low-tech
- Cultures: Japanese minimal, Scandinavian, Script-native bilingual
- Industries and moods: Civic, Enterprise systematic, Industrial, Transit wayfinding, Architectural, Sports, Food warm, Organic natural, Botanical, Playful kids, Gamified, Maximalist, Monochrome

## How the art director uses this file

**Start from the brief, not the catalog.** Open this file only after the five brief lines from unslop step 1 exist (who and where, job, three voice words, named reference, real content). Without them you will pick by habit.

**1. Shortlist by fit, then by failure.** Pull 6-8 entries whose `Fits` clause matches the audience, the job and the content you actually have. Strike every entry whose `Fails` clause describes this brief, for example an image-led direction when no real photography exists.

**2. Develop three divergent directions.** Draw them from at least two families and make them differ on at least three axes: type class, palette strategy, density, radius, imagery mode, motion stance. Light, dark and colorful versions of one layout are one direction, not three. For each direction write:

- a name and a one-line thesis built from the voice words ("calm, clinical, careful" becomes "a pharmacy label, not a spa");
- the named reference it moves toward;
- the entry's token sketch rewritten for this brand;
- the one signature move a stranger would recognize;
- two moves from the entry you refuse, and why.

**3. Never pick by habit.** A direction you used on the previous project, or one rated `high`, needs a written reason tied to the brief before it can be one of the three. At least one of the three is rated `low` or `medium`. If all three feel safe, replace the safest one.

**4. Choose and record.** The creative director picks one direction. Write one line on why each of the other two lost, so later passes do not drift back toward the default.

**Blending two directions.** One direction owns structure: grid, density, type hierarchy and radius. The other lends at most two signature moves, such as its palette strategy, its imagery treatment or its motion stance. Name the blend in five words or fewer ("Swiss grid, Risograph color"). Density and radius must agree, or you state the logic (rule 14). Test by deleting the borrowed moves: the page should still stand. If it collapses, you built a collage of costumes.

**Make it the brand's own, not a costume.** A costume uses every move of a movement at full strength. A brand keeps the two or three moves that carry its message and translates them into its own material.

- Swap period props for real ones: the product's real model numbers instead of fake plate numbers, a real sequence instead of decorative "01 / 02 / 03" (rule 13).
- Take the accent from the brand or brief (rule 11), never from the movement's stock palette: Constructivist red only if the brand is red.
- Typefaces named under Lineage or Real references are history, not picks. Choose fonts by browsing for the voice words (unslop step 2).
- Shoot or render the brand's own physical world in the direction's manner (rule 6). A direction is a lens, not a stock-photo filter.
- Compare the result with the brief's named reference: it should feel closer to that reference than to the movement's textbook page.
- If the brand already has tokens, components or a DESIGN.md, they win (rule 5); use the catalog only for the gaps.

**Reading an entry.** `Lineage` says where the look comes from. `Real references` are makers to study, not to copy. `Fits` ends with a `Fails:` clause. `Token sketch` gives classes and strategies, never exact fonts or hex values. `Slop risk` describes how generators fake the look and names the unslop rules it collides with. `Saturation` rates how often generators produce the look unprompted in 2024-2026 (`low` rare, `medium` common, `high` reads as AI on sight). `Repo resources` are paths from the repo root.

**Repo caveats.** The one-word style folders in `design-systems/brand-systems/` (brutalism, editorial, glassmorphism, retro and similar) are thin: a palette, a font trio and generic rules, so treat them as starter tokens. Several repo skills hard-code moves the unslop rules reject, such as eyebrow pills, mono metadata, ASCII ornament, global grain and scroll fades: `styles/minimalist-ui/`, `styles/industrial-brutalist-ui/`, `templates/web-prototype-taste-brutalist/`, `templates/web-prototype-taste-editorial/`, `templates/web-prototype-taste-soft/`, `core-design/high-end-visual-design/`, `design-systems/brand-systems/atelier-zero/`. Take structure and tokens from them; unslop stays the driver.

## Catalog

Every entry is a `###` name followed by the same eight lines. Keep the format; a script reads the names and the Saturation values.

### Constructivism
- **Lineage:** Russian avant-garde after 1917: artists turned to posters, books and film publicity for the new state, using diagonals, photomontage and a red and black palette [S1]; El Lissitzky's and Rodchenko's book design fed Jan Tschichold's "Die neue Typographie" [B1].
- **Real references:** El Lissitzky's "Beat the Whites with the Red Wedge" (1919) and his design of Mayakovsky's "For the Voice" (1923); Alexander Rodchenko's Dobrolet and Mosselprom advertising (1923-1925) [S1]; Vladimir and Georgii Stenberg's film posters, such as "Man with a Movie Camera" (1929).
- **Fits:** Manifestos, campaigns, unions and activist groups, film and festival programs, launches built on one argument. Fails: calm services, healthcare, luxury and anything whose voice words say "gentle"; vague copy in this style reads as propaganda.
- **Signature moves:** Type: heavy condensed sans set in blocks and on diagonals, words used as shapes; color: red and black on unbleached paper, at most one more spot color; layout: dynamic diagonals, overlapping planes, cut photomontage; imagery: high-contrast photography, cropped and angled; motion: hard cuts and slides along the main diagonal.
- **Token sketch:** Type class: condensed grotesque, two weights; palette: ink plus one brand-derived spot color on paper; radius: 0; density: medium, large type blocks against open ground.
- **Slop risk:** Generators paste a red wedge and a tilted headline onto an ordinary SaaS layout. The diagonal must organize content, rotated text that is not reading content breaks rule 13, and red is the accent only if the brand is red (rule 11).
- **Saturation:** low
- **Repo resources:** none (closest structure: `templates/poster-hero/`)

### Bauhaus
- **Lineage:** The Bauhaus school ran in Weimar (1919-1925), Dessau (1925-1932) and Berlin (1932-1933); László Moholy-Nagy's arrival in 1923 moved typography to the center, and Herbert Bayer's lowercase "universal" alphabet became its emblem [S2][B2].
- **Real references:** Herbert Bayer's universal alphabet and Bauhaus print work [S2]; Moholy-Nagy's "typophoto" layouts; Joost Schmidt's poster for the 1923 Bauhaus exhibition; Marianne Brandt's metalwork.
- **Fits:** Art and design schools, architecture and maker institutions, tools for builders, learning products that want geometry instead of cartoons. Fails: romantic or luxury brands, dense data apps, and any palette that needs nuance; the primary triad turns childish fast.
- **Signature moves:** Type: geometric sans, lowercase experiments, thick rules and bars beside type; color: red, yellow and blue with black on white; layout: asymmetric balance on a clear grid, circle, square and triangle as structural blocks; imagery: photography combined with type, products on plain ground; motion: shapes translating or rotating in exact steps.
- **Token sketch:** Type class: geometric sans, one family; palette: one brand-derived primary as the accent, the other primaries as rare structural fills; radius: 0, or full circles only; density: low to medium.
- **Slop risk:** The costume is confetti of circles and triangles around a centered headline. Shapes must carry structure (sections, numbers, navigation), and three equal primaries break rule 11.
- **Saturation:** low
- **Repo resources:** `templates/html-ppt/assets/themes/bauhaus.css`, `core-design/ui-ux-pro-max/data/styles.csv` (row "Bauhaus")

### Art Deco
- **Lineage:** Machine-age luxury of the 1920s and 1930s in posters, architecture and ocean liners, named retrospectively after the 1925 Paris Exposition internationale des arts décoratifs [B2].
- **Real references:** A. M. Cassandre's "Normandie" poster for the French Line (1935) [S3] and his rail posters; the Chrysler Building by William Van Alen (1930).
- **Fits:** Hotels, bars, cinemas and theaters, jewelry, spirits, invitations, anything with a 1920s-30s story or a hospitality ritual. Fails: tech products without a period story, children's products, accessibility-first services; ornament at small sizes becomes noise.
- **Signature moves:** Type: tall geometric display capitals with strong stroke contrast, wide spacing on short lines only; color: black, cream and a metallic gold or one jewel tone; layout: vertical symmetry, stepped frames, sunburst and chevron geometry; imagery: streamlined machines and buildings seen from below; motion: slow symmetrical reveals.
- **Token sketch:** Type class: geometric or Didone display capitals plus a plain text face; palette: dark ground, one metallic-feeling accent from the brand, cream text; radius: 0 with stepped corners; density: low.
- **Slop risk:** Gold gradient text and fan ornaments on every section break rule 13 twice. Keep ornament to one hero frame or menu, use a flat ochre that passes contrast instead of a shine, and keep body text plain and large (rule 15).
- **Saturation:** low
- **Repo resources:** none (pairings tagged "art deco" live in `core-design/ui-ux-pro-max/data/typography.csv`; reject reflex picks per unslop step 2)

### Swiss International
- **Lineage:** The International Typographic Style grew in Zurich and Basel in the 1940s and 1950s from Ernst Keller's teaching, through Josef Müller-Brockmann, Armin Hofmann and Emil Ruder, and spread through the journal Neue Grafik from 1958 [S4][B3][B4].
- **Real references:** Müller-Brockmann's Zurich Tonhalle concert posters and "Grid Systems in Graphic Design" (1981) [B3]; Ruder's "Typographie" (1967) [B4]; Hofmann's Basel theater posters; Unimark's 1970 New York subway manual (see Transit wayfinding).
- **Fits:** Information-heavy products, cultural institutions, transport, documentation, B2B with real data; voice words like "precise, objective, legible". Fails: brands that need warmth or humor, and thin content; a grid with nothing to arrange looks empty, not Swiss.
- **Signature moves:** Type: neo-grotesque, flush left and ragged right, hierarchy from size and weight only; color: white or off-white, black, one strong accent; layout: modular grid with visible alignment, asymmetric placement, generous margins; imagery: objective photography, often black and white, cropped to the grid; motion: almost none, state changes snap or slide along grid lines.
- **Token sketch:** Type class: grotesque or neo-grotesque, one family, 3-4 sizes with large jumps; palette: neutral plus one brand accent; radius: 0; density: medium to high, governed by the grid.
- **Slop risk:** Generator Swiss is a Helvetica-like sans, a red square and a 12-column grid that nothing aligns to. Make the grid real (shared baselines and column edges, rule 17) and skip faux plate numbers and crosshair marks (rule 13).
- **Saturation:** medium
- **Repo resources:** `templates/deck-swiss-international/`, `templates/html-ppt/assets/themes/swiss-grid.css`, `styles/industrial-brutalist-ui/` (Swiss Industrial Print mode), `core-design/ui-ux-pro-max/data/styles.csv` (rows "Minimalism & Swiss Style", "Swiss Modernism 2.0")

### Mid-century modern
- **Lineage:** American and European modernism of roughly 1945-1965, when corporate identity, film titles and furniture carried European modernism to mass audiences [B2][B5].
- **Real references:** Saul Bass's titles for Hitchcock's "Vertigo" (1958), made with John Whitney's spirals, and for "Anatomy of a Murder" (1959) [S5]; Paul Rand's IBM logos and his "Thoughts on Design" (1947) [B5]; Charles and Ray Eames's furniture and films.
- **Fits:** Furniture and interiors, architecture practices, coffee and hospitality, film festivals, consumer products with an optimistic, crafted personality. Fails: hard enterprise tools, finance that earns trust through restraint, and youth brands that read it as their parents' living room.
- **Signature moves:** Type: friendly geometric or humanist sans with cut-paper display lettering; color: muted warm set (mustard, teal, tomato, olive) on cream; layout: loose asymmetric compositions, paper shapes overlapping photos; imagery: flat cut-paper illustration, silhouettes, period-true product photography; motion: jaunty stepped animation like a title card, short.
- **Token sketch:** Type class: geometric or humanist sans plus one display cut; palette: one warm brand accent plus two muted supports on cream; radius: small (2-6px), organic shapes only inside illustration; density: low to medium.
- **Slop risk:** Boomerangs and starbursts as wallpaper and the full mustard-teal-tomato set on every page. Pick one accent (rule 11) and confine the cut-paper language to one illustration system.
- **Saturation:** low
- **Repo resources:** `templates/html-ppt/assets/themes/midcentury.css`

### Retro 70s
- **Lineage:** 1970s graphics: soft heavy display type, supergraphics, earth tones and confident identity systems such as NASA's 1975 Graphics Standards Manual by Danne & Blackburn [S6].
- **Real references:** the NASA Graphics Standards Manual and its "worm" logotype, since reissued by Standards Manual [S6]; Herb Lubalin's work for ITC and its magazine U&lc.
- **Fits:** Food and drink, outdoor and travel, music, personal finance that wants warmth, small consumer brands with a real founder story. Fails: precision tools, medical, and briefs where looking current matters; the palette goes muddy on screens unless contrast is checked.
- **Signature moves:** Type: soft heavy display with tight spacing, rounded or chunky serifs, set large; color: rust, mustard, olive and brown on cream; layout: big stacked type, stripes or arcs as supergraphics, rounded rectangles; imagery: warm film photography, sun-faded color; motion: slow slides and stripe wipes.
- **Token sketch:** Type class: soft display serif or rounded heavy sans plus a neutral text face; palette: one earth-tone accent from the brand on warm cream, deep brown ink instead of black; radius: medium, one value; density: low to medium.
- **Slop risk:** A sunset-stripe badge and faux-distressed texture over everything (rule 13). Use one supergraphic per page at most, real warm photography instead of a filter, and check brown-on-cream contrast (rule 15).
- **Saturation:** medium
- **Repo resources:** `design-systems/theme-factory/themes/golden-hour.md`, `design-systems/brand-systems/vintage/` (thin tokens)

### Memphis
- **Lineage:** The Memphis Group, formed in Milan around Ettore Sottsass in December 1980, named after a Bob Dylan song, first shown in 1981 and disbanded in 1988 [S7].
- **Real references:** Sottsass's "Carlton" room divider (1981); Nathalie Du Pasquier's patterns; furniture by Peter Shire and Michele De Lucchi.
- **Fits:** Youth culture, events, toys and games, creative agencies, ice cream and snacks; loud joy with a design-history wink. Fails: finance, health, legal, B2B, and brands that cannot carry pattern without losing legibility.
- **Signature moves:** Type: bold geometric sans set straight, playful display only for titles; color: clashing brights (pink, yellow, cyan) with black; layout: collisions of simple volumes, tilted blocks; imagery: terrazzo, squiggle and laminate patterns, cut-out objects on flat color; motion: quick snaps, not bounce (rule 20).
- **Token sketch:** Type class: geometric sans; palette: one brand-led bright as the action color, pattern colors confined to illustration; radius: mixed only with a written logic (rule 14); density: medium.
- **Slop risk:** Random squiggles and dots sprinkled behind text, which is how "Corporate Memphis" got its name. Keep patterns inside defined shapes, never under body copy, and keep the action color unique (rule 11).
- **Saturation:** low
- **Repo resources:** `templates/html-ppt/assets/themes/memphis-pop.css`, `core-design/ui-ux-pro-max/data/styles.csv` (row "Memphis Design")

### Postmodern new wave
- **Lineage:** Wolfgang Weingart's Basel experiments broke Swiss rules from inside; April Greiman carried them to Los Angeles; Emigre, founded in Berkeley in 1984 by Rudy VanderLans and Zuzana Licko and among the first journals made on the Macintosh, and David Carson's Ray Gun took them into the 1990s [S8].
- **Real references:** Emigre magazine and its type foundry, which devoted issues to Carson and Ray Gun in 1992-1993 [S8]; April Greiman's "Does It Make Sense?" issue of Design Quarterly (1986); David Carson's Ray Gun spreads.
- **Fits:** Music, art schools, festivals, type foundries, culture magazines, portfolios where layering is the message. Fails: transactional or task-driven products and accessibility-critical services; illegibility is a feature only when reading is optional.
- **Signature moves:** Type: mixed families and sizes in one composition, layered and overlapping, spacing as expression; color: off-register overprints, acid accents on muted grounds; layout: deconstructed grids, type and image collage, text on paths; imagery: scans, video stills, photocopies; motion: jump cuts and layered parallax that stays readable.
- **Token sketch:** Type class: a neutral grotesque plus one eccentric display, with written rules for which goes where; palette: two inks plus a neutral; radius: 0; density: high in compositions, low in reading areas.
- **Slop risk:** Chaos without a system reads as broken. Keep the layering for openers, set body text in one clean column at 60-75ch (rule 16), and hold contrast on every overlap (rule 15).
- **Saturation:** low
- **Repo resources:** none

### Risograph zine
- **Lineage:** Riso Kagaku's stencil duplicators, built for schools and offices, were taken up by independent publishers in the 2000s; misregistration, grain and overprinting spot inks became the look of the small-press revival [S9].
- **Real references:** the Riso-printed zines and art books of the art-book fair circuit, such as Printed Matter's NY Art Book Fair; Riso Kagaku's machines themselves, whose one-drum-per-color process defines the look [S9].
- **Fits:** Independent publishers, bookshops, community events, small food and drink brands, illustrators, education side projects; voice words like "handmade, local, generous". Fails: premium finance and enterprise, brands needing photographic accuracy, and dense UI where overprint texture cannot survive.
- **Signature moves:** Type: chunky grotesque or typewriter-like faces at large sizes, little text; color: two or three spot inks (fluorescent pink, blue, yellow) overprinting into new colors; layout: poster-like pages, intentional misregistration of a few pixels; imagery: halftoned or grainy photos, simple illustration; motion: little or none.
- **Token sketch:** Type class: grotesque or slab plus a plain text face; palette: two spot colors, one of them the brand accent, overprinted with multiply; radius: 0 or small; density: low.
- **Slop risk:** A grain overlay across the page plus a pink and blue duotone is the shortcut, and rule 13 rejects global grain. Texture images and display type only; controls stay flat and crisp, and spot inks stay out of body text.
- **Saturation:** low
- **Repo resources:** none (halftone techniques are described in `styles/industrial-brutalist-ui/`)

### Collage
- **Lineage:** Dada photomontage (Hannah Höch, John Heartfield) and Kurt Schwitters's Merz collages, then punk's cut-and-paste, including Jamie Reid's ransom-note lettering for the Sex Pistols' "God Save the Queen" (1977) [S10][B2].
- **Real references:** Höch's "Cut with the Kitchen Knife" (1919-1920); Reid's Sex Pistols artwork [S10]; Quentin Fiore's layouts for "The Medium Is the Massage" (1967) [B6].
- **Fits:** Culture and music, editorial features, activist campaigns, fashion lookbooks, brands whose story is assembled from many sources. Fails: data products, onboarding flows, any interface where users must find a control fast.
- **Signature moves:** Type: cut-out letters and mixed sources for display only, a calm text face for reading; color: paper whites, newsprint and one or two strong inks; layout: layered torn fragments, overlapping cutouts, tape seams; imagery: photographs with hard or torn edges, scans of real paper; motion: pieces dropping into place one by one.
- **Token sketch:** Type class: neutral text face plus collage display assets; palette: paper neutrals plus one brand ink; radius: 0, edges come from the cut; density: medium in collages, low elsewhere.
- **Slop risk:** Generators fake collage with CSS rotations and drop shadows on stock photos, decoration that explains nothing (rule 13). Build collages from the brand's own photos and documents (rule 6) and keep navigation, forms and body text out of the collage layer.
- **Saturation:** low
- **Repo resources:** `design-systems/brand-systems/atelier-zero/` (collage system; its italic-serif headline mixing, rotated side notes and global paper noise conflict with rules 3 and 13), `core-design/ui-ux-pro-max/data/styles.csv` (row "Anti-Polish / Raw Aesthetic")

### Hand-drawn
- **Lineage:** Illustrated packaging, children's books, comics and sketchnotes; on the web, illustration-led brands use drawn marks to signal a human voice.
- **Real references:** Oatly's handwritten packaging; PostHog's hand-drawn hedgehogs; Excalidraw's sketchy diagrams (rendered with rough.js); Randall Munroe's xkcd explainers.
- **Fits:** Education, explainers, indie tools, warm wellness without pastel blobs, products whose founders draw, diagrams that should feel provisional. Fails: luxury, security and finance, where it reads as unserious, and teams without one consistent illustrator.
- **Signature moves:** Type: a clean text face, hand lettering only for short notes and titles; color: ink on paper plus one marker color; layout: arrows and annotations that point at real product details; imagery: one hand and one line weight across all drawings; motion: draw-on strokes for diagrams only.
- **Token sketch:** Type class: humanist sans or friendly serif; palette: ink, paper and one marker accent from the brand; radius: irregular inside drawings, one small radius on controls; density: low to medium.
- **Slop risk:** Hand-drawn SVG icons beside a stock icon set break rule 12, and comic-font body text breaks reading. Draw illustrations, not interface icons, and keep controls in one icon family.
- **Saturation:** low
- **Repo resources:** `templates/wireframe-sketch/`, `templates/frame-flowchart-sticky/`, `design-systems/brand-systems/doodle/` (thin tokens), `design-systems/brand-systems/posthog/`

### Craft heritage
- **Lineage:** Letterpress, wood type and workwear labels, descended from the Arts and Crafts movement; Nashville's Hatch Show Print, founded in 1879, still prints posters from its wood type and has run as a non-profit working museum since 1986 [S11].
- **Real references:** Hatch Show Print posters [S11]; William Morris's Kelmscott Press books (1891-1898); Filson's workwear labels (the company dates from 1897).
- **Fits:** Makers, breweries, distilleries, workwear, outdoor goods, bookshops and local institutions with real history. Fails: brands without real heritage, where it becomes fake vintage, and digital-first products that must feel current.
- **Signature moves:** Type: wood-type display, slab serifs and condensed gothics at poster sizes, a readable text face; color: red, black or blue ink on uncoated paper, kraft and cream; layout: centered poster stacks and labels, borders as frames; imagery: process photos, tools, hands, the workshop; motion: none or very little.
- **Token sketch:** Type class: slab or wood-type display plus a text serif; palette: one ink accent from the brand on paper tones; radius: 0; density: medium.
- **Slop risk:** "Est. 2024" badges, fake distress textures and invented founding stories (rules 1, 9 and 13). Show the real workshop, real dates and real makers.
- **Saturation:** low
- **Repo resources:** `design-systems/brand-systems/vintage/` (thin tokens), `design-systems/brand-systems/paper/` (thin tokens), `image-direction/canvas-design/` (poster output)

### Editorial magazine
- **Lineage:** Magazine art direction from Alexey Brodovitch at Harper's Bazaar (1934-1958), who composed spreads as single images with white space as material [S12], to Richard Turley's Bloomberg Businessweek (2010-2014), where the grid exists to be broken by graphics and covers aim to surprise [S13].
- **Real references:** Harper's Bazaar under Brodovitch [S12]; Bloomberg Businessweek under Turley [S13]; WIRED; The New York Times Magazine.
- **Fits:** Long-form publishers, brands with real stories and photography, annual reports, cultural institutions, newsletters with a point of view. Fails: tools where users act rather than read, and briefs that are not magazine-shaped, where it reads as borrowed prestige.
- **Signature moves:** Type: a display face with character at large sizes, a sturdy text face, decks and captions as real hierarchy; color: ink and paper, with color from photography and one accent; layout: spreads, varied column widths, pull quotes and crops that change rhythm per story; imagery: commissioned or real photography art-directed per story; motion: restrained transitions between stories.
- **Token sketch:** Type class: contrasting display plus text serif or sans; palette: ink and paper plus one accent; radius: 0; density: medium, varied by section.
- **Slop risk:** The generator version is an italic serif headline, a tiny mono kicker, hairline rules and no photography (see Warm editorial minimal). Earn the look with real stories and images, vary layouts between sections, skip the eyebrow on every section (rule 2), and set pull quotes by size and space, since thick left borders trip the lint's side-stripe check.
- **Saturation:** medium
- **Repo resources:** `templates/article-magazine/`, `templates/magazine-poster/`, `design-systems/brand-systems/wired/`, `design-systems/brand-systems/publication/` (thin tokens), `templates/html-ppt/assets/themes/magazine-bold.css`, `core-design/ui-ux-pro-max/data/styles.csv` (row "Editorial Grid / Magazine")

### Newspaper
- **Lineage:** Broadsheet and Berliner news design: column grids, headline weight as news value, datelines and rules; the Guardian's 2005 Berliner redesign, led by Mark Porter, commissioned the Guardian Egyptian family from Paul Barnes and Christian Schwartz [S14].
- **Real references:** the Guardian's 2005 redesign and Guardian Egyptian [S14]; the Financial Times on its salmon paper; The New York Times graphics desk.
- **Fits:** News, local journalism, newsletters, research digests, status pages and changelogs with many items of unequal importance. Fails: single-product marketing pages with little content; the look needs volume and real hierarchy.
- **Signature moves:** Type: a robust headline face in several weights, a text face built for small sizes, bylines and datelines as metadata; color: paper, ink and one section color; layout: multi-column grid, story weight shown by headline size and column span, thin column rules; imagery: news photography with credits, charts with sources; motion: none beyond live-update cues.
- **Token sketch:** Type class: headline serif or grotesque plus a text serif; palette: neutral paper plus one accent for links or breaking news; radius: 0; density: high.
- **Slop risk:** Generators add fake datelines, issue numbers and an invented "Est." year on the masthead (rules 9 and 13). Every date, byline and number is real or labeled sample data, and story importance actually varies.
- **Saturation:** low
- **Repo resources:** `design-systems/brand-systems/wired/` (broadsheet density), `templates/frame-data-chart-nyt/`, `templates/html-ppt/assets/themes/news-broadcast.css`

### Warm editorial minimal
- **Lineage:** The 2020s SaaS adaptation of editorial design: warm off-white canvas, display serif, small mono labels and hairline rules; `core-design/impeccable/reference/brand.md` already lists this "editorial-typographic" lane as saturated.
- **Real references:** Notion's marketing pages and Anthropic's Claude pages (see the repo's notion and claude systems).
- **Fits:** Writing, knowledge and research tools whose product is text, when the brand truly is calm and literate. Fails: most other briefs, because it is the current shorthand for "tasteful"; it also fails with no imagery or product to show.
- **Signature moves:** Type: display serif headings, grotesque body, mono only for shortcuts; color: warm paper, near-black ink, one muted accent; layout: generous margins, single-column hero, hairline dividers; imagery: product screenshots or ink illustration; motion: barely any.
- **Token sketch:** Type class: serif display plus sans text; palette: warm neutral plus one accent; radius: small (4-8px); density: low.
- **Slop risk:** It is the anti-default turned default: an italic serif word in the headline (rule 3), a tracked mono eyebrow on each section (rules 2 and 4), pale gray body text on beige (rule 15), no product shown (rule 6). Use it only with a written reason and change at least two of its moves.
- **Saturation:** high
- **Repo resources:** `styles/minimalist-ui/`, `templates/web-prototype-taste-editorial/`, `design-systems/brand-systems/warm-editorial/`, `design-systems/brand-systems/notion/`, `design-systems/brand-systems/claude/`, `core-design/impeccable/reference/brand.md`

### Document-like
- **Lineage:** The plain HTML document and the printed report: content first, browser defaults or close to them, from early academic pages to essay sites.
- **Real references:** Craigslist and Hacker News (plain, dense link pages); Berkshire Hathaway's bare website; Paul Graham's essay pages.
- **Fits:** Essays, policies, documentation, internal tools, changelogs, legal and pricing pages where trust comes from plainness; developer audiences who distrust marketing. Fails: consumer brands that need desire, image-led products, and pages where plainness reads as abandonment.
- **Signature moves:** Type: one readable text face, semantic headings, real lists; color: near-black on white, classic link blue; layout: one column at 60-75ch, table of contents, footnotes; imagery: captioned figures only when they inform; motion: none.
- **Token sketch:** Type class: text serif or system sans, one family; palette: ink, paper and one link color; radius: 0; density: medium.
- **Slop risk:** The fake version adds a minimal costume (tiny gray text, huge margins, a mono date line) and loses what makes plainness work: speed and legibility. Keep text dark (rule 15), headings balanced (rule 16), and add nothing that is not content.
- **Saturation:** low
- **Repo resources:** `design-systems/brand-systems/kami/`, `templates/doc-kami-parchment/`, `templates/kami-landing/`, `templates/docs-page/`, `templates/pm-spec/`

### Academic
- **Lineage:** Scholarly print and its digital heirs: Donald Knuth's TeX (1978) and LaTeX papers, Edward Tufte's books on displaying evidence [B7], and interactive research articles.
- **Real references:** Tufte's "The Visual Display of Quantitative Information" (1983) [B7]; the Distill journal's interactive machine-learning articles; Our World in Data's charts; arXiv preprints set in LaTeX.
- **Fits:** Research labs, universities, think tanks, scientific tools, data-heavy explainers, policy reports. Fails: impulse consumer products and playful brands; citation apparatus on a marketing page is a costume.
- **Signature moves:** Type: scholarly text serif with true small caps, old-style figures in prose and tabular figures in tables; color: black plus one muted annotation color; layout: wide margins with sidenotes, numbered figures, footnotes, references; imagery: charts and diagrams with sources; motion: interactive figures that respond to input, nothing decorative.
- **Token sketch:** Type class: text serif plus a quiet sans for UI; palette: ink and paper plus one annotation color; radius: 0; density: medium to high.
- **Slop risk:** Fake citations, invented figures and "Fig. 1" labels on decorative images (rules 9 and 13). Number figures only when the text refers to them, and every chart cites a real source or is labeled sample data.
- **Saturation:** low
- **Repo resources:** `templates/html-ppt/assets/themes/academic-paper.css`, `templates/kami-deck/`, `templates/data-report/`, `core-design/ui-ux-pro-max/data/styles.csv` (row "Academia (Scholarly Mobile)")

### Luxury fashion
- **Lineage:** Fashion magazines and house identities: Brodovitch-era white space and Didone mastheads [S12], then a 2010s convergence on plain all-caps sans logos, often traced to Saint Laurent under Hedi Slimane (2012), which critics call "blanding" [S15].
- **Real references:** Harper's Bazaar under Brodovitch [S12]; the simplified logos of Saint Laurent, Celine (which dropped its accent in 2018), Balenciaga and Burberry [S15].
- **Fits:** Fashion, beauty, jewelry, galleries, high-end hospitality with strong photography and few words. Fails: without commissioned imagery it collapses into an empty white page; it is also wrong for value brands and dense information.
- **Signature moves:** Type: high-contrast Didone or plain wide-tracked capitals for the wordmark, small precise text; color: black, white and the photograph; layout: full-bleed images, single asymmetric images with space, minimal navigation; imagery: editorial fashion photography and video as the main content; motion: slow crossfades and video.
- **Token sketch:** Type class: Didone or wide grotesque display, small neutral sans for UI; palette: monochrome, color only from imagery; radius: 0; density: very low.
- **Slop risk:** Pale captions on beige, a serif logo and a stock model photo; the "blanding" convergence is itself a known sameness. Use real campaign imagery (rule 6), keep captions readable (rule 15), and find one ownable typographic idea instead of generic wide capitals.
- **Saturation:** medium
- **Repo resources:** `design-systems/brand-systems/luxury/` (thin tokens), `design-systems/brand-systems/elegant/` (thin tokens), `image-direction/brandkit/`, `core-design/ui-ux-pro-max/data/styles.csv` (rows "Exaggerated Minimalism", "Minimalist Monochrome")

### Quiet luxury
- **Lineage:** The 2023 "quiet luxury" or "stealth wealth" moment in fashion, amplified by the series Succession: no logos, fine materials, muted palettes [S16].
- **Real references:** The Row, Loro Piana and Brunello Cucinelli, the labels most cited in that coverage [S16]; Aesop's apothecary-style bottles and stores.
- **Fits:** Premium services, hospitality, skincare, architecture and interiors, private banking, consultancies whose clients already know them. Fails: products that must be discovered or explained fast, and brands without the materials or craft to back the restraint, where restraint reads as beige.
- **Signature moves:** Type: refined text serif or quiet sans at modest sizes, no shouting display; color: tonal neutrals (stone, oat, charcoal) with one deep accent; layout: calm, symmetric, few elements, lots of space; imagery: close-up material photography (fabric, stone, glass) in soft daylight; motion: slow fades.
- **Token sketch:** Type class: text serif or humanist sans; palette: tonal neutral ladder tinted toward one deep brand hue; radius: small, one value; density: low.
- **Slop risk:** It slides into the generic beige landing page: pale gray text on cream (rule 15), no imagery, vague copy (rule 9). Show real materials and real offers; quiet does not mean empty.
- **Saturation:** medium
- **Repo resources:** `design-systems/brand-systems/refined/` (thin tokens), `design-systems/brand-systems/elegant/` (thin tokens), `image-direction/brandkit/`

### Cinematic
- **Lineage:** Film titles and movie marketing: Saul Bass's graphic title sequences [S5], widescreen framing, light and darkness as composition; on the web, dark full-bleed pages for studios, cars and media tools.
- **Real references:** Bass's "Vertigo" titles with John Whitney's spirals [S5]; Ferrari's and Bugatti's sites; Runway's media-led product pages (see the repo's systems).
- **Fits:** Film, games, automotive, music, launches of visual products, AI video or audio tools with real output to show. Fails: text-heavy services, accessibility-critical flows, anything without footage; a dark page with no film is just dark.
- **Signature moves:** Type: large display set sparingly like title cards, small precise UI type; color: near-black with light from the imagery, one accent; layout: full-bleed 16:9 or wider frames, one idea per viewport; imagery: real footage and stills with dramatic light; motion: deliberate sequences, crossfades and slow pushes, scroll-linked only when it tells a story.
- **Token sketch:** Type class: condensed or wide display plus neutral sans; palette: dark ground, imagery-led color, one accent; radius: 0 to small; density: very low.
- **Slop risk:** Lens flares, light leaks and grain over everything (rule 13), loops that never end (rule 20), and hero text over video without a scrim (rule 15). Use real footage, give motion an end, and honor reduced motion.
- **Saturation:** medium
- **Repo resources:** `templates/frame-light-leak-cinema/`, `templates/hyperframes/`, `design-systems/brand-systems/bugatti/`, `design-systems/brand-systems/ferrari/`, `design-systems/brand-systems/runwayml/`, `core-design/ui-ux-pro-max/data/styles.csv` (row "Modern Dark (Cinema Mobile)")

### Documentary photo-led
- **Lineage:** Photojournalism and the picture magazine: the photograph carries the argument and the design steps back.
- **Real references:** Magnum Photos (the cooperative founded in 1947); National Geographic's yellow-bordered covers; Patagonia's catalog and campaign photography; Tesla's and SpaceX's full-viewport photo pages (see the repo's systems).
- **Fits:** NGOs, travel, outdoor, architecture, food sourcing, journalism, any brand with real places and people. Fails: when only stock photos exist, which turns generic instantly, and abstract software with nothing physical to show.
- **Signature moves:** Type: quiet and functional, captions with credit and place; color: neutral chrome so photos hold the color; layout: large photographs at their true aspect ratios, sequences, captions next to images; imagery: real, specific, often unposed photographs of the brand's world; motion: slow sequence transitions, no zoom gimmicks.
- **Token sketch:** Type class: neutral sans or text serif; palette: neutral plus one accent taken from the photography; radius: 0; density: low.
- **Slop risk:** Category stock ("happy team at a laptop") instead of the brand's world breaks rule 6, and text over photos without a scrim breaks rule 15. Without real photography, leave labeled slots and list the shots needed.
- **Saturation:** low
- **Repo resources:** `design-systems/brand-systems/tesla/`, `design-systems/brand-systems/spacex/`, `design-systems/brand-systems/airbnb/`, `core-design/impeccable/reference/brand.md` (Imagery section)

### Retro computing
- **Lineage:** The first mass-market graphical interfaces: the 1984 Macintosh, with Susan Kare's icons drawn on 32x32 grids and her Chicago system font [S17], then Windows 95 chrome; revived on the web as nostalgia.
- **Real references:** Kare's Macintosh icons and fonts [S17]; Windows 95; Poolsuite FM's classic Mac OS style web player.
- **Fits:** Developer tools with humor, indie software, retro games, music players, personal sites, launches that celebrate a long product history. Fails: enterprise trust, healthcare, audiences too young to remember unless the play is explicit; window chrome around everything wastes mobile space.
- **Signature moves:** Type: bitmap or system-like fonts for chrome and labels only, a modern text face for reading; color: platinum grays, black, white and one highlight; layout: windows, title bars, menus and dialogs that actually work; imagery: 1-bit icons and dithered pictures; motion: instant state changes and window zooms.
- **Token sketch:** Type class: bitmap display plus readable sans; palette: system grays plus one highlight from the brand; radius: 0 or tiny; density: medium.
- **Slop risk:** Fake window chrome (three traffic-light dots) wrapped around marketing text, and bitmap fonts in body copy. Chrome must function (close, drag, menus), body text stays legible, and icons come from one family (rule 12).
- **Saturation:** low
- **Repo resources:** `design-systems/brand-systems/vintage/` (thin tokens), `templates/html-ppt/assets/themes/retro-tv.css`

### Pixel
- **Lineage:** Arcade and console graphics built from tiles and sprites, from Namco's Pac-Man (1980) and Nintendo's Famicom (1983), kept alive by indie games.
- **Real references:** Pac-Man and early Nintendo sprites; indie games such as Stardew Valley (2016) and Celeste (2018).
- **Fits:** Games, game tooling, retro hardware, playful developer communities, kids' coding. Fails: anything that must signal trust or premium; pixel fonts at small sizes fail legibility.
- **Signature moves:** Type: pixel display at integer scales only, readable sans for text; color: limited palettes of 8-16 colors with strong contrast; layout: tile grids, chunky borders, dialog boxes; imagery: sprites and tilesets drawn on a grid and rendered with `image-rendering: pixelated`; motion: frame-stepped sprite animation with `steps()`.
- **Token sketch:** Type class: pixel display plus sans text; palette: limited indexed set with one brand accent; radius: 0 or stair-stepped; density: medium.
- **Slop risk:** Blurry art scaled by fractions, pixel fonts in paragraphs, and emoji sprites (rule 12). Scale by whole numbers, keep text readable, and draw or license one coherent sprite set.
- **Saturation:** low
- **Repo resources:** `design-systems/brand-systems/pacman/`, `design-systems/brand-systems/tetris/`, `templates/gamified-app/`, `core-design/ui-ux-pro-max/data/styles.csv` (row "Pixel Art")

### Skeuomorphic
- **Lineage:** Interfaces imitating physical objects, peaking in early iOS with leather, felt and paper textures, which iOS 7 (2013) left behind for flat UI [S18].
- **Real references:** iOS 6-era Game Center felt, the Notes legal pad and the iPad Calendar's leather; audio plugins that model hardware knobs and meters.
- **Fits:** Music and audio tools, instruments and calculators, games, products whose users know the physical device (cameras, synths, mixers), nostalgia campaigns. Fails: data-dense apps, accessibility-first services, anything where texture slows comprehension.
- **Signature moves:** Type: system faces, engraved or embossed only on hardware-style labels; color: material colors (metal, wood, paper) with clear contrast; layout: controls placed as on the physical device; imagery: rendered or photographed materials under one light source; motion: physical behavior, knobs that rotate and switches with inertia.
- **Token sketch:** Type class: neutral sans; palette: material-derived neutrals plus one indicator color; radius: matched to the real object; density: medium.
- **Slop risk:** Random gradients and shadows that fake depth without one light source, and skeuomorphic and flat controls mixed without logic. Pick one light direction and one material system, and keep focus and states visible (rule 19).
- **Saturation:** low
- **Repo resources:** `design-systems/brand-systems/skeumorphism/` (folder spelled this way; thin tokens), `core-design/ui-ux-pro-max/data/styles.csv` (row "Skeuomorphism")

### Frutiger Aero
- **Lineage:** A name coined in 2017 by Sofi Lee (now Sofi Xian) at the Consumer Aesthetics Research Institute for the glossy, nature-meets-technology look of roughly 2004-2013, after the Frutiger typeface and Windows Aero; it returned as an internet nostalgia aesthetic around 2023 [S19][S20].
- **Real references:** Windows Vista and Windows 7 Aero glass; the era's stock imagery of bubbles, sky and grass; CARI's archive entry [S19].
- **Fits:** Nostalgia campaigns, music and fashion projects for people who grew up with it, playful water, weather or outdoor products. Fails: serious B2B and anything that must look current; the gloss reads dated unless the intent is obvious.
- **Signature moves:** Type: humanist sans, clean and friendly; color: sky blue, aqua, fresh green, white highlights; layout: rounded glossy panels with reflections; imagery: water, bubbles, fish, grass, sunlit sky, glossy 3D icons; motion: soft float or shimmer on one hero element.
- **Token sketch:** Type class: humanist sans; palette: blue-green family with one brand accent and white highlights; radius: medium to large, one scale; density: low to medium.
- **Slop risk:** Gloss and blur on every component turns into glassmorphism slop (rule 13), and text on busy nature photos fails contrast (rule 15). Spend the gloss on one signature element and keep surfaces flat and legible.
- **Saturation:** low
- **Repo resources:** none (closest tokens: `design-systems/brand-systems/glassmorphism/`)

### Y2K
- **Lineage:** Late-1990s to early-2000s techno-optimism: translucent plastic hardware, chrome type, rave and game graphics; revived by fashion and music around 2020.
- **Real references:** Apple's Bondi Blue iMac G3 (1998); The Designers Republic's graphics for the Wipeout games and Warp Records; the original Mac OS X Aqua interface.
- **Fits:** Fashion, music, youth brands, festivals, consumer tech launches with a playful edge. Fails: trust-heavy categories (finance, health, B2B) and long reading, since chrome and gloss hurt legibility.
- **Signature moves:** Type: wide or extended display, techno and blobby letterforms for display only; color: chrome silver, iridescent pastels, electric blue, translucent tints; layout: floating objects, capsules, layered translucency; imagery: chrome objects, device renders, low-poly 3D; motion: finite spins and shimmer on hero objects.
- **Token sketch:** Type class: extended display plus clean sans; palette: silver neutrals plus one saturated brand color; radius: large capsule, one scale; density: low to medium.
- **Slop risk:** Chrome gradient text everywhere (rule 13) and stacked sparkle stickers. Put the chrome into one rendered object or the wordmark and keep UI type flat and solid.
- **Saturation:** medium
- **Repo resources:** `templates/html-ppt/assets/themes/y2k-chrome.css`, `core-design/ui-ux-pro-max/data/styles.csv` (row "Y2K Aesthetic")

### Vaporwave
- **Lineage:** An internet music and art movement of 2010-2012, with Daniel Lopatin's "Chuck Person's Eccojams" and James Ferraro's "Far Side Virtual" as precursors and Macintosh Plus's "Floral Shoppe" (December 2011, by Vektroid) as the defining release [S21].
- **Real references:** the "Floral Shoppe" cover (marble bust, pink grid, Japanese text) [S21]; late-1990s Windows and Mac UI fragments; the mall and corporate stock imagery the movement satirized.
- **Fits:** Music, art projects, parody, merch, cultural commentary. Fails: any brand that wants to be taken at face value; the look is ironic by origin and turns sincere brands into jokes.
- **Signature moves:** Type: Windows-era system fonts and full-width characters as texture; color: pastel pink, cyan and purple; layout: floating windows, grids receding to a horizon, classical busts; imagery: marble statues, palms, early 3D renders, VHS artifacts; motion: slow loops and tracking glitches.
- **Token sketch:** Type class: system sans plus display; palette: pink, cyan and purple, one of them the action color; radius: 0 or classic window chrome; density: low.
- **Slop risk:** Using it sincerely for a SaaS product, and decorative Japanese text that says nothing (rule 2). Use it only when the irony is the point and the audience is in on it.
- **Saturation:** low
- **Repo resources:** `templates/html-ppt/assets/themes/vaporwave.css`, `core-design/ui-ux-pro-max/data/styles.csv` (row "Vaporwave")

### Flat
- **Lineage:** Rooted in Swiss modernism, formalized by Microsoft's Metro language (the Zune in 2006, Windows Phone 7 in 2010) and mainstreamed by Apple's iOS 7 in 2013 [S18].
- **Real references:** Windows Phone 7 and its Metro tiles, iOS 7, Android's move toward flat surfaces [S18].
- **Fits:** Utility apps, cross-platform products, dashboards, public services, anything that needs speed and clarity on small screens. Fails: brands that need richness or desire; total flatness hides what is clickable.
- **Signature moves:** Type: clean sans with clear weights; color: solid fills, bright but limited; layout: grids of tiles and blocks; imagery: simple icons and flat illustration; motion: quick fades and slides that explain state.
- **Token sketch:** Type class: neutral sans; palette: neutral plus one accent, semantic colors only for states; radius: small, one value; density: medium.
- **Slop risk:** Buttons that do not look pressable and equal tiles everywhere (rule 7). Keep affordances visible through fills, borders or contrast, and size tiles by importance.
- **Saturation:** medium
- **Repo resources:** `design-systems/brand-systems/flat/` (thin tokens), `core-design/ui-ux-pro-max/data/styles.csv` (rows "Flat Design", "Flat Design Mobile (Touch-First)")

### Material
- **Lineage:** Google's Material Design, announced at Google I/O on June 25, 2014 under Matías Duarte [S22]; Material You (Material 3) arrived in 2021 with wallpaper-derived themes, and Material 3 Expressive in May 2025 [S23].
- **Real references:** Android and Google Workspace apps; the official Material 3 web components (`@material/web`).
- **Fits:** Android apps, Google-ecosystem integrations, admin panels and productivity tools that gain from a complete, accessible component system. Fails: brand marketing that must not look like a Google product; untouched Material reads as a template.
- **Signature moves:** Type: role-based scale (display, headline, title, body, label); color: tonal palettes generated from one seed, tinted surfaces; layout: layered surfaces, cards, navigation rail or bar, floating action button; imagery: product UI and illustration; motion: container transforms and shared-axis transitions that explain hierarchy.
- **Token sketch:** Type class: system sans with role-based sizes; palette: one brand seed generating tonal roles; radius: shape scale by component size; density: medium, adjustable.
- **Slop risk:** Default Material (the baseline purple seed, untouched shapes) is the "default state" rule 5 forbids. Use the official package, seed it from the brand, and customize shapes and type roles.
- **Saturation:** medium
- **Repo resources:** `design-systems/brand-systems/material/`, `core-design/design-taste-frontend/SKILL.md` (section 2.A and Appendix A install commands), `core-design/ui-ux-pro-max/data/styles.csv` (row "Material You (MD3 Mobile)")

### Corporate Memphis
- **Lineage:** Flat vector people with big limbs and small heads, spread across tech after Facebook introduced its Alegria illustration system, made by the studio Buck with illustrator Xoana Herrera, in 2017; named as a jab at the Memphis Group and widely criticized as featureless and interchangeable [S24].
- **Real references:** Facebook's Alegria system and the many 2018-2021 startup sites that copied it [S24].
- **Fits:** Rarely: neutral human figures for public-service explainers or internal training, redrawn by a real illustrator in the brand's own style. Fails: nearly every brand page; it now signals a template and sanitized tech optimism.
- **Signature moves:** Type: friendly geometric sans; color: flat pastels with saturated purple-blue; layout: hero illustration of people collaborating beside a headline; imagery: faceless figures with exaggerated proportions; motion: looping vector animations.
- **Token sketch:** Type class: geometric sans; palette: flat pastel set; radius: large; density: low.
- **Slop risk:** It is the slop: illustration that restates the copy and shows no real customer (rules 2 and 6). If people must appear, use real photography or a commissioned style tied to the brand.
- **Saturation:** high
- **Repo resources:** none

### Glassmorphism
- **Lineage:** Translucent blurred panels from Windows Vista's Aero through iOS 7's blur (2013) to macOS Big Sur (2020), the year Michal Malewicz popularized the name [S25]; Apple's Liquid Glass, announced at WWDC on June 9, 2025, made a refracting glass material the shared language of iOS 26 and macOS Tahoe 26 [S26].
- **Real references:** macOS Big Sur system UI [S25]; Apple's Liquid Glass [S26]; Microsoft Fluent's Acrylic material.
- **Fits:** Overlays above rich imagery or live content (media players, maps, camera, spatial UI), OS-like utilities, one floating layer above a photograph. Fails: text-heavy pages, data tables, low-power devices, and flat white pages where glass has nothing to blur.
- **Signature moves:** Type: clean sans with enough weight to survive blur; color: translucent light or dark tints over vivid content; layout: floating layers with clear hierarchy, one glass level; imagery: rich photography or video beneath the glass; motion: subtle layer parallax and light that responds to movement.
- **Token sketch:** Type class: neutral sans, medium weight minimum; palette: translucent neutral surfaces plus one accent, with solid fallbacks; radius: medium to large, concentric; density: low to medium.
- **Slop risk:** A glass nav and glass cards on a purple-blue blob background is the 2024-2026 generator default, and blur erodes contrast (rule 15). Use glass only where content passes beneath it, provide solid fills under `prefers-reduced-transparency`, and test text contrast on the worst frame.
- **Saturation:** high
- **Repo resources:** `design-systems/brand-systems/glassmorphism/` (thin tokens), `templates/html-ppt/assets/themes/glassmorphism.css`, `core-design/design-taste-frontend/SKILL.md` (Appendix C, honest Liquid Glass approximation), `core-design/ui-ux-pro-max/data/styles.csv` (rows "Glassmorphism", "Liquid Glass")
