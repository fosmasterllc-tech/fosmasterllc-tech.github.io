# BODY RIOT

**a one-person party for every inch of you**

---

## What Is This

BODY RIOT is a body-positive hype app built for every body — disabled, fat, scarred, soft, strong, all of it. Seven modes. Eyes-free operable. Full accessibility. Built in one HTML file, zero dependencies, runs on your phone right now.

**Status: BUILT** — Live and playable at `fosmasterllc-tech.github.io/body-riot.html`

---

## The Modes

**Hype Cannon** — Tap FIRE and get blasted with unfiltered body-positive hype. Spoken. Big text. Haptics buzz. Confetti flies.

**Compliment Slot Machine** — Shake your phone or pull the lever. Three randomized reels spin out something like *"Your thighs are majestic royalty."* Jackpot siren. Haptic ding.

**Strut Mode** — An announcer walks YOU out like a superstar. *"Ladies and gentlemen, the sexiest person in this room is about to walk out. That's you."* House lights down. Adrenaline up.

**Affirmation Rave** — One-person disco. Beat drops. Neon pulses. Affirmations land on the bass. Photosensitivity-safe (calm pulse mode on by default).

**Shameless Booth** — Type or say something you've been hard on yourself about. The app absorbs it, reframes it, roasts it with love. *"Someone out there is absolutely obsessed with exactly that."*

**Booty Metronome** — Shake your phone, wiggle, move however. The accelerometer counts every motion and cheers you on. No sensor? Manual tap button works too.

**Glow-Up Mirror** — Front camera + neon glow + a crown. Nothing recorded, nothing sent anywhere. Audio-only fallback if you don't want the camera.

---

## Accessibility

**Three-channel output on everything:**
- **Visible text** (big, high-contrast, strontium aqua on midnight black)
- **Spoken aloud** (speech synthesis, fully voice-navigable)
- **Haptics** (vibration feedback on every action)

**Full keyboard nav.** All buttons. All modals. Escape closes. Tab moves through.

**Screen reader ready.** ARIA live regions. Skip links. Proper semantics. Tested with VoiceOver.

**Reduce motion respected.** No confetti, no flashing animations if you've set that OS preference.

**Settings panel** — Turn voice on/off, sound effects on/off, haptics on/off, reduce motion on/off. Persists to localStorage.

---

## Technical

- **Single HTML file** — no build step, no npm, no CDN drama
- **Vanilla JS** — no frameworks, no dependencies
- **Web Audio API** — synth + noise for all sounds (no samples)
- **Accelerometer** — motion tracking for Booty Metronome
- **Camera API** — local, device-only, nothing sent (Glow-Up Mirror)
- **localStorage** — persists settings; falls back to memory if blocked
- **Speech Synthesis API** — native TTS for voice output
- **Vibration API** — haptic feedback on supported devices

---

## The Mandate

10% of FOS Master LLC's NET revenue (after all costs and payouts are settled) goes directly to pediatric cancer research, preferably through The V Foundation.

The 10% footer is hardcoded into every page. It's not optional. It's not a donation button. It's a ledger line.

---

## How to Use

1. Download or clone `body-riot.html`
2. Open it in any modern browser (mobile or desktop)
3. Tap FIRE to start, or pick a mode from the grid
4. All modes are fully voice-navigable — say "fire", "slot", "strut", "rave", "booth", "booty", or "mirror"

**No setup. No login. No tracking. Runs entirely on your device.**

---

## Colors

- **Strontium aqua:** `#00FFFF` — accent, glow, highlights
- **Midnight black:** `#050507` — background, safe for eyes in daylight
- **Gold:** `#FFD700` — reserved for the 10% charity footer only

---

## Browser Support

Chrome/Edge/Safari/Firefox on iOS, Android, desktop. Requires:
- Web Audio API (for synth)
- Geolocation or Accelerometer (for motion modes, optional fallback exists)
- Camera API (for mirror, optional fallback exists)
- Speech Synthesis API (for voice, optional fallback exists)

If a sensor or API isn't available, the app degrades gracefully. No hard failures.

---

## License & Notes

Built by FOS Master LLC for the Black Tide Ultimate Frisbee community and everyone who deserves to feel celebrated exactly as they are.

Temperature zero on the facts: Everything in this app is tested. Everything works. Nothing is hallucinated. Sensors are real. Copy is hard-R swagger and body-positive. The 10% is locked in.

If you find a bug, open an issue. If you want to contribute, fork and PR.

---

**Go celebrate yourself. You earned it.**
