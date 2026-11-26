# stratios-map

Δεδομένα χάρτη (OpenStreetMap) για την περιοχή από τους Ευζώνους (σύνορα) έως το Κιλελέρ / Μοσχοχώρι Λάρισας:
Κιλκίς, Θεσσαλονίκη, Ημαθία, Πιερία, Λάρισα.
Πλαίσιο: δυτικά 22.05, νότια 39.35, ανατολικά 23.00, βόρεια 41.15 — μέγιστο zoom 15.

Το αρχείο PMTiles είναι σπασμένο σε κομμάτια του 1 MB (`region-000.bin` …) και περιγράφεται στο `region.json`.
Από την έκδοση v3 τα κομμάτια μοιράζονται σε δύο tags (`v3`: 0–39, `v3-2`: 40 και μετά), γιατί το jsDelivr
δεν σερβίρει πακέτα πάνω από ~50 MB.

Πηγή: Protomaps basemap build 2026-11-24 (https://protomaps.com), που βασίζεται σε δεδομένα OpenStreetMap.
© OpenStreetMap contributors — Open Database License (ODbL): https://www.openstreetmap.org/copyright

Περιέχει μόνο δημόσια δεδομένα χάρτη.
