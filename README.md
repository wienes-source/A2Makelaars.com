# A2Makelaars.com

Websitebestanden voor A2 Makelaars, gericht op Aalsmeer en omgeving.

## Inhoud

- `index.html` — homepage
- `nieuws.html` — nieuws en marktinzichten
- `assets/style.css` — vormgeving en responsive layout
- `assets/script.js` — mobiele navigatie en gedrag conceptformulier

## Publiceren via Hostinger

Voor een statische HTML-site ondersteunt Hostinger Git-deployment via GitHub OAuth.

1. Open Hostinger hPanel.
2. Ga naar **Websites** en open het dashboard van `A2Makelaars.com`.
3. Ga naar **Advanced / Geavanceerd → Git**.
4. Kies **Connect with GitHub / Continue with GitHub**.
5. Autoriseer de Hostinger GitHub-app voor deze repository.
6. Selecteer repository `wienes-source/A2Makelaars.com`.
7. Selecteer branch `main`.
8. Kies de map waar de website moet worden geplaatst (voor de hoofddomeinsite doorgaans `public_html`).
9. Start de eerste deployment.
10. Schakel automatische deployments in wanneer deze optie wordt aangeboden, zodat toekomstige wijzigingen op `main` automatisch naar Hostinger gaan.

> Let op: bij de eerste Git-deployment kunnen bestaande bestanden in de doelmap worden overschreven. Maak daarom eerst een backup van de huidige `public_html`-map als daar nog bestanden staan die bewaard moeten blijven.

## Nog te configureren

- Definitieve contactgegevens
- Koppeling van het contactformulier aan een mailbox of formulierdienst
- Eventuele woning-/kavelobjecten en foto's
- Favicon en definitief logo
- Eventuele juridische pagina's (privacy/cookies)

## Status

Conceptversie — 25 september 2026.
