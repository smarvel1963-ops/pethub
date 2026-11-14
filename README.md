# Pet Hub
Save path: C:/MarvelApps/pethub/README.md

Live (once pushed): https://smarvel1963-ops.github.io/pethub/ - app #10 of the Marvel Corp Hub family (Scott 2026-11-13: "Pet Hub",
then "Yes, build it"; plan: C:/MarvelApps/docs/hub_improvement/pethub/PET_HUB_PLAN_2026-11-13.md; look: his board 1,
docs/hub_improvement/pethub/boards/board1_four_screens_2026-11-13.png).

This repo is Pet Hub's OWN shell: index.html, manifest.json, icons, sw.js and privacy.html. The app itself is the shared Hub
engine in the Day Hub repo, run with window.DH_MODE = "pet" plus pet.js and pettiles.css (Pet Hub's look, loaded only here).

- Own data on the phone (pethub.v1, S.pt); photos in IndexedDB (pethub.photos), never in the backup, emptied by Erase.
- Screens (board 1): Our Happy Crew (all my pets), each pet's page (age, birthday + Gotcha Day countdowns, milestone, today's care,
  Our Memories), Birthdays & Ages (party card, calendar, upcoming, slideshow, ages at a glance), Memory Moments (life journey,
  scrapbook, Then & Now, On This Day, Add Memory), Add Your Pet (species, birthday or estimated age, Gotcha Day, photo), Daily Care,
  Health & Records (shots, vet visits, medicines, weight chart), Pet Passport (ID, microchip, emergency vet, poison control,
  papers), Rainbow Bridge. Picking a pet turns the app to that pet's colour.
- Reminders: care times, doses, shots (7 days + day of), vet visits (evening before + 1 hour), birthdays (week + day), Gotcha Days.
- Never veterinary advice: medicines are exactly what the owner typed from the vet.
- Icons: drawn in code by docs/hub_improvement/pethub/make_pethub_icons.py.
- Release order: push THIS repo first (and turn on GitHub Pages), then the Day Hub repo.
- Tests: the Day Hub repo (python tests/test_pet.py; plus tests/run_tests.py for the whole engine).
