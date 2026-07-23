# FireServicesExam

A multiple-choice quiz app for T&T Fire Service entrance exam practice (Math, English, General Knowledge).

- The actual app (UI, logic, and all 120 questions) lives in: `www/index.html`
- Questions/answers are inside that file's `<script>` section, in a JavaScript object called `QUESTION_BANKS`
- `package.json`, `capacitor.config.json`, and `.github/workflows/build-apk.yml` are just the wrapper that lets GitHub Actions compile this into an Android .apk automatically

See HOW-TO-BUILD-APK.md (provided separately in chat) for setup steps.
