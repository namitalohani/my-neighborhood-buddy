# My Neighborhood Buddy — starter website

This is a static, beginner-friendly first landing page for the Mahanagar, Lucknow pilot.

## What is included
- Responsive landing page in one file (`index.html`)
- Interactive OpenStreetMap view
- An illustrative 2.5 km circle centred approximately on Gole Market, Mahanagar
- Clear separation between the official Ward 53 core and nearby candidate coverage
- Community contribution entry point (currently an email link placeholder)
- No database, login, API key or paid service required for this prototype

## Important geography note
The 2.5 km circle is a planning catchment only. It is NOT the official Ward 53 boundary.
The official 31 October 2022 delimitation notification describes Ward 53 using written locality and boundary descriptions. The actual GIS polygon still needs to be obtained/validated.
Neighbouring localities in this prototype are candidate coverage labels, not a claim that their complete municipal areas lie inside the circle.

## Publish free with GitHub Pages
1. Sign in to GitHub and create a new public repository named `my-neighborhood-buddy`.
2. On your computer, unzip this folder.
3. Upload `index.html` and `README.md` to the repository's main/root folder.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch `main` and folder `/ (root)`, then click **Save**.
7. GitHub will show your public website address after it finishes publishing.

You can edit the words in `index.html` using GitHub's pencil/edit button. Change the contact email before publishing.

## Free hosting choice
For this first static demo, GitHub Pages is the simplest free option. Netlify is also suitable and makes later form/function integrations easier. Once the project needs resident accounts, complaint tracking, submissions, moderation and a database, we will add a backend (for example Supabase) rather than pretending a static page can securely store those records.

## Map and data notes
- Map display uses Leaflet and OpenStreetMap tiles via public CDN/tile service. Keep attribution visible. For a widely used production app, choose a tile provider and comply with its usage policy.
- Map centre is approximate Gole Market coordinates: 26.87514, 80.95811.
- OpenStreetMap and community place data can be incomplete. Verify critical details before publishing.
- No government affiliation is claimed.

## Suggested next build steps
1. Replace placeholder contact email.
2. Confirm the 2.5 km catchment centre and exact streets/localities using a proper GIS layer.
3. Add a structured directory with source, last-verified date, location, service area and verification status for each listing.
4. Add a community-submission form and moderation workflow.
5. Add resident accounts and complaint tracking only after privacy/security design is ready.

## Sources used for initial planning
- Lucknow district official Nagar Nigam voter-list page: https://lucknow.nic.in/voter-list-of-nagar-nigam/
- Lucknow Nagar Nigam 31 Oct 2022 delimitation notification: https://lmc.up.nic.in/pdf/DelimiationfinalNotification31_10_2022HINDI.pdf
- Lucknow Nagar Nigam older Ward Suchna list: https://lmc.up.nic.in/pdf/WARD_suchna_english.pdf
- Government-reported geospatial mapping of UP urban wards (HT, 19 Apr 2024): https://www.hindustantimes.com/cities/lucknow-news/geospatial-database-mapping-of-783-urban-bodies-14-455-wards-of-u-p-ends-101713536576065.html
- Gole Market, Mahanagar map reference: https://mapcarta.com/N534853105
- Nearby locality reference: https://www.fabhotels.com/hotels-in-lucknow/mahanagar/
