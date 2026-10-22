# MB-System-SVP-tools

Four complementary tools for supporting sound-speed profile (SVP) assessment, extraction, evaluation and assignment in MB-System workflows.

- **`mbsvplocation` — Identify suitable analysis locations.** Examines multibeam data in analysis windows, using geometric and quality metrics to identify suitable sections and flag systematic distortion that may warrant SVP investigation.
- **`mbsvpbest` — Compare candidate profiles.** Evaluates WOA-derived and embedded SVPs by reprocessing multibeam data and ranking bathymetric residuals, with comparison reports and an option to apply the best-ranked profile.
- **`mbsvproute` — Extract profiles along a route.** Reads survey locations from an MB-System `.ste` file and extracts annual-average WOA18 or WOA23 profiles using Chen or Leroy calculations, with profile completion to 11,000 m and provenance reporting.
- **`mbsvpnearest` — Assign profiles by proximity.** Matches multibeam files to existing SVPs using their WOA grid-cell locations and optionally updates MB-System parameter files with the selected profile assignments.
