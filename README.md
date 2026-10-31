# IPR Racing:

**IPR Racing Team. _OUTRACE THE ODDS_** A rental karting team where results come purely from your on track performance, never through bias, connections or politics.

Website: [iprracingteam.in](https://www.iprracingteam.in)
Email: the.iprracing@gmail.com
Founded: June 2026

This repository holds the official IPR Racing website.

---

## Who we are:

IPR Racing is a karting team and community of rental karting drivers spread across cities in India. We race at our own local tracks, meet up at championship events and run a season-long championship that anyone can take part in from wherever they live.

The team is open to beginners, experienced racers and motorsport fans alike. What we care about is how you drive, how you improve and how you treat the people around you.

## Why the name:

At a rental karting event in 2026, a kart fault that the organisers themselves had confirmed was dismissed with four words: "It's part of racing". No requalification was given. Drivers who had paid and travelled to be there were told to just accept it.

In rental karting the kart isn't yours, the mechanics aren't yours and none of the kart preparation is in your control. Giving every driver a fair kart is the organiser's job. Calling a confirmed fault "part of racing" is an excuse.

IPR Racing was founded in June 2026 to race without that excuse. The name keeps the phrase on purpose, as a reminder of what we stand against.

## What we believe in:

- **Merit.** Results are earned on track, by the driver, and nowhere else.
- **Fairness.** Equal karts and equal treatment, with no favourites.
- **Honesty.** Our championship runs on trust, so honesty comes first.
- **Respect.** For other drivers, track staff, marshals and organisers.
- **Open to all.** Any city, any country, any experience level.

## The Consistency Championship:

Our members live in different cities, so the championship is raced from your own local track. Instead of rewarding one lucky flyer lap, it rewards the hardest skill in a rental kart: lapping at the same pace, again and again.

**Season 1 runs from June to December 2026 and entry is free.**

| Article | Rule |
|---|---|
| 1. Drive 10 laps | Ten consecutive laps at your local track. Drive more if you like and your best 10 in a row are scored. |
| 2. Send proof | Onboard footage, a photo of the timing screen or a written log taken straight off the display. |
| 3. Scored on CV | Your coefficient of variation decides the month. Lower is better. |
| 4. F1-style points | The ten lowest CVs each month score points. Most points from July to December crowns the Champion. |
| 5. Fast and steady | Drive more than 10 laps and if your fastest lap of the session falls inside your scored 10, you earn a bonus point. |
| 6. Every lap counts | Fewer than 10 laps in a row costs 1 point per missing lap, if that session is your result for the month. |
| 7. Ties | A tie in a month goes to the lower standard deviation. A tie for the title goes to the lower average CV, then to more months competed. |
| 8. Built on trust | No cameras or officials watch our tracks. What you submit is taken as the truth, so be honest with yourself first. |

### How CV works:

CV (coefficient of variation) is the standard deviation of your 10 laps divided by your average lap time.

```
CV = standard deviation of your laps / average lap time
```

Dividing by the average puts a 28 second track and a 55 second track on equal footing, no matter what kart you drive. You can test your own laps with the lap test on the website. It uses the sample standard deviation, exactly as the championship does.

## Where we're heading:

- **Grow the team** across more cities, with members racing at their local tracks every month.
- **Race together** at rental karting championships as IPR Racing, in team kit.
- **Run our own events.** The long-term goal is IPR events at tracks we choose, run the way every rental event should be:
  - Karts checked before every session, so no result is decided by a faulty machine.
  - Equal kart allocation, with no favourites.
  - Rules agreed in advance and never changed once racing starts.
  - Results earned cleanly, on track.
- **Build a recognised name** in Indian rental karting first, and then wider.

## Join the team:

Joining is free, from any city or country.

1. Go to [iprracingteam.in](https://www.iprracingteam.in) and open the entry form from the Join IPR section.
2. Fill in your details and your home track.
3. Under 18? A parent or guardian confirms first.

Questions before joining? Email the.iprracing@gmail.com.

## Our partners:

IPR Racing is supported by:

- Berakah Studios
- Sam'D Learning Technologies
- Racing Simplified
- Favgreen
- Metzoid Industries
- TASA Growth Impetus Pvt Ltd
- Vyas

Interested in partnering with the team? Write to the.iprracing@gmail.com.

---

## About this website:

The site is a single, hand-built page with no framework and no build step.

### Features:

- **Live track map.** A simulated 10 lap session drawn on a canvas track, showing how a consistent driver lays down one tight line while an erratic one smears across the track. The fastest lap is marked in purple, as on an F1 timing screen.
- **Lap test.** Type or paste 10 laps (seconds like 41.62 or minutes like 1:02.45) and get your CV, average, standard deviation and spread, scored the same way as the championship. Everything is calculated in your browser and nothing is sent anywhere.
- **Day and night mode** with a smooth transition.
- **Partners section** that sizes every sponsor logo evenly, whatever its original shape.
- **Responsive layout** for phones, tablets and desktops, with a mobile menu.

### Built with:

- HTML, CSS and plain JavaScript in one file
- Canvas for the track map and lap drawings
- Google Fonts: Archivo and Martian Mono
- Hosted on Vercel, with the domain at GoDaddy

### Files:

```
index.html     the whole website: markup, styles and scripts
Sponsors/      partner logos shown in the Partners section
```

### Running it locally:

No installation is needed. Download or clone the repository and open `index.html` in a browser.

```
git clone https://github.com/xavdx/IPR-Racing-Team.git
cd IPR-Racing-Team
```

Note: the automatic trimming of sponsor logos only works when the page is served over http, not when opened directly as a file. To see it locally, run a simple local server from the project folder, for example:

```
python -m http.server 8000
```

and open http://localhost:8000.

### Editing common things:

Near the top of the script in `index.html`:

- `CONFIG` holds the join form link and the Instagram link.
- `SPONSORS` is the list of partner logos. Each entry has a name, the logo file path inside `Sponsors/`, an optional website link and a scale value to fine-tune its size.

To add a partner, put the logo file in `Sponsors/` and add one line to `SPONSORS`.

### Deployment:

Every push to the main branch is deployed automatically by Vercel to [iprracingteam.in](https://www.iprracingteam.in).

---

## Brand and usage:

The IPR Racing name, logos, kit designs and website design belong to IPR Racing. Please don't reuse them without permission. Partner logos belong to their respective owners and are shown with their permission.

If you'd like to use something from this project, email the.iprracing@gmail.com and ask. We're happy to help.

---

**IPR Racing Team. _OUTRACE THE ODDS_. Founded June 2026.**