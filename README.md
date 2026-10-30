# Interaktiv frekvensomformer

En dansksproget undervisningsanimation til maskinmesterstuderende. Viser en trefaset frekvensomformer med 3 × 400 V / 50 Hz forsyning.

## Funktioner

- **Ensretter:** trefaset B6-diodebro med spændings- og strømkurver.
- **Mellemkreds:** DC-reaktor og kondensator, spænding før og efter udglatning.
- **Inverter:** IGBT-bro, sinus-PWM, justerbar udgangsfrekvens (0–100 Hz), spænding (0–400 V, ønsket fase-fase RMS), PWM-frekvens og tidszoom.
- **Samlet system:** overblik over omformeren og asynkronmotoren.
- **Slipkompensering:** principillustration med belastningsskyder og mulighed for at aktivere kompensation.
- Pause, trinvis fremføring, justerbar animationshastighed, valg af spændingsreference og FFT på inverterfanen.

> **Undervisningsmodel:** DC-filter, motorstrømme og slipkompensering er forenklede principmodeller. FFT og kurver er ikke beregnet til præcis dimensionering eller kvantitativ harmonisk analyse. Den ønskede udgangsspænding kan være begrænset af DC-mellemkredsen og sinus-PWM.

## Brug lokalt

Åbn `index.html` i en moderne browser. Ingen installation eller eksterne biblioteker er nødvendige.

## Udgiv på GitHub Pages

1. Opret et nyt repository på GitHub, f.eks. `frekvensomformer`.
2. Upload **indholdet** af denne mappe til repositoryets rod (især `index.html`).
3. Åbn **Settings → Pages**.
4. Under **Build and deployment**: vælg **Deploy from a branch**.
5. Vælg branch **main**, folder **/(root)** og klik **Save**.
6. Når udgivelsen er færdig, viser GitHub Pages linket på samme side.

For et repository kaldet `frekvensomformer` vil adressen typisk have formen `https://BRUGERNAVN.github.io/frekvensomformer/`.

## Vedligeholdelse

Opdatér `index.html` i repositoryet og commit ændringen. GitHub Pages offentliggør normalt automatisk den nye version efter kort tid.

## Teknologi

Ren HTML, CSS, SVG, Canvas og JavaScript. Ingen buildproces.
