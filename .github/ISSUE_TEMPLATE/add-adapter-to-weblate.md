---
name: Add adapter to Weblate
about: Use this template to request an adapter to be added to Weblate
title: Add <adapter name> to Weblate
labels: ''
assignees: UncleSamSwiss

---

**Checklist:**

-   [ ] The adapter contains the i18n files in a separate folder with the default naming scheme
-   [ ] All translation JSON files are up-to-date (call `gulp translateAndUpdateWordsJS` and commit and push those changes to master/main)
-   [ ] Repository hook is configured on GitHub (set the Payload URL to `https://weblate.iobroker.net/hooks/github/`)

**Request:**

Please add the following adapter to Weblate:
Name: ioBroker.mygreatadapter
URL: https://github.com/MeMyselfAndI/ioBroker.mygreatadapter

**Remarks:**
<!-- add your remarks here -->
