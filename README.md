Wayvia by Risk Survivors
Team: Pyae Hein Khant, Yin Nwe Oo
Problem Statement: Travel Planner
Video Presentation: https://youtu.be/VlZ4CmAWpM0
Presentation Slides: https://cloudmails-my.sharepoint.com/:p:/g/personal/tp088751_mail_apu_edu_my/IQCKmebmWJ6gSbkpzYBfuVsnAakapfio-Qn-uvW_bB8BJgg?e=KU4uoi

1. Project Overview
The Problem
There's lots of disconnected tools and channels: you get inspiration from TikTok, Instagram, Google Maps, and so on, you book the vacations in airline apps, Booking.com, Agoda, and so on, you store the documents in email inboxes and screenshot galleries, you create an itinerary in Google Sheets or Notion, you create a budget in Spreadsheets; and splitting the expenses happens in a WhatsApp, group-chat discussion, and so on. But when it goes off the track, whether the flight gets delayed, there's bad weather and visitors miss their booking, or a booking has been cancelled, nobody has coordinated how to react and everything that goes wrong is answered individually and the trip goes down the drain.
The stakeholders are the travelers themselves: fellow travelers making short journeys, couples, families traveling with children and/or older family members, new international travelers seeking some clarity and confidence, and solitary travelers, particularly women, who are concerned about safety. One person in every group is tasked with manual coordination and is the "organizer" who does not receive the pay for such a role. It is also supported by research—Google/Kantar revealed that 44% of younger travelers find planning overwhelming while surveys into family travel highlight affordability and making it easier to travel for a sizable portion of parents.
Sort of works, but doesn't do all kinds of things, such as keeping people up to date on or determine activity choices based on group voting, understanding how a cancellation or a flight delay will impact the rest of the trip, and help a group reach some shared agreement and execute that on the unfortunate scenario that there is an overall disruption where they must create a Plan B. They structure information – they do not coordinate people.
Our Solution
With Wayvia, the team can get all pieces of inspiration, bookings, documents, and budgets on one realistic, shared itinerary – and stay flexible together when things change. It is not a booking platform, it is NOT a booking platform that extends upon the IGR tools that travelers use every day (Maps, app, airline's app, Booking.com, calendar) and connects back out with links to those that need to take action. Groups could go from scattered inspiration to a dependent-aware, feasibility checked itinerary and in case of a problem, the app automatically assesses the impact and suggests alternative contingency routes instead of leaving group members "beach bumming."
Features
●	Visual vision board for gathering travel inspiration (links, screen shots, notes)
●	AI extraction to structure places and bookings automatically saved.
●	Arrangements for group voting and preferences in relation to activities and accommodation. Routine of group voting and preferences in relation to activities and accommodation.
●	Creative communities that are planned for accommodation are a development of location, budget, and activity clusters.
●	Itinerary generation with dependency-awareness and feasible check.
●	Starting from the map view, main itinerary and optional (Explore) layer:
●	Import flights/booking documents (email forward, import, paste, manual)
●	Insurance documents, permits, and terms simplified by document hub with AI!
●	Accounting of shared budget and expenses with settlement calculations.
●	Find, investigate, and rate the disruption of courses and/or lessons. Disruption reporting that includes impact analysis and disturbance severity scoring.
●	Generates explanations in plain language for the AI using rules instead of referring to training data.
●	Dedicated support for group approval workflows of decisions and recovery plans
●	Team notifications and activity fees. Grouped notifications and activity fees.
●	Elevated level out to booking providers, hotels, airlines, and Maps.
●	Export from calendar and offline trip pack feature.
2. Ideation & Process
2.1 Ideas We Considered
Table of every distinct idea generated, with why each was kept or dropped, order it so that chosen ideas are listed first.
Idea	Why it was dropped / kept

A (Dependency-aware itinerary generation (Chosen)	Kept because it is the biggest differentiator from list-based planners like TripIt or Wanderlog — the app understands that one change (e.g., a flight delay) cascades into the transfer, check-in, and next day's plans, instead of treating every item independently.
B Rule-based disruption detection + backup-plan generator with group approval (Chosen)	Kept because without it, the app is just a nicer shared to-do list. This is what turns "everyone panics separately" into a structured group decision, the actual coordination promise.
C Full booking platform (build our own flight/hotel booking engine)	Dropped because it needs partnerships with every provider, heavy compliance, and capital we do not have. We positioned the app as a coordination layer instead: import bookings, deep link back to the provider to purchase
D Fully autonomous AI booking/cancellation (AI acts without asking)	Dropped because of too much liability and would break user trust immediately. AI prepares the action; the user always approves it.
2.2 Ideation Boards
 
A user flow showing the first-time journey from signing up to seeing a finished itinerary, screen by screen.
 
A problem tree tracing root causes (scattered inspiration, bookings, documents, and decisions) up through the core problem to its real-world effects (unpaid organiser, budget conflicts, unrealistic itineraries, no backup plan). 
A mind map of the app's core idea: six key capabilities (vision board, AI extraction, group voting, itinerary engine, disruption recovery, budget tracking) radiating out from the central concept. 
A flowchart of the planning-mode decision: once a trip is created, the group chooses an inspiration-first or AI-first path, and both converge on a shared, voted-on plan.
2.3 Mentor Consultation
Date	Mentor	Feedback Received	What Was Changed
6th Sept 2026	Zach Khong	The mentor appreciated our core app idea but thought that UI/UX should be made simpler and cleaner so that they can use it easily. He also encouraged us to be more trip-focused instead of the individual travelers, and less on people who have not travelled with ideas of their own. 	We changed the voice of our product: our main use-case was group coordination and not that of the individual traveler. The UI/UX direction was also made simpler, with the shift towards AI-first suggestion flows being reduced in favor of user-driven and group-based planning. 
3. Design & Prototype
UI Prototype: https://www.figma.com/design/QOtxahI7x5mpSyDyePf0Aw/UI-UX?node-id=0-1&t=7snKEXVssTz8TzlH-1
Home
   

The entry point: your current trip at a glance, a "smart co-planner" to spin up a new trip with AI, and curated guides and popular group itineraries to clone.

Travel Board
   	
The shared vision board — drop a TikTok, Instagram, or Maps link and the app auto-extracts the spot into a card the squad can browse and vote on.

Card Details

   	
Tapping a spot opens its full details, where the squad reaches consensus by voting "Definitely going" or "Maybe later."

AI Smart Itinerary 

   	
The day-by-day schedule is dependency-aware — it shows live weather, walking pace, travel buffers between stops, and locks once the group's votes are in.

Map View
 
Live squad tracking on the map, with real-time disruption alerts (here, a cancelled ferry), a transit-mode comparison, and one-tap directions.

Budget & Expenses
   	

Shared trip budget broken down by category, per-person balances, and expense logging via receipt scan, bill upload, or manual entry.

Disruption & Backup Plans
     
When something goes wrong — here, a monsoon downpour — the app runs an impact analysis on the itinerary and generates ranked backup plans with cost and time trade-offs for the squad to vote on.

Trip Documents

     	
A central archive for bookings, insurance, and travel documents, auto-ingested from forwarded emails or screenshots, with AI-extracted key dates and coverage details.
4. What Makes It Different

Most travel planning apps are either inspiration generating (Pinterest-like boards) or organization (checklist/itinerary apps), but not a combination of the two — or none. Our novel deals with the problem of being full of ideas, but not having a plan that you can execute when things go wrong:

Itinerary, not a list dependent on geographic elements. Other itinerary tools take the individual items as separate elements. Our senses know that it matters when something changes — if the flight is delayed, the airport transfer and hotel check-in and next morning are all delayed. The central part: the tour is not a fixed piece of text; it is a small system of relationships.
Integrated voting system in each decision, not something added on. The trip is not voted on in a thread, instead, each activity and every response of the disruption occur through a "Must-do / interested / Skip" vote, and the group can decide, not the usual conversation that fizzles out.
Clean-up the environment based on rules and group approval. If things do not go according to plan (for example: the rain, venue was cancelled due to tickle, or teammate who fell sick), the app not only notifies people, but simulates 2-3 backup plans, ranks them, breaks down the trade-off in layman's terms, and invites the group to vote on the best one to proceed with. This is the element that makes ‘Everyone reacts individually' a coordinated response.
A coordination layer, not another booking app. We do not pretend to be replacing airlines, hotels, or Google Maps. We structure what is already booked and link back to the tool when it is necessary — reduced scope and it is not competing with providers users already trust.
Document simplifiers for great jobs. Long insurance policies or permits are boiled down to their essentials—who, what, when, where, and how much — not itinerary, but it cuts out a tangible reason to cause last minute hassle among the group, e.g. "Wait, does our insurance cover all this?".

Comparison with existing solutions:
Feature	TripIt/Wander log	Our App
Store bookings & build itinerary	Have	Have
Group voting on activities	Does not have	Have
Understands how one change affects the rest of the trip	Does not have	Have
Generates and helps the group approve a backup plan when something goes wrong	Does not have	Have
Simplifies long documents (insurance, permits) into key facts	Does not have	Have


5. Technical Architecture & Feasibility
Tech stack
Layer	Choice	Why	Constraints we expect
Frontend	React Native (with Expo)	 	Ships to both iOS and Android from a single codebase, surely boosts build/test cycle in a quick build stage, no need to configure native Xcode/Android Studio builds from scratch.	 	Some native features might require us to “eject” from Expo's managed workflow later, which is a trade-off for now because our MVP does not need those 
Backend	FastAPI	Quick to construct, has awesome async support for actual-time features (voting/circumstance alerts), also our team already has Python experience. 	At scale will have to manage WebSockets carefully, at hackathon/MVP scale not specifically so. 
Database	PostgreSQL + PostGIS via Supabase	Proper geo queries for "distance to activity cluster" scoring, and it is a relational structure that suits our data model just fine (Trip → Members → Activities → Votes) and all Supabase includes us a bundle of Postgres + Auth + Realtime	 	Supabase's free tier limits connections and row updates (is fine for MVP but not beyond the capacity of a paid plan if you are hitting a high number of concurrent trips). 
Realtime Routing	Supabase Realtime	Will be needed in the group voting and disruption alert functions for instant updates to feel real-time (instant response) across members' phones.
	free tire sufficient for a hackathon demo.
Push notifications	Expo Push Notifications 	included by default in the React Native/Expo stack, and does not require an independent service (like Firebase Cloud Messaging) to be set up separately for MVP	 	Does not deliver the push notification instantly on the latest devices (delays are caused by OS-level battery optimization) appropriate for a demo, but should be noted for a real-world application 
Maps & routing	Google Maps Platform (Routes API, Distance Matrix API) 	Enables map experience that users expect on mobile (pinch-zoom, native markers), as well as well-documented API for calculating routes/distance (needed for our itinerary) — 	se an API key, but paid per request outside of free tier — will cache routes/distance results on back-end per trip and proxy-api call server-side, never expose in application bundle 
Weather	OpenWeatherMap	It is important for us to provide a use case that disrupts the application: when there is rain or heat in the air; Free tier is good enough for us	 	The free tier limits requests per hour per API key, so we would be checking the weather per trip on schedule instead of per user action. 
Flight status	Manual Entry / Paste for MVP; Amadeus / AviationStack as a stretch goal 	The manual entry (no "stretch goal") has no integration risk and unblocks the core itinerary/disruption flow without waiting for the API's approval; 	Amadeus and AviationStack require it to be approved by the developer account, which may take some time 
Document processing	PDF parsing library + LLM for extraction (Document Simplifier)	LLM is good for "explain this in plain language", 	LLM output requires a "needs checking" flag that is displayed to the user — do not consider auto-extraction as authoritative. 
Hosting
	Backend on Railway or Render; Supabase for DB/Auth/Realtime; app distributed via Expo (EAS Build) for demo, TestFlight/Google Play internal testing if time allows	Generous free tiers suited to a 3-week build; Expo/EAS lets us generate installable builds without needing paid Apple/Google developer accounts for the demo stage.	

	Publishing to actual app stores (App Store/Play Store) require paid developer accounts ($99/yr Apple, $25 one-time Google) and review time — out of scope for the hackathon demo, we will distribute a build link/QR code instead
Build plan & scope.
Our mentor advises us to narrow in scope to focus on group trip coordination first, with the solo-traveler mode and AI-first "no idea what I want" flow explicitly un-scheduled for this build phase. In the 3-week construction period, we will make the following builds:
●	The process of creating trips, invitations, and the basics of traveler profiles.
●	To facilitate the description of input, you can present the retrieved list of locations on a Vision board by manual entry (by the user) or using links from Google maps (can be extracted automatically or manually into the board with Google maps links).
●	Collective decision making of saved places & activities.
●	Planning hotel accommodations and defaulting to a simple scoring based on place.
●	Generating a single trip dependency-aware Itinerary (not AI-generated from scratch).
●	A view of the itinerary on a map.
●	Basic settlement calculation with shared budget / expense.
●	One or two types of disruption (e.g., flight delay or weather) disruption reporting with a rule-based suggestion for a backup plan and group vote.
New functionalities that will be available at a later point in time: planning using AI for ‘undecided' user profiles, solo-traveler mode, document simplifier, calendar export, trip pack (offline). They are still under plans for the future features in that full product spec, but we are continuing to enforce the build phase to implement an end-to-end process that makes group coordination (trip creation, voter-confirmed trip confirmation and itinerary, and disruption recovery) easy to use for everyone, due to mentor UI/UX suggestions.



