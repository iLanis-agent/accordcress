# Accordcress 1.0 TEST
Native Android stable matching preference puzzle. Android8+ min26/target35. Package com.gg007.accordcress.

## Rules
Known stable matching adaptation with two abstract groups, A-D and 1-4. Pair each letter with one different number. Every preference list is strict and complete, best on the left. An unpaired letter and number form a blocking pair only when BOTH rank each other above their assigned partners. A complete bijection wins when no blocking pair exists. This is not a maximum rank-sum problem. Select a letter, then assign a number. Assigning a used number clears its old letter; CLEAR removes the selected assignment. CHECK STABILITY explicitly, undo/reset, twelve original instances and saved palette/optional partner guides. Each generated instance has exactly one stable matching, verified by enumeration, not a claim about all instances.

## Download and status
https://mega.co.nz/#!YM9xACKJ!ek79RHJpRkL-FXp4TOJBT77mzZPyK9ocyO4jgksIgYI
APK 20974 bytes; SHA256 a03e90fdf756c287f46cb0f89713e286442ab873ac7aa01b3bf0b7f6f6214386. Original certificate SHA2561651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. No requested permissions; original GG007 icon unchanged. Anonymous downloaded bytes match.

## Checks
Seed 931110 generates twelve distinct strict preference instances with twelve different unique solutions among 24 bijections each. An independent list-walking blocking-pair oracle compares 15552 assignments including blanks/out-of-range/duplicates (all 6^4 per level) against production inverse-rank checking. All 288 complete bijections checked. Independent deferred acceptance from BOTH proposing sides returns the enumerated unique answer for all 12 instances. Bounds, incomplete entries, explicit check, solved locks, assignment stealing, clear, undo/reset pass. All 12 actual drawing-adapter letter/number/check tap-solves pass; menus/privacy/next/levels/saved palette/partner guides/completion pass. Eight drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
All 224 prior studio and 803 legacy descriptions reviewed. Linkcress pairs geometric circles with noncrossing lines; FairChore minimizes total assigned cost; Rankcress reconstructs permutation smaller-right counts. Accordcress instead checks reciprocal ordinal preferences for every unmatched cross-group pair. No matching factory mechanic found. Known stable matching problem, not globally new. Original seeded preference tables, native code and preference illustration. Six fully read reference, educational and software documentation pages support the definition and proposal/rejection oracle. Multiple stable matchings can exist in general: uniqueness here is established only for these twelve tables by complete enumeration. No real-life fairness, truthful reporting, historical or complexity claims used. One educational page misattributes a Nobel award and differs on runtime; these peripheral claims are not used.

## Build and tests
JDK17/AndroidSDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/accord-test src/com/gg007/accordcress/Board.java BoardTest.java then java -cp /tmp/accord-test com.gg007.accordcress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your private signing material. No signing secret included. adapter/android contains the Java2D drawing adapter used with AccordAdapterTest.java, not an Android runtime.

## Privacy and branding
Accordcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, partner guides and solved-puzzle marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 menu, original icon, studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative225-card studio and publishing fragments privately preserved:
https://files.instinct.com/osi8eett9cyi-accordcress-source-archive
https://github.com/iLanis-agent/accordcress holds README only, full Git source pending. Existing three studio includes and Pages settings untouched. Both sites verified separately.

## Rule sources
https://mathworld.wolfram.com/StableMarriage.html
https://daffidwilde.github.io/matching/docs/discussion/stable_marriage.html
https://algorithms.alexli.ca/stable-marriage-gale-shapley/
https://www.neeldhara.com/materials/dsanotes/stable-matchings/
https://www.cs.cornell.edu/~rafael/networks-html/chapter14.html
https://cs4261.devanshshah.dev/stable-matchings
