🍋 LEMONTAG
Where Project Cars Find Their Next Chapter

Every project car has a story. A first owner who found it rusting in a field. A soldier who bought it overseas on a handshake. A father and son who rebuilt the engine on weekends. These stories don't belong in a Craigslist ad — they deserve to travel with the car, forever.
Lemontag is a marketplace and provenance platform built for the car enthusiast community. When life gets in the way — and it always does — project cars get sold. Bills come due. Garages get cleared out. But the emotional bond between an owner and their build doesn't disappear when the keys change hands.
Lemontag solves this. Every car listed on the platform receives a permanent LT-#### tag number that follows the vehicle through every sale, every new owner, every decade. Think of it as a social security number for your build — carrying its full history, its story, and the names of everyone who ever turned a wrench on it.

What Makes It Different
FeatureWhat It DoesLemontag IDA permanent tag number assigned to every car — it never changes, no matter how many times it sellsStory ListingsRich narrative listings that capture why a car matters, not just what it isKeeper's RegistryFormer owners can register sentimental interest — and get first right of refusal when their car comes back to market5 Status States🟢 Active · 🟡 Pending · 🐿️ Squirreled · 🔄 Transferred · 🏡 DomesticatedAirtable BackendA no-code admin dashboard — manage listings, approve submissions, and track offers without touching a line of code

The Five States of a Lemontag Car

🟢 Active — Listed and available for sale or offers
🟡 Pending — An offer has been accepted; sale in progress
🐿️ Squirreled — Deeply loved, story shared, but not for sale (the owner is holding the keys tight)
🔄 Transferred — Changed hands, awaiting formal transfer completion
🏡 Domesticated — Transfer complete; safely in a new collection


Tech Stack

Frontend — Single-file HTML/CSS/JS, deployable on GitHub Pages with zero dependencies
Backend — Airtable (Personal Access Token API) for listings, offers, and Keeper registrations
Admin Panel — Password-protected dashboard built into the platform; connect Airtable credentials and manage everything in-browser
No framework. No build step. No server.


Getting Started

Deploy index.html to GitHub Pages (or any static host)
Create a free Airtable base called Lemontag with tables: Listings, Keepers, Offers
Generate a Personal Access Token at airtable.com/create/tokens with data.records:read, data.records:write, and schema.bases:read scopes
Open your live site → click Admin → go to Settings → paste your token and Base ID → click Save & Test Connection
Your platform is live. Start issuing tags.


The First Tag
LT-0001 belongs to a 1965 Chevrolet Impala SS — 396 Big Block, Super Sport, royal blue. Bought from a fellow soldier while stationed in Korea. Shipped back to the States. Rebuilt from the block up. The car that started all of this.
