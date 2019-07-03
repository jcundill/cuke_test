# cuke_test
simple configuration of the cucumber.json generation for cypress-cucumber-preprocessor

```
Cudas-MBP:cuke_test jcundill$ npm install
npm WARN cuke_test@1.0.0 No repository field.

audited 9268 packages in 6.211s
found 2 low severity vulnerabilities
  run `npm audit fix` to fix them, or `npm audit` for details
Cudas-MBP:cuke_test jcundill$ npx cypress run --spec cypress/integration/BackgroundSection.feature
===================================================================================================

  (Run Starting)

  ┌───────────────────────────────────────────────────────────────────────────────────────────────┐
  │ Cypress:    3.3.2                                                                             │
  │ Browser:    Electron 61 (headless)                                                            │
  │ Specs:      1 found (BackgroundSection.feature)                                               │
  │ Searched:   cypress/integration/BackgroundSection.feature                                     │
  └───────────────────────────────────────────────────────────────────────────────────────────────┘


───────────────────────────────────────────────────────────────────────────────────────────────────

  Running: BackgroundSection.feature...                                                   (1 of 1)


  Background Section
    ✓ Basic example #1 (130ms)
    ✓ Basic example #2 (52ms)


  2 passing (353ms)


  (Results)

  ┌─────────────────────────────────────────┐
  │ Tests:        2                         │
  │ Passing:      2                         │
  │ Failing:      0                         │
  │ Pending:      0                         │
  │ Skipped:      0                         │
  │ Screenshots:  0                         │
  │ Video:        true                      │
  │ Duration:     0 seconds                 │
  │ Spec Ran:     BackgroundSection.feature │
  └─────────────────────────────────────────┘

  - Started processing:   Compressing to 32 CRF
  - Finished processing:  /Users/jcundill/code/cuke_test/cypress/videos/BackgroundSection.feature.mp4 (1 second)


===================================================================================================

  (Run Finished)


      Spec                                               Tests  Passing  Failing  Pending  Skipped
  ┌───────────────────────────────────────────────────────────────────────────────────────────────┐
  │ ✔ BackgroundSection.feature                352ms        2        2        -        -        - │
  └───────────────────────────────────────────────────────────────────────────────────────────────┘
    All specs passed!                          352ms        2        2        -        -        -

Cudas-MBP:cuke_test jcundill$ ls -al cypress/my-cucumber-files/
total 8
drwxr-xr-x  3 jcundill  staff    96  3 Jul 21:58 .
drwxr-xr-x  8 jcundill  staff   256  3 Jul 21:53 ..
-rw-r--r--  1 jcundill  staff  1920  3 Jul 22:03 TEST--cucumber--BackgroundSection--A.json
Cudas-MBP:cuke_test jcundill$
```
