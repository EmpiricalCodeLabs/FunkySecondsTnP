# Funky Seconds – Privacy Policy and Terms and Conditions

The public Privacy Policy and Terms and Conditions for **Funky Seconds**, a word guessing party game for Android.

**Live site:** https://empiricalcodelabs.github.io/FunkySecondsTnP/

**Google Play Console privacy policy URL:** https://empiricalcodelabs.github.io/FunkySecondsTnP/privacy/

| Document | English | Afrikaans | Nederlands | Português | Türkçe |
|---|---|---|---|---|---|
| Privacy Policy | [privacy/](https://empiricalcodelabs.github.io/FunkySecondsTnP/privacy/) | [privacy/af/](https://empiricalcodelabs.github.io/FunkySecondsTnP/privacy/af/) | [privacy/nl/](https://empiricalcodelabs.github.io/FunkySecondsTnP/privacy/nl/) | [privacy/pt/](https://empiricalcodelabs.github.io/FunkySecondsTnP/privacy/pt/) | [privacy/tr/](https://empiricalcodelabs.github.io/FunkySecondsTnP/privacy/tr/) |
| Terms and Conditions | [terms/](https://empiricalcodelabs.github.io/FunkySecondsTnP/terms/) | [terms/af/](https://empiricalcodelabs.github.io/FunkySecondsTnP/terms/af/) | [terms/nl/](https://empiricalcodelabs.github.io/FunkySecondsTnP/terms/nl/) | [terms/pt/](https://empiricalcodelabs.github.io/FunkySecondsTnP/terms/pt/) | [terms/tr/](https://empiricalcodelabs.github.io/FunkySecondsTnP/terms/tr/) |

## Updating

Don't edit the HTML by hand. The pages are generated from the same text the app shows in-app (`assets/text/terms_privacy/<language>/privacy.json` and `terms.json` in the Funky Seconds app source), so the website and the app always match.

1. Edit the JSON in the app source.
2. From the app root, run:
   ```
   dart run tool/build_legal_site.dart ../FunkySecondsTnP
   ```
3. Commit and push this repo. GitHub Pages republishes within a few minutes.

A new in-app language is picked up once it's added to `_languages` in `tool/build_legal_site.dart`. The script refuses to run if a language folder is missing from that list.

## Contact

funkysecondsgame@gmail.com
