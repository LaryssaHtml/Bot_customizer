# 🤖 Bot Customizer

**Customize your Garry's Mod bots like never before.**
Models, colors, voices, combat, dancing, profiles, and a lot more — all from one simple menu.

> 🌐 **Language note:** The menu defaults to **Portuguese**. To change it, go to the **Options tab**, pick your language, then **fully close and reopen** the Bot Customizer menu so everything translates correctly.

---

## 📑 Table of Contents

- [Quick Start](#-quick-start)
- [Full Feature List](#-full-feature-list)
- [Adding Custom VOX Audio](#-adding-custom-vox-audio)
- [Freecam Troubleshooting](#-freecam-troubleshooting)
- [FAQ](#-faq)
- [About & Credits](#-about--credits)

---

## 🚀 Quick Start

1. **Start a Multiplayer game** on any map (this addon only works in Multiplayer).
2. **Spawn a bot** — open the console and type:
   ```
   bot
   ```
3. **Stop it from wandering off** — right after, type:
   ```
   bot_zombie 1
   ```
   > Do this *before* adding more bots, or they'll all be walking around the map instead of standing still for you to customize.
4. **Open the menu** — press **F6** (default keybind, changeable in Options) or type:
   ```
   bot_customizer
   ```
5. **Pick your language** in the Options tab, then close and reopen the menu.
6. Go to the **BOTS tab**, select a bot, and start customizing!

---

## ✨ Full Feature List

<details>
<summary><b>🧍 Bot Management</b></summary>

- Add bots directly from the menu
- Remove bots directly from the menu
- Tip: add bots via console (`bot` + `bot_zombie 1`) first so they don't wander before you customize them

</details>

<details>
<summary><b>🎨 Appearance</b></summary>

- Change the bot's **model**, with live preview before applying
- Edit **bodygroups** (for models that support them)

</details>

<details>
<summary><b>🪪 Identity & Profile</b></summary>

- Custom **name**
- **Name color**, including gradient/degradê support
- Custom **title** under the name
- Full **bio / bot profile card**
- **Profile photo** — supports static images or GIFs
- **Polaroid-style** photo option

</details>

<details>
<summary><b>😀 Expressions</b></summary>

- Quick **facial expression** sliders (smile, anger, sadness, etc.)
- Works best with models that support **Face Poser** — some bots may not visibly react if their model doesn't support it, that's normal, not a bug

</details>

<details>
<summary><b>🔊 Voice / VOX</b></summary>

- Built-in VOX voice lines
- **Custom audio support** — add your own voice files (see [Adding Custom VOX Audio](#-adding-custom-vox-audio))

</details>

<details>
<summary><b>⚔️ Combat & AI Behavior</b></summary>

- **Hostile mode** — bots fight each other or the player
- **Follow mode** — bots follow you around
- Bots **react to being attacked**, even accidentally — if you don't want a fight, this can be **disabled in the Options tab** so accidental hits don't trigger retaliation
- Bots can **self-heal** during a fight
- Give bots **weapons** or **held props** (up to **3 loadout slots** to switch between)

</details>

<details>
<summary><b>🎒 Items & Props</b></summary>

- Give the bot a real weapon **or** a decorative prop version of it
- Attach a **free-choice prop** to your own hand or the bot's hand
- Hold a **microphone or any other prop** while dancing with ACTMOD

</details>

<details>
<summary><b>🚗 World Interaction</b></summary>

- Make bots **enter your vehicle**
- **Teleport bots** to your location instantly
- **Freecam** system for cinematic shots (see troubleshooting below)

</details>

<details>
<summary><b>💃 Dancing (ACTMOD)</b></summary>

- Full compatibility with **ACTMOD** — make your bots dance
- Combine with props (hold a mic, an instrument, anything) while dancing

</details>

---

## 🎵 Adding Custom VOX Audio

1. Go to your Garry's Mod installation folder, usually:
   ```
   C:\Program Files (x86)\Steam\steamapps\common\GarrysMod\garrysmod
   ```
2. Create this folder structure inside it (create any missing folders manually):
   ```
   sound\bot_customizer\voices
   ```
3. Drop your audio files inside the `voices` folder.
   - **WAV recommended**, MP3 should also work, other formats may vary.
4. Your files will now show up in the VOX system inside Bot Customizer.

---

## 🎥 Freecam Troubleshooting

- Having issues with Freecam? As a last resort, try **restarting the server**.
- Stuck on the ground after leaving Freecam? Press **V**, float upward, then release it — you should be able to move normally again.

---

## ❓ FAQ

**Why is the menu in Portuguese by default?**
That's just the default language. Change it anytime in the **Options tab**, then close and reopen the menu so the translation applies fully.

**Did you use AI to make this?**
Yes — I used AI assistance mainly for the **Lua logic** behind more complex systems (bot combat AI, Freecam, etc.). The original **idea, design direction, and structure** of the addon are entirely mine. This addon took about a month of continuous testing, fixing, and revising — it's not something you just generate and ship.

**Can I use an image/asset you used and you don't have rights to?**
If you're the original owner of any image used (like backgrounds) and want it removed or credited differently, just contact me — I'll remove or swap it, no problem.

**Can I suggest a feature or report a bug?**
Absolutely, suggestions and bug reports are welcome! Just keep in mind updates might take a while since I juggle other projects.

**Can I make my own improved version?**
Go for it! Just please credit the original idea/addon.

**Why did you make this?**
Honestly — I wanted bots for screenshots, videos, and roleplay, and just wanted something fun (and some company) in Garry's Mod. I figured other people probably wanted the same thing, so I released it.

---

## 🙏 About & Credits

Created solo, with AI assistance on complex Lua logic (combat AI, Freecam, and similar systems). Idea, design, and structure are original.

- **GitHub:** [LaryssaHtml](https://github.com/)
- **Instagram:** [@emotionalssciencegirl](https://www.instagram.com/)
- **YouTube:** Lyssa

Skull icon PNG sourced from rawpixel.com — contact me for any credit/removal requests regarding other assets.
