# The Card Trick Library

**Learn 46 card tricks, then go and fool real people.**

A free, single-page web app that teaches card magic to young people aged 12 to 18. It covers the tricks, the maths behind them and the legends who made card magic famous. It gets learners off the screen with real-world performance missions, and includes a safe, UK-focused guide to starting a small magic business.

It has no sign-up, no tracking and no server. Everything runs in the browser.

---

## Features

### Learn
- **46 tricks**: 10 classics plus 36 original routines built on proven principles. Each one is tagged Beginner or Intermediate, and Self-working, Mathematical or Sleight of hand.
- **Be fooled first**: five tricks are performed *on you*, on a virtual felt table, before you learn them.
- **Guess before you peek**: two hints come before each secret.
- **Behind the curtain**: a full explanation of why each trick works, with diagrams.
- **The laboratory**: run a trick 1,000 times to prove it works, then change one step and watch it fail.

### Practise
- **Rehearsal mode**: one step at a time in huge type, with a timer that logs your practice.
- **Drills**: step-order, find-the-key-card and letter-count speed drills, all scored and timed.
- **Mastery ladder**: four honest levels per trick, from "knows the steps" to "fooled a real person".
- **Patter scripts**: words to say in mysterious, funny or storytelling style.
- **Fix it**: common mistakes for every trick and how to fix them.

### Perform for real
- **Missions**: ten real-world challenges, from performing to a mirror up to a first booked gig.
- **Show log**: record each show, including who watched, whether they were fooled, and what to change next time.
- **Show builder**: plan a set and get warnings about running time, secret setups, decks and pacing.
- **Practice journal**: streaks, minutes per day and time per trick.
- **Ten badges** to earn along the way.

### Go pro (UK, ages 12–18)
A nine-step guide covering safety with a parent or carer, child performance licences, pricing, an act name and flyer builder, the £1,000 trading allowance with an earnings tracker, and a gig-day checklist. This is general information, not legal advice.

### Explore
- **Card maths**: 16 little-known facts, a faro shuffle machine, the match game and the Kruskal count.
- **Legends**: stories of famous women and men in card magic and sleight of hand.

---

## Run it

It's one HTML file with no build step.

- **Locally:** download the repo and open `index.html` in any modern browser.
- **GitHub Pages:**
  1. Push these files to a repository.
  2. Go to **Settings → Pages**.
  3. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
  4. Save. Your site appears at `https://<your-username>.github.io/<repo-name>/` after a minute or two.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app: HTML, CSS and JavaScript in one file |
| `favicon.svg` | Browser tab icon |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |
| `README.md` | This file |

## Privacy

Progress, badges, show logs, the journal, set lists and flyer details are saved in the learner's own browser using `localStorage`. Nothing is sent anywhere. Clearing browser data resets everything, and progress doesn't move between devices.

The only external requests are for Google Fonts (Bungee, Lexend and JetBrains Mono), plus any links the learner chooses to follow.

## Safety

The app is designed for young people:
- Missions remind learners never to perform for strangers alone.
- The business section asks that a parent or carer handles bookings, messages, money and attends every gig.
- The flyer builder warns if a phone number or address is typed in.

## Accuracy

The mathematical methods were checked by simulation, and each trick's laboratory lets you check them yourself. Facts about UK rules and famous performers link to their sources inside the app. Rules can change, so check with your local council and GOV.UK before your first paid gig.

## Credits

Classic principles are credited inside the app where they're known, including Gergonne, Gilbreath, Si Stebbins, Fitch Cheney, Kruskal and the Josephus problem. The original routines are new presentations of these principles. Card magic has a long history, so similar ideas may exist elsewhere.

## Licence

No licence has been chosen yet. Add one (for example MIT for the code) before inviting others to reuse it.
