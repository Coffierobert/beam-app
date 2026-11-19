# Data

Store project data files here. Current beam-section catalogs:

- `aisc-w-shapes-v16.json` contains the 289 AISC W-shapes in Shapes Database
  v16.0, including weight, dimensions, strong-axis `Ix`, and `Sx`. Its source
  and units are recorded in the file.
- `lumber-2x-sections.json` contains geometry for common 2x4 through 2x12
  sawn-lumber sections. `Ix` and `Sx` are calculated from actual dimensions.

The lumber file does not include species/grade-specific modulus or allowable
stress. Those values must come from a verified, applicable design-values
source; section geometry by itself is not a strength rating.
