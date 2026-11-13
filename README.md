# OrderJaba legal site (Terms &amp; Privacy)

Self-contained static pages for the **Privacy Policy** and **Terms of Service**, hosted on
**GitHub Pages**. The App Store and Google Play both require a **public Privacy Policy URL**, so these
must be reachable before submitting the apps.

```
index.html     landing page linking both documents
privacy.html   Privacy Policy
terms.html     Terms of Service
style.css      shared styles (OrderJaba brand, light + dark)
```

## Live URLs (GitHub Pages — dennohdev/orderjaba-legal)

```
Home:     https://dennohdev.github.io/orderjaba-legal/
Privacy:  https://dennohdev.github.io/orderjaba-legal/privacy.html
Terms:    https://dennohdev.github.io/orderjaba-legal/terms.html
```

Use the Privacy URL in **App Store Connect** (App Privacy → Privacy Policy URL) and **Google Play
Console** (Policy → App content → Privacy Policy). Optionally also paste the same copy into
Admin → Business Settings → Terms &amp; Privacy so the `/config` API serves it in-app.

## Contact details used

Contact is listed as **OrderJaba, Nairobi, Kenya**, email **orderjaba@gmail.com**, phone
**+254 704 180224**, and the M-Pesa Till **3342130** (matches the app checkout). If you register a
formal company name or change contact details, update both `privacy.html` and `terms.html` and
re-push — Pages redeploys automatically.

## Updating

```bash
# edit the files, then:
git add -A && git commit -m "Update legal docs" && git push
```

## When the real domain is ready

Re-host the same files at e.g. `https://orderjaba.co.ke/privacy` and `…/terms`, update the two store
listings, and keep this GitHub Pages copy as a redirect or take it down.
