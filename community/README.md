# Waystitch community review

Anyone can read the reports below. Choose a form to post or comment using your GitHub account. Each report shows its author, replies and review history. You can use Waystitch as a guest.

| Topic | Submit | Browse |
| --- | --- | --- |
| Map or address correction | [Open form](https://github.com/nee00ooo/speedometer-map-packs/issues/new?template=map.yml) | [Open reports](https://github.com/nee00ooo/speedometer-map-packs/issues?q=is%3Aissue%20is%3Aopen%20label%3Amap-correction) |
| Road conditions and speed limits | [Open form](https://github.com/nee00ooo/speedometer-map-packs/issues/new?template=roads.yml) | [Open reports](https://github.com/nee00ooo/speedometer-map-packs/issues?q=is%3Aissue%20is%3Aopen%20label%3Aroad-report) |
| Suggest a trail or trail update | [Open form](https://github.com/nee00ooo/speedometer-map-packs/issues/new?template=trails.yml) | [Open reports](https://github.com/nee00ooo/speedometer-map-packs/issues?q=is%3Aissue%20is%3Aopen%20label%3Atrail-contribution) |
| App feedback | [Open form](https://github.com/nee00ooo/speedometer-map-packs/issues/new?template=feedback.yml) | [Open reports](https://github.com/nee00ooo/speedometer-map-packs/issues?q=is%3Aissue%20is%3Aopen%20label%3Aapp-feedback) |

[Awaiting review](https://github.com/nee00ooo/speedometer-map-packs/issues?q=is%3Aissue%20is%3Aopen%20label%3Aneeds-review) · [More evidence requested](https://github.com/nee00ooo/speedometer-map-packs/issues?q=is%3Aissue%20is%3Aopen%20label%3Aneeds-evidence) · [Published changes](https://github.com/nee00ooo/speedometer-map-packs/issues?q=is%3Aissue%20label%3Apublished) · [My submissions](https://github.com/nee00ooo/speedometer-map-packs/issues?q=is%3Aissue%20author%3A%40me)

To see someone's contributions, open one of their reports and use the **Author** filter in Issues, or enter `is:issue author:USERNAME`. The studio manages the review labels and publishes accepted changes. Other contributors can supply sources, confirm observations or propose corrections in a reply.

## What reaches the app

- **Named trails.** Include the public trail name, region, country, source and rights to distribute the geometry. You can attach a ZIP containing a route-only GPX. Reviewers check access, source rights, continuity and endpoints. Accepted routes appear under **Trails & GPX → Saved trails → Browse reviewed community trails** after the studio updates the [reviewed routes](trails.json). A first-time contributor can submit a trail.
- **Mapped places and trail advice.** Include a public map feature reference when possible. Maintainers can publish dated information in [reviewed outdoor notes](outdoor-notes.json). The app checks the note's review and expiry dates. Country pack geometry changes arrive with a later map edition.
- **Road reports.** Include the road, travel direction, observation time and an official source or sign where available. Reply when a hazard clears. The studio reviews this queue. Live driver alerts are a separate, planned feature. A posted limit needs its own evidence.
- **App issues.** Include the Waystitch screen, app version and steps that reproduce the problem. Closed testers can send private feedback through the Google Play listing.

Share personal journeys and meeting pins in a message to a recipient you choose. Check exact coordinates and remove any private approach to the trail before making a public submission.

## Maintaining the two public feeds

For outdoor notes, retain the feature reference, original issue, source, review and expiry dates. Park authorities, local signage and closures take precedence. For a reviewed route, add an entry to the routes list containing the positive GitHub issue number, public name, region and source credit, plus one coordinate array per continuous section. Store each point as [longitude, latitude]. Preserve gaps. Exclude contact information, comments, times, altitude and device identifiers. Bump the relevant revision whenever an entry changes, including a withdrawal. Readers can refresh the list and save a walk to their device.
