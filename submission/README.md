# Capstone Paper : CTR Opportunity Scoring

This folder marks the final submission for the FlyRank ML Internship capstone.

**Paper:** Finding the Pages That Deserve a Second Look CTR Opportunity Scoring in Search Content

**Live paper:** see `paper_url.txt`

**Summary:** This capstone builds and honestly validates a way to rank search-visible pages by how far their click-through rate falls below what similarly-ranked pages typically achieve. A position-bucket baseline is compared against a Random Forest model on a client-grouped validation split, with a leaked feature caught and removed along the way. The honest, leakage-free result is a ~10.5% reduction in prediction error over the baseline — reported deliberately as a modest, decision-support number rather than an inflated claim.

**Repo:** all notebooks, outputs, and figures behind this paper live under `work/` in this repository.
