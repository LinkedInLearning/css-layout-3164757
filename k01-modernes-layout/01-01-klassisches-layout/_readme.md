# Projektdateien für 3164757 Webtechniken lernen 3: CSS-Layout (2023) 

Basis sind die Übungsdateien aus dem Buch »Einstieg in HTML und CSS« (2. Auflage, 2022)


## Änderungen in den Übungsdateien für 01-01-klassisches Layout 

### HTML
durchgehende Einrückung mit 2 Leerzeichen 


### CSS 
Namen der Stylesheets wie im Buch (nicht wie im Videokurs)
- inhalte.css => content.css 
- formulare.css => forms.css 

basis.css 
Bug aus Übungsdateien V1.0 behoben (Semikolon statt Komma): 
img, video { max-width: 100%; height: auto; } 

layout.css 
body hat margin: 0 auto (statt 0.25rem auto)

navi-inline.css 
Unterstreichung der Links für .current a, .site-nav a:hover und .site-nav:focus 

content.css 
Farbe #666 statt gray
.beitragsinfo { color: #666; } 

forms.css 
enthält das CSS aus formulare.css (Challenge/Solution, K07, Videokurs Teil 2 (2022)) 
Fine-Tuning: 
- label: alle = cursor:pointer; nur div > label = display: block (nicht DSGVO)
- border für Eingabefelder: dimgrey => #333 
- min-width für Input-Felder und Button: 16rem => 18rem 
- max-width für textarea: 25rem => 30rem


-- eof -- 