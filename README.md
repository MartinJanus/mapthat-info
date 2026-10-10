# MapThat public information

Public privacy and data-deletion information for the MapThat Instagram DM
prototype, operated by Martin Janus. Contact: appmapthat@gmail.com.

This repository contains only public documentation. It does not contain the
MapThat application, account credentials, private messages, or user fixtures.

## Published pages

- Home: https://martinjanus.github.io/mapthat-info/
- Privacy policy: https://martinjanus.github.io/mapthat-info/privacy.html
- Data deletion: https://martinjanus.github.io/mapthat-info/data-deletion.html

GitHub Pages publishes the `docs/` folder from `main`. The Markdown pages use
GitHub's supported Minimal theme; there is no custom JavaScript, analytics,
tracking pixel, or contact form. Email links open the visitor's mail application.

## Updating the policy

Edit the pages in `docs/`, update their effective date when the policy changes,
review the text against the application's actual behavior, then commit and push
to `main`. GitHub Pages will rebuild the site. Verify the public pages after a
deployment and before entering their URLs in Meta's dashboard.

The current notice covers the fixed-reply experiment. Review it before adding
Reel retrieval, AI providers, location extraction, persistent storage, analytics,
or additional hosting providers. Do not describe future processing as if it is
already happening or claim that a future feature is covered by this notice.

Privacy and deletion emails need to be monitored by the operator. A request must
be fulfilled using the actual systems holding the person's data; this static
site does not automate deletion or implement a Meta deletion callback.

## References

- [Meta Instagram App Review settings](https://developers.facebook.com/documentation/instagram-platform/app-review)
- [Meta Platform Terms](https://developers.facebook.com/terms/)
- [GitHub Pages setup](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [European Commission information obligations](https://commission.europa.eu/law/law-topic/data-protection/information-business-and-organisations/obligations_en)

Publishing this repository makes these documents publicly accessible. It does
not change the private MapThat application's visibility, deploy its backend, or
publish the Meta app. Those are separate actions.
