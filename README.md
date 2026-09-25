# Looncontrole — PC 302 Student

Een volledig client-side looncontroletool voor GitHub Pages.

## Gebruik
1. Upload `index.html` naar een GitHub repository.
2. Zet GitHub Pages aan via **Settings → Pages → Deploy from branch**.
3. Open de gepubliceerde pagina.
4. Vul je gewerkte uren, pauzes, overuren, zondag/nachturen en onkosten in.
5. Vergelijk het resultaat met je loonbrief.

## Standaardwaarden
De standaardwaarden zijn gebaseerd op de aangeleverde contract- en loonbrieven:
- bruto uurloon: €15,97
- overuren 150%: €23,955/u
- overuren 200%: €31,94/u
- zondagpremie: €2,00/u
- kledijvergoeding: €2,20/dag
- studentenbijdrage: 2,71% (afgeleid uit de aangeleverde loonbrieven)
- overuren vanaf 11 effectieve werkuren per dag

Controleer altijd je eigen loonbrief/contract wanneer tarieven veranderen.

## Privacy
Alles draait lokaal in je browser. Er is geen backend en er worden geen gegevens naar een server gestuurd. De knop Opslaan gebruikt alleen localStorage van je browser.
