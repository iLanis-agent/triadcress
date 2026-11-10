# Triadcress 1.0 TEST
Native Android four-feature triple-recognition puzzles. Android8+ min26/target35. Package com.gg007.triadcress.

## Rules
Known all-same/all-different triple-recognition adaptation. Nine distinct cards each show four independent attributes: count 1/2/3; circle/square/triangle; cyan/gold/white; open/striped/solid. Choose exactly three cards. For EACH attribute separately, the values must be all the same or all different. Two alike and one different fails. Every hand has exactly one valid triple. Tap a selected card again to deselect; no fourth selection. Tap CHECK THREE explicitly. Undo/reset, twelve hands, saved palette and optional feature labels. Labels show count/shape/color/fill; C/S/T shapes, C/G/W colors, O/H/F fills. This is a fixed-hand solo puzzle, not the commercial multiplayer dealing/scoring game.

## Download and status
https://mega.co.nz/#!VQ9AyQ4K!FPXG_p_8ysIw84UV-djRxvCZHYxkxug-96KMYHjZpQM
APK 20974 bytes; SHA256 7514dda43e0641f8f05808bb186a3b4a52f8b43a611f48ac814be1436c9cb914. Original certificate SHA2561651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. No requested permissions; original GG007 icon unchanged. Anonymous downloaded bytes match.

## Checks
Seed901110 generates twelve distinct nine-card hands, each with exactly one valid triple among84. Independent direct equality/distinctness oracle compared with production base-three modular sums for all614125 ordered triple/range cases, including repeated cards and invalid IDs;6480 accepted ordered triples equal1080 unordered triples. All6168 board-mask/invalid comparisons passed. Selection limit, deselection, explicit check, bounds, incomplete selections, solved locks, undo/reset pass. All12 actual drawing-adapter card/card/card/check tap-solves pass; wrong triples, menus/privacy/next/levels/saved palette/feature labels/completion pass. Eight drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
All221 prior studio and803 legacy descriptions reviewed. Mastermind tests a hidden code with positional feedback; Pairbloom/Binarybrook balance whole lines; Chromaring colors graph neighbors differently. Triadcress instead selects an unordered triple from a visible ternary attribute deck, applying an independent all-equal/all-distinct test to all four features. No matching factory mechanic found. Known SET-style concept, not globally new; no commercial affiliation. Original seeded hands, code and geometric artwork, not copied card art/layouts/equations. Six fully read sources: publisher, MAA, AMS, MathWorld, independent rules guide and ScienceNews. Stable rule consensus used; historical invention dates, neuroscience claims, prices and setless-hand probabilities are not used.

## Build and tests
JDK17/AndroidSDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/triad-test src/com/gg007/triadcress/Board.java BoardTest.java then java -Xmx256m -cp /tmp/triad-test com.gg007.triadcress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your private signing material. No signing secret included. adapter/android contains the Java2D drawing adapter used with TriadAdapterTest.java, not an Android runtime.

## Privacy and branding
Triadcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, feature labels and solved-hand marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 menu, original icon, studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative222-card studio and publishing fragments privately preserved:
https://files.instinct.com/mtqj341nvqtq-triadcress-source-archive
https://github.com/iLanis-agent/triadcress holds README only, full Git source pending. Existing three studio includes and Pages settings untouched. Both sites verified separately.

## Rule sources
https://www.playmonster.com/product/set/
https://maa.org/math-values/on-your-mark-get-set-geometry/
https://www.ams.org/publicoutreach/feature-column/fc-2015-08
https://mathworld.wolfram.com/SETGame.html
https://www.ultraboardgames.com/set/game-rules.php
https://www.sciencenews.org/article/set-math
