# Layout outline voor https://www.drieklomp.nl/woningen/nieuwe-fluitersmaatscheweg-20-renkum/

## Globale structuur
- Header / navbar: fixed top, full-width bar met container-fluid; linker kolom hamburger, links hoofdmenu, gecentreerd logo, rechts extra menu/dropdowns.
- Hero media: direct onder navbar een fotomosaiek; grote hoofdafbeelding links, rechts een kolom met één middelgrote foto boven en twee kleine foto’s onder (laatste met “+ aantal” overlay); statusbadge bovenop.
- Detail header: blok met adres/prijs/metadata onder de galerij; daaronder een horizontale anchor-balk met links naar Omschrijving, Kenmerken, Media, Brochure, Plattegronden, 360, Video.
- Omschrijving + contact: sectie met twee kolommen (ca. 8/12 tekst met inklapbare omschrijving, 4/12 zijbalk met kantoorinfo, CTA “Plan een bezichtiging”, award, share-icoontjes).
- Highlights: grid met kengetallen (oppervlakte, inhoud, perceel, kamers, slaapkamers, energielabel) in kolommen (md: 2 per rij, lg: 3 per rij, xl: 6 per rij).
- Kenmerken: lijstsectie met headings (Algemeen, Oppervlakten en inhoud, etc.); onder elke heading rijen met label/waarde in een interne 2-koloms row (label ±1/3, waarde ±2/3).
- Media gallery: volledige breedte container met titel “Media” en grid van thumbnails (lg: 4 per rij, md: 2 per rij, mobiel: 1), elk linkt naar modal/slider.
- Kaart: blok met titel “Kaart” en één kaartafbeelding met overlaybutton “Bekijk op kaart”, linkt naar Google Maps.
- Form CTA: afsluitende CTA-sectie, gecentreerd (titel + enkele knop “Schrijf u in als zoeker!”).
- Footer: container met gecentreerd logo en verdere footerinhoud (niet uitgewerkt in deze snapshot).

## Per sectie

### 1. Header / navbar
- Positie: fixed bovenaan.
- Layout: container-fluid met een row; kolommen voor hamburger, links menu-items, centraal logo, rechts dropdowns/extra menu.
- Mobile: hamburger open/close het menu; menu-items onder elkaar.
- Breedte: full-width achtergrond, inhoud fluid grid.
- Verticale spacing: compacte navbar hoogte.

### 2. Hero media (fotomosaiek)
- Positie: direct onder de navbar en actiebar.
- Layout: 2-koloms grid; links grote foto, rechts een kolom met boven een middelgrote foto en onder twee kleine foto’s naast elkaar, laatste met “+ meer” overlay; statusbadge overlay op grote foto.
- Mobile gedrag: stacked (grote foto boven, overige foto’s eronder).
- Breedte: container, volledige breedte binnen grid.
- Verticale spacing: standaard sectiepadding boven/onder.

### 3. Detail header + anchor navigation
- Positie: na de media.
- Layout: adres/plaats/prijsblok in één kolom binnen container; direct gevolgd door horizontale lijst met anchor-links (Omschrijv­ing, Kenmerken, Media, Brochure, Plattegrond, 360, Video).
- Mobile: anchors als horizontale scrollbare/gestapelde lijst.
- Verticale spacing: normale padding; anchorbar compact.

### 4. Omschrijving + contact
- Positie: onder de anchorbar.
- Layout: twee kolommen; linker kolom (ca. 8/12) met titel “Omschrijving”, paragraaftekst en “Lees de volledige omschrijving” toggle; rechter kolom (ca. 4/12) met contactkaart (kantoorinfo, telefoon/e-mail, CTA “Plan een bezichtiging”, awardbeeld en shareknoppen).
- Mobile: kolommen gestapeld (eerst omschrijving, dan contact).
- Verticale spacing: royale sectiepadding.

### 5. Highlights (kengetallen)
- Positie: na omschrijving/contact.
- Layout: grid van highlight-kaarten; elke kaart icon + label + waarde.
- Desktop: 6 kolommen op xl (col-xl-2), 3 op lg, 2 op md, 1 op mobiel.
- Verticale spacing: standaard sectiepadding; cards met interne padding.

### 6. Kenmerken (detailtabel)
- Positie: onder highlights.
- Layout: heading “Kenmerken”, gevolgd door categorie-headings; per categorie een lijst van rijen, elke rij een kleine 2-koloms verdeling (label ±1/3, waarde ±2/3).
- Mobile gedrag: rijen blijven per regel, maar label/waarde breken onder elkaar indien nodig.
- Breedte: container.
- Verticale spacing: ruime marge tussen categorie-headings en rijen; extra “Bekijk alle kenmerken” toggle onderaan.

### 7. Media gallery
- Positie: na kenmerken.
- Layout: titel “Media” boven een thumbnails-grid; kaarten links naar modale slider.
- Desktop: 4 kolommen (lg), md: 2 per rij, mobiel: 1 per rij; kleine gutters.
- Verticale spacing: standaard sectiepadding.

### 8. Kaart
- Positie: na media.
- Layout: titel “Kaart” + één kaartafbeelding met overlaybutton “Bekijk op kaart”.
- Mobile: afbeelding volle breedte.
- Verticale spacing: standaard sectiepadding.

### 9. Form CTA
- Positie: vlak boven de footer.
- Layout: gecentreerde titel en één prominente knop; enkelkoloms binnen container.
- Verticale spacing: royale top/bottom padding.

### 10. Footer
- Positie: onderaan de pagina.
- Layout: container met gecentreerd logo (verdere kolommen niet zichtbaar in snapshot); border-top/bottom accent.
- Mobile: elementen gestapeld/centraal.
- Verticale spacing: ruime padding rond logo en footerinhoud.
