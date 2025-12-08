# Layout outline voor https://www.verhage-lemahieu.nl/

## Globale structuur
- Header / navbar: horizontale topbar met logo links, telefoonwidget, account-iconen en toggler; hoofdmenu in een centrale container met dropdowns.
- Hero: full-width slider direct onder de navbar; één grote achtergrondafbeelding met overlaytitel in container, waarschijnlijk gecentreerd/links in beeld.
- Over ons intro: container met 2 kolommen (tekstlinks, afbeelding rechts), ruime padding.
- Diensten: container met titel en een grid van 4 cards (desktop 4 naast elkaar, md 2 per rij, mobiel 1 per rij).
- Uitgelicht aanbod: sectie met titel en horizontale carousel van woningcards (afbeelding boven, data/kenmerken onder).
- Verkoop-CTA: container met 2 kolommen (tekstlinks, afbeelding rechts), vergelijkbare spacing als intro.
- Nieuwsbrief-CTA: container met logo + korte tekst en CTA-knop; elementen in een flex/blok, op mobiel gestapeld.
- Partnerlogo-slider: smalle sectie met carrousel van partnerlogo’s.
- Footer: bovenste rij met meerdere kolommen (3 menu-kolommen + contactkolom), onderste balk met copyright, social icons en subfootermenu.

## Per sectie

### 1. Header / navbar
- Positie: vast bovenaan de pagina.
- Layout: containerbreedte, logo links, telefoonwidget en account-iconen rechts van logo, vervolgens hamburger toggler; uitklapbaar hoofdmenu met meerdere dropdowns; full-width achtergrond, content begrensd tot container.
- Mobile gedrag: menu collapsed achter toggler; dropdowns uitklapbaar.
- Breedte: centrale container (typisch ~1140–1200px).
- Verticale spacing: compacte hoogte, standaard navbar-padding.

### 2. Hero slider
- Positie: direct onder de navbar.
- Layout: full-width slider met één beeld; overlaytekst binnen een centrale container.
- Desktop: afbeelding vult breedte; caption/heading in overlay (enkele kolom).
- Mobiel: afbeelding schaalt mee; caption blijft bovenop, gestapeld.
- Breedte: afbeelding full-bleed, tekst begrensd tot container.
- Verticale spacing: hoge hero-hoogte met ruime top/bottom-ruimte door de afbeelding.

### 3. Over ons (introblok)
- Positie: na de hero.
- Layout: 2 kolommen op desktop (tekst links met titel, subtitel, paragraaf, knop; afbeelding rechts). Kolommen wisselen naar stack op mobiel (eerst tekst, dan beeld).
- Breedte: content in centrale container.
- Verticale spacing: royale padding boven/onder.

### 4. Onze diensten (feature grid)
- Positie: onder het introblok, binnen main-content container.
- Layout: titel bovenaan, daaronder een row met 4 gelijkvormige cards (cta’s).
- Desktop: 4 kolommen naast elkaar; medium schermen 2 per rij; mobiel 1 per rij.
- Cardinhoud: titel en link/arrow; geen visuals in de markup.
- Breedte: container.
- Verticale spacing: normale sectie-padding.

### 5. Uitgelicht aanbod (carousel)
- Positie: na de diensten.
- Layout: sectietitel bovenaan (container), daaronder een horizontale owl-carousel met woningcards.
- Cardstructuur: afbeelding boven, daaronder adres, titel, prijs en enkele kenmerken (type, kamers, oppervlaktes).
- Desktop: meerdere cards zichtbaar naast elkaar in de carousel; mobiel: één per swipe.
- Breedte: cards en titel in container.
- Verticale spacing: standaard sectieafstand boven/onder.

### 6. Verkoop-CTA
- Positie: na de uitgelicht-carrousel.
- Layout: 2 kolommen (tekst links: subtitel, h3, tekst, knop; afbeelding rechts).
- Mobile gedrag: gestapeld (tekst boven, beeld onder).
- Breedte: container.
- Verticale spacing: ruime padding vergelijkbaar met intro.

### 7. Nieuwsbrief-CTA
- Positie: na de Verkoop-CTA.
- Layout: logo/tekstblok + knopblok binnen één container; flex-achtig op desktop, op mobiel onder elkaar.
- Desktop: logo/tekst links, knop/tekst rechts.
- Breedte: container.
- Verticale spacing: matige padding (kortere sectie dan hero/intro).

### 8. Partnerlogo-slider
- Positie: net boven de footer.
- Layout: horizontale carousel met meerdere partnerlogo’s (smalle hoogte).
- Desktop: meerdere logo’s in één rij; mobiel: minder logo’s zichtbaar per swipe.
- Breedte: full-width container.
- Verticale spacing: compacte sectie, beperkte padding.

### 9. Footer
- Positie: onderaan de pagina.
- Layout: container met bovenste grid van kolommen: drie menukolommen (Aanbod, Onze diensten, Informatie) plus een contactkolom rechts; daaronder een footerBottom-balk met copyright links en social icons + subfootermenu.
- Mobile gedrag: kolommen gestapeld; subfootermenu en socials onder elkaar.
- Breedte: container.
- Verticale spacing: standaard footer-padding, extra kleine balk voor bottom row.
