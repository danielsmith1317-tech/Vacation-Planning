# Vacation planning lifecycle — permanent site standard

This document governs every active, future and archived trip page. Follow it when a confirmed decision or new booking is supplied, in addition to the rules in README.md.

## Stages
1. **Researching:** Show comparable options, honest occupancy/bed validation, location/quality/rate comparisons, points/MMP/MMA (if available), and potential activities. Prices are research quotes until booked. 
2. **Planning:** Show chosen shortlist, intended dates, proposed itinerary and next actions. Mark tentative items amber. Keep alternatives minimal and collapsible; do not falsely mark them confirmed.
3. **Booked / Confirmed:** A stage that can apply independently to a hotel, train, flight, transfer or excursion, even if the wider trip remains partly planned. Show verified booked choice and useful dates, room/seat, check-in, location, directions, transportation, nearby transit, groceries and food. Stop showing outdated comparisons for that component. Keep monetary figures ONLY within Budget / Bookings; do not display costs in summary labels, transportation or accommodation cards outside budget. Use green for confirmed. Verify sources before changing status. Show open actions (tickets/API/ETA/cancellation) explicitly. Never publish personal booking references, reservation-management deep links, travel document numbers or credentials.
4. **Completed / Archived:** Retain historical itinerary, known bookings, maps and retrospective notes. Remove shopping research as the primary view; never invent missing historic data. Any current weather is clearly labeled reference weather, not weather experienced on the trip.

## Page behavior
- All trip pages share the structure **Overview / Transportation / Lodging / Itinerary / Things to Do / Food & Groceries / Maps / Auto Weather / Budget & Bookings / Confirmed Links** as appropriate to recorded facts.
- The trip stage and each component stage are distinct; a partially booked trip may have confirmed flights and undecided lodging.
- Food and groceries, Metro/train access and route times are specific to the selected city and selected lodging. Do not mix cities in the visible view.
- Keep Things to Do compact: a few top priorities visible and expandable categories for the rest. Preserve user favorites, notes and hidden-item state in existing browser storage.
- Transportation includes airport/station maps for every known endpoint; map directions use live routes and distinguish estimates.
- Weather loads when page opens, with sensible error/loading states and forecast-range/historic distinction.
- Blue/navy is a site identity; confirmed status green, undecided status amber, archive neutral. Trips may have unique accent colors.
- Verified individual room occupancy and actual bed configurations matter, not just a 3-person occupancy count. Do not infer other travelers' reservations from a separate person's Gmail.
- Preserve current hub, existing trip folders, archive folders, research data still needed in other unbooked parts of a trip, and relative navigation.

## Publishing workflow
- When the user asks to add or update a trip or supplies a confirmed booking **in an active conversation**, check the latest main-branch files, update only affected components and hub status, publish authorized changes to the existing repository, and verify the Pages deployment/affected behavior.
- **Not an unattended automatic sync:** simply receiving a provider email, changes at Marriott, or time passing does NOT by itself publish the website. Do not claim live synchronization unless a specific authenticated ingestion + publishing automation has been implemented, authorized and tested.
- Only use verified source facts. Never automatically infer a booking from a search result, a selection screenshot or a deep link. Confirm before displaying as booked.
- Archived trips retain the same page shell, map links, auto-weather reference and verified history, even if incomplete.

## Consistency audit — October 7, 2026

- Paris/London is the reference for confirmed-versus-research transitions, city-specific grocery panels, compact activity browsing, and separating costs from travel cards.
- All active and archived pages retain their existing content and navigation, automatic Google Weather, maps, and stage indicators. Common section names were aligned where equivalent content exists; missing historic bookings must not be fabricated to fill a template.
- Punta Cana optional tours are collapsed by default, matching the compact Paris activity pattern.
- Recheck any new booking against the exact travelers, dates, fare class, beds and cancellation rules. Each component may move to Confirmed independently. A whole trip should not be called fully booked while significant items remain TBD.
- Before publishing any new trip, check navigation, responsive layout, map/weather load, links, confirmation coloring, city-specific food, research collapse, and no public booking secrets.
