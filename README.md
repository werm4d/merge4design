M4D Website — Project Image Manifest
Sources in OneDrive under 00_M2-README_START-HERE/10_LANE/ — card images from M2_2026-PROJECTS/M2_2026_014_FORWARD-HOUSING-DEVELOPMENT/ARCHIVE; feature image from 02_2025-PROJECTS/AE24-002_CLAYMONT/A_ADMIN/A6_MARKETING
Source file	Target path (this folder)	Used by
The Forward Home by LEEP.jpg (AE24-002_CLAYMONT/A_ADMIN/A6_MARKETING)	claymont-forward-home.jpg	Featured — Claymont (4.7MB source — resize required)
38E-23RD-STREET.png	soulfully-conscious.png	Card — Soulfully Conscious
LAMOTT-DAYCARE.png	lamott-daycare.png	Card — LaMott Daycare
Bench inventory for future rotation (already in ARCHIVE): 2026-05-22-26-Exterior-Front2.jpg, 2026-05-21-26-Interior-Main.jpg,
2026-05-22-26-Roof-Main.jpg, Screenshot_Bennett-FRNT.png, CHESTER.png / CHESTER-II.png,
N-MARKET.png.
Optimization (before committing)
Target ~1600px wide, JPEG quality ~80, under 400KB each. PowerShell (run in this folder):
magick claymont-forward-home.jpg -resize 1600x -quality 80 claymont-forward-home.jpg
(If ImageMagick isn't installed: right-click > Open with Photos > Resize image > Custom 1600px.)
Rotating the feature
In index.html, the featured block is marked with the comment
"FEATURED PROJECT — to rotate the feature". Swap its content with any work-card;
the feature block adds a specs grid and location line — fill those when promoting a card.
