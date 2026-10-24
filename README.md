# dhaka-rush

<div align="center">

# ঢাকা রাশ · Dhaka Rush

**A 3D open-world browser game set on the streets of Dhaka.**
Drive rickshaws, CNGs, local buses and the UIU bus, pick up passengers, survive the jam, the monsoon and the occasional roadside fight.

**রিকশা · সিএনজি · লোকাল বাস · UIU বাস** · মোবাইল ও ল্যাপটপে খেলুন

![HTML5](https://img.shields.io/badge/HTML5-single%20file-e8364f)
![three.js](https://img.shields.io/badge/three.js-r160-16a36f)
![Web Audio](https://img.shields.io/badge/Web%20Audio-procedural-ffb627)
![Mobile](https://img.shields.io/badge/mobile-touch%20controls-2bd4c8)

![Dhaka Rush cover](screenshots/cover.jpg)

### [▶ Play now](https://YOUR-USERNAME.github.io/dhaka-rush/) · [🎬 10-second gameplay video](media/gameplay_10s.mp4)

</div>

---

## Table of contents

- [About](#about)
- [Features](#features)
- [Screenshots](#screenshots)
- [How to play](#how-to-play)
- [Vehicles](#vehicles)
- [UIU bus routes](#uiu-bus-routes)
- [Radio stations](#radio-stations)
- [Run it locally](#run-it-locally)
- [Deploy to GitHub Pages](#deploy-to-github-pages)
- [How it is built](#how-it-is-built)
- [Project structure](#project-structure)
- [Known limitations](#known-limitations)
- [বাংলায় সংক্ষেপে](#বাংলায়-সংক্ষেপে)
- [Credits](#credits)

## About

Dhaka Rush is a Vice City–style open-world game, but the city is Dhaka and the language is Bangla. Everything in it is generated in code at load time: the buildings, the shop signboards, the rickshaw art, the traffic, the people and even the music. There are no image, model or audio files to download, so the whole game is a single `index.html`.

It runs in any modern browser on a laptop or a phone, with keyboard and mouse on desktop and an on-screen joystick and buttons on touch devices.

## Features

**The city**
- Nine areas: উত্তরা, বনানী, গুলশান, মিরপুর, ফার্মগেট, মতিঝিল, মোহাম্মদপুর, ধানমন্ডি, পুরান ঢাকা, plus সদরঘাট on the Buriganga and ইউনাইটেড সিটি.
- Bangla shop signboards (মায়ের দোয়া হোটেল, বিসমিল্লাহ ফার্মেসী…), rooftop billboards, tangled power lines, black rooftop water tanks, laundry on balconies, tea stalls, krishnachura trees.
- Landmarks: Shaheed Minar, a Shapla fountain plaza, a mosque in Old Dhaka, Dhanmondi lake, launches and wooden boats on the river.
- **UIU campus** modelled on the real building: two exposed-concrete towers with red brick jali on their inner faces, a glazed centre tower, open atria under steel-truss roofs, a stepped podium and the big lawn.

**The street**
- Nearly 70 AI vehicles that drive on the **left**, as in Bangladesh: rickshaws, green CNG auto-rickshaws, private cars, yellow cabs, local buses, painted trucks, UIU buses and police pickups.
- They queue, honk when stuck, and push through jams the way Dhaka traffic does. Some bus and CNG drivers are reckless.
- Pedestrians on every footpath, who jump out of the way and shout at you.
- Traffic police waving at intersections.

**Gameplay**
- **Passenger trips**: "মামা, ধানমন্ডি যাবেন?" Pick them up at the yellow marker, drop them before the timer runs out, and earn a tip for a smooth, fast ride.
- **UIU bus service**: three routes that collect students from Kuril, Notun Bazar and Aftabnagar and deliver them to campus before class starts.
- **Take any vehicle**: press F next to it. The driver gets out and complains. Do it in front of the police and you get wanted stars and a siren chase.
- **Accidents turn into fights**: crash into someone and both drivers get out. Throw punches (with combos), or pay ৳80 to settle it peacefully. A crowd always gathers, and someone always films it. You can also break up other people's fights for a tip.
- **Monsoon**: rain, wet reflective roads, lightning, waterlogged streets that slow everyone down, umbrellas, and fares go up by 50 % ("বৃষ্টির মধ্যে আর দামাদামি করব না, চলেন!").
- **Modes**: running clock (day turns to night), always day, always night, or always raining.
- **Garage**: call a rickshaw, CNG, car, local bus or UIU bus to your side at any time.

**Sound**
- Four radio stations, all synthesised live in the browser (no recorded music): Baul, Bhatiyali, Dhaka fusion and Bangla rock.
- Police chases and fights switch the radio to rock automatically, then switch back.
- Rickshaw bells, CNG and bus horns, engine sounds, rain and thunder.

## Screenshots

| | |
|---|---|
| ![Golden hour street](screenshots/golden_hour_street.jpg) | ![UIU campus](screenshots/uiu_campus.jpg) |
| Golden hour in the city | The UIU campus and the UIU bus |
| ![Night CNG](screenshots/night_cng_gameplay.jpg) | ![Rainy day](screenshots/rainy_day_uiu_bus.jpg) |
| Driving a CNG at night | Monsoon traffic |
| ![Street fight](screenshots/street_fight.jpg) | ![Traffic jam](screenshots/dhaka_traffic_jam.jpg) |
| After the crash comes the fight | Dhaka traffic from above |
| ![Shaheed Minar](screenshots/shaheed_minar.jpg) | ![Mobile](screenshots/mobile_gameplay.jpg) |
| Shaheed Minar | Playing on a phone |

## How to play

### Laptop / desktop

| Key | Action |
|---|---|
| `W A S D` / arrow keys | Walk or drive |
| Mouse (drag or click to lock) | Look around |
| `F` / `E` | Get in / out of a vehicle · settle a fight · break up a fight |
| `Space` | Brake (in a vehicle) / jump (on foot) |
| `Shift` | Run |
| `H` | Horn |
| `R` | Change radio station |
| `K` / left click | Punch (during a fight) |
| `1` `2` `3` | Choose a UIU bus route |
| `B` | Start / stop rain |
| `C` | Camera distance |
| `V` | Garage and modes menu |
| `M` | Mute |
| `Esc` / `P` | Pause |

### Phone / tablet

- **Left side**: put your thumb anywhere and drag. This is the joystick. Push up to accelerate, down to brake or reverse, sideways to steer.
- **Right side buttons** change with the situation: **উঠুন / নামুন** (get in / out), **ব্রেক / লাফ** (brake / jump), **হর্ন** (horn), **ঘুষি** (punch), **রেডিও** (radio).
- **Top buttons**: **মেনু** (garage and modes), **ক্যামেরা** (camera), **বৃষ্টি / রোদ** (rain on/off), **পূর্ণ পর্দা** (fullscreen).
- Drag on an empty part of the screen to turn the camera.
- Landscape is more comfortable, but portrait works too. Tip: use your browser's **Add to Home Screen** to open it full-screen like an app.

### Money

| How | Amount |
|---|---|
| Passenger trip | about ৳30 to ৳350, depending on distance and vehicle; +15–30 % tip for a fast, smooth ride; ×1.5 in the rain; half if you are late |
| UIU bus trip | ৳250 + ৳15 per student + ৳200 if you arrive before class |
| Winning a fight | ৳100 to ৳200 in "compensation" |
| Breaking up someone else's fight | ৳50 tip |
| Settling your own fight | costs ৳80 |
| Getting caught by the police | fine of 20 % of your money (at least ৳100) |

Money and the number of trips are saved in your browser (`localStorage`).

## Vehicles

| Vehicle | Top speed | Notes |
|---|---|---|
| রিকশা (rickshaw) | ~25 km/h | Rickshaw art on the back, pedalling puller, bell |
| সিএনজি (CNG) | ~58 km/h | The classic green auto-rickshaw, two-stroke engine sound |
| প্রাইভেট কার (car) | ~97 km/h | White, silver, black, red, blue or a yellow cab; right-hand drive |
| লোকাল বাস (local bus) | ~61 km/h | Route boards like "গুলিস্তান - মিরপুর ১০", passengers hanging from the door |
| UIU বাস | ~61 km/h | Orange and white AC bus, students visible in the windows |
| ট্রাক (truck) | ~58 km/h | Painted cargo body (AI only) |
| পুলিশ পিকআপ (police) | ~101 km/h | Blue pickup with a light bar; stealing one is a bad idea |

## UIU bus routes

Get into a UIU bus and choose a route. Students wait at orange bus shelters, wave when they see the bus, walk to the door and board when you stop. Then drive them to the campus gate before the class timer runs out.

| Route | Stop 1 | Stop 2 | Destination |
|---|---|---|---|
| 1 · কুড়িল | কুড়িল বিশ্বরোড | কুড়িল ফ্লাইওভার মোড় | UIU campus |
| 2 · নতুন বাজার | নতুন বাজার মোড় | নতুন বাজার বাসস্ট্যান্ড | UIU campus |
| 3 · আফতাবনগর | আফতাবনগর মেইন গেট | আফতাবনগর মেইন রোড | UIU campus |

The map is not to scale. The stops are placed in roughly the right directions from campus (Kuril to the north, Notun Bazar to the west, Aftabnagar to the south).

## Radio stations

| Station | Style | Instruments |
|---|---|---|
| ঢাকা রাশ এফএম ৯৯.৯ | বাউল (Baul) | khol, ghungur, kartal, ektara with its pitch bend, dotara, harmonium, a singing voice |
| নদী এফএম ৮৮.৮ | ভাটিয়ালি (Bhatiyali) | tanpura drone, soft khol, oar splashes, gliding bansuri |
| জ্যাম বিট ১০৪.২ | ঢাকাই ফিউশন | kick and snare, synth bass, dotara arpeggios, tabla fills |
| রক এফএম ৯১.৬ | বাংলা রক | distorted power chords and chugs, drums, a lead guitar, a dotara and ektara intro |

Melodies are written by the game itself from short motifs on Bangla folk scales, so the music keeps changing while each song keeps a recognisable hook.

## Run it locally

The game is one HTML file, but it loads three.js and two Google Fonts from the internet, so you need a connection.

```bash
git clone https://github.com/YOUR-USERNAME/dhaka-rush.git
cd dhaka-rush
python -m http.server 8000
# open http://localhost:8000 in your browser
```

Opening `index.html` by double-clicking may not work in every browser, so a local server is the reliable way.

## Deploy to GitHub Pages

1. Create a public repository, for example `dhaka-rush`, and upload the contents of this folder (`index.html`, `README.md`, `screenshots/`, `media/`).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and click **Save**.
4. After a minute or two the game is live at `https://YOUR-USERNAME.github.io/dhaka-rush/`.
5. Replace `YOUR-USERNAME` in this README with your GitHub username so the **Play now** link works.

Any static host works the same way (Netlify, Vercel, Cloudflare Pages): just serve `index.html`.

## How it is built

- **Rendering**: [three.js](https://threejs.org) r160 loaded from jsDelivr through an import map. ACES tone mapping, a gradient sky shader with sun, moon and stars, soft shadows that follow the player, fog that thickens at night and in the rain.
- **Procedural city**: a 6 × 6 block road grid plus an outer ring. Each block is split into lots and every building is generated with window textures, balconies, AC units, shopfronts, awnings, signboards and rooftop tanks. All geometry of the same material is merged per district chunk to keep draw calls low.
- **Textures**: drawn on `<canvas>` at load time: windows (with a separate night emissive map), asphalt with lane markings and potholes, pavers, grass, brick jali, rickshaw art, lungi checks, and a 2048 × 3072 atlas holding every Bangla signboard.
- **Traffic AI**: vehicles follow lanes on the road graph with left-hand-traffic offsets, take quadratic Bézier turns through intersections, keep a gap to whatever is ahead, honk when stuck and nudge through deadlocks. Police switch to a chase mode that steers toward you and routes around buildings with BFS on the road graph.
- **Physics**: an arcade bicycle model for steering, vehicles approximated by chains of circles, collisions against building boxes through a spatial hash.
- **Audio**: everything is synthesised with the Web Audio API: Karplus–Strong plucked strings for ektara and dotara, formant filters for the singing voice, waveshaper distortion for the rock guitar, and noise-based drums, rain and thunder. The radio is a look-ahead step sequencer.
- **Mobile**: a floating joystick, context-sensitive buttons, a layout that adapts to portrait and landscape, haptic feedback, and lighter graphics settings on touch devices.

## Project structure

```
dhaka-rush/
├── index.html          # the whole game: HTML, CSS and JavaScript in one file
├── README.md
├── screenshots/        # images used in this README
└── media/
    └── gameplay_10s.mp4
```

Inside `index.html`, the script is organised in sections:

| Section | What it does |
|---|---|
| world constants, renderer | grid size, lanes, districts, scene, lights, camera |
| geometry builder | merges boxes, cylinders and quads with vertex colours |
| canvas textures, sign atlas | all textures and Bangla signboards |
| people, vehicles | low-poly models for pedestrians and every vehicle type |
| road graph, colliders | lane following, turns, spatial hash, collision helpers |
| city generation | blocks, buildings, landmarks, UIU campus, river, wires |
| sky, audio, radio | day/night cycle, sound effects, the four stations |
| missions, wanted level | passengers, police chases, getting caught |
| fights, monsoon | accidents, fights, crowds, rain, floods, lightning |
| UIU, garage, modes | campus, bus routes, calling vehicles, day/night/rain |
| HUD, input, main loop | minimap, touch controls, keyboard, frame updates |

## Known limitations

- Needs an internet connection the first time (three.js and fonts load from CDNs).
- Low-end phones may run below 30 fps. The game already lowers shadow quality and the number of pedestrians on touch devices.
- The fullscreen button does not work inside some in-app browsers (for example, when the link is opened inside Facebook or Messenger). Opening it in Chrome or Safari works.
- The city layout is stylised, not a real map of Dhaka.

## বাংলায় সংক্ষেপে

**ঢাকা রাশ** হলো ঢাকা শহরের একটা 3D ওপেন-ওয়ার্ল্ড গেম, যেটা browser-এ চলে, কিছু install করতে হয় না।

- **কী করবেন:** রিকশা, সিএনজি, বাস বা UIU বাস চালিয়ে যাত্রী টানবেন, ভাড়া কামাবেন। জ্যাম, বৃষ্টি, জলাবদ্ধতা, পুলিশ আর রাস্তার ঝগড়া সামলাতে হবে।
- **UIU বাস:** কুড়িল, নতুন বাজার আর আফতাবনগর রুট থেকে স্টুডেন্টদের তুলে ক্লাস শুরুর আগে ক্যাম্পাসে পৌঁছে দিন।
- **মোড:** চলমান সময়, দিন, রাত বা বৃষ্টি। মেনু থেকে যেকোনো সময় বদলানো যায়।
- **রেডিও:** বাউল, ভাটিয়ালি, ঢাকাই ফিউশন আর বাংলা রক। সব গান গেমের ভেতরেই তৈরি হয়।
- **খেলবেন কীভাবে:** ল্যাপটপে `W A S D` দিয়ে চালান, `F` দিয়ে গাড়িতে উঠুন বা নামুন। মোবাইলে বাম দিকে আঙুল টেনে জয়স্টিক, ডান দিকের বোতাম দিয়ে বাকি সব।

## Credits

Made by **Muna**, CSE, United International University, with help from Claude (Anthropic).

Built with [three.js](https://threejs.org), fonts [Galada](https://fonts.google.com/specimen/Galada) and [Hind Siliguri](https://fonts.google.com/specimen/Hind+Siliguri) from Google Fonts.

The UIU building and bus are a fan tribute made by a student; this is not an official United International University project.
