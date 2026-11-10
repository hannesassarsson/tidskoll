# Tidskoll

Tidslogg för en arbetsplats: ankomst, frukost, lunch och hemgång per företag och dag, med veckosammanställning och PDF-rapport.

- **Körs som artifact i Claude.** Sidan använder Claudes delade lagring och nedladdning (`claude.use("db")`, `claude.use("downloads")`) och fungerar därför inte fristående.
- `index.html` är en kopia av artifactens källkod från 2026-11-10 (613 rader).
- `vendor/jspdf.umd.min.js` och `vendor/jspdf.plugin.autotable.min.js` (jsPDF och jsPDF-AutoTable) ligger i artifacten men inte i det här repot.

Artifacten i Claude är originalet. Det här repot är en säkerhetskopia och uppdateras inte automatiskt.
