# Strait of Hormuz Energy Security Study - Reviewer Package

Peer-review package for: The Strait of Hormuz and Global Energy Security: Geopolitical Tensions, Maritime Trade, and the Risk of Supply Chain Disruption

Contains:
- final/ : manuscript (markdown, PDF, LaTeX, DOCX), references.bib, figures
- datasets/ : raw + cleaned data with checksums (datasets/manifest.json) and cleaning scripts
- analysis/reanalysis/ : machine-readable results (findings_reanalysis.json, findings_extended.json, findings_robustness.json, findings_eventlevel.json) and reports
- experiments/ : all analysis scripts
- verification/ : citation verification, peer-review response record, issues audit

Run: python experiments/hormuz_reanalysis.py (core), hormuz_reanalysis_extended.py (supplementary), hormuz_robustness.py (robustness), hormuz_eventlevel.py (event-level).

