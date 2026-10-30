# 🤖 Bot Customizer

**Customize your Garry's Mod bots like never before.**
Models, colors, voices, conversations, combat, dancing, profiles, inventory, saved characters, and a lot more, all from one simple menu.

> 🌐 **Language note:** The menu defaults to **Portuguese**. Go to the **Options tab**, pick your language, then **fully close and reopen** the Bot Customizer menu so everything translates correctly. Bots can talk in **Portuguese, English, Spanish and Russian** (some translation mistakes may exist). If you don't understand English well, feel free to paste this page into an AI translator or Google Translate. Enjoy! ❤️

---

## 📑 Table of Contents

- [Update Log](#-update-log)
- [Quick Start](#-quick-start)
- [Full Feature List](#-full-feature-list)
- [Adding Custom VOX Audio](#-adding-custom-vox-audio)
- [Doors & Navigation (Experimental)](#-doors--navigation-experimental)
- [Freecam Troubleshooting](#-freecam-troubleshooting)
- [FAQ](#-faq)
- [About & Credits](#-about--credits)

---

## 🆕 Update Log

### 🎃 Big Halloween Update 1.1

**💬 Bots can talk now!**
- Bots understand chat requests: follow, stop, come here, "excuse me", crouch, jump. They handle abbreviations, typos and even swearing.
- Languages: Portuguese, English, Spanish, Russian.
- Bot speech also appears in the chat, in color.
- Personality: friendly, sarcastic or dark, or automatic based on the bot's biography.
- Continuous conversation: after you talk to a bot, it stays in the conversation for 60 seconds.
- **Teach your bot:** "I'll teach you" or "when I say X, answer Y". Up to 1000 phrases per bot, answers up to 240 characters. Everything is saved.
- Bots can tell their biography and answer questions about it (best friend, where they live, who they hate). *Experimental.*
- Bots remember your name and gender.
- RP roles: soldier, master, villain and shopkeeper.
- Dating: bots can accept, stall or refuse.
- About 400 famous names, each bot with its own fixed opinion.
- Favorites by category and personality. Bots can sing (public-domain songs only).
- Fight lines when a fight starts, when hit, and when winning.
- Bots comment when they receive a new weapon.
- Vehicle talk, with the bot looking back and forth between front and player.
- Gender-aware speech (e.g. "curioso" becomes "curiosa" for female bots).
- Bots use the age, profession and origin you fill in on the Profile Sheet.
- You can still write as the bot from the **Bots** tab.
 

  **⚔️ Combat improvements**
- Bots now aim better with firearms and can shoot from a distance or up close.
- Bots may fight back against NPCs when they feel threatened.
- As an ally, the bot defends you if someone attacks you.

**🧭 Doors & navigation (experimental)**
- Bots can open doors and use a working navmesh to reach you.
- Locked door? The bot looks for another route, and if none exists it tries to unlock the door.
- Bots can use unlocking items (keys SWEP, Sonic Screwdriver, etc.) if you give them one.
- Without a suitable item, the bot tries the handle and gives up.
- Admin command `bc_nav_debug` shows how the bot is following you (may be in Portuguese).

**🎨 Menu & visuals**
- 8 new themes: purple, black & gray, red, hacker green, hot pink, white and pink, Halloween and Christmas.
- Speech bubble with the profile photo (GIF supported), with text, background and border colors.
- **Profile Sheet** tab: Age, Height, Profession, Origin and Trait, plus new Polaroid styles.
- Options and Profile now use dropdown menus for a cleaner layout.
- New Items mode: **Always hold**.
- Name above the head now works correctly on any model.
- Teleport: the bot now spawns facing you, and groups all face you.

**🛠️ New tabs & systems**
- **Inventory:** see the bot's items, equip/unequip weapons, reorder and remove items.
- **Characters:** save name, biography, colors, etc. and load them on another bot or in a later session.
- **Allies:** allied bots never damage you and won't turn on you after accidental hits. Their ally status is shown on their sheet. They also defend you if someone attacks you.
- **Permissions (admin):** choose who can use the menu and edit bots on public servers. *Experimental.*
- **VOX wheel (G):** quick voice lines, up to 2 pages.
- **Teleport wheel (T):** quick teleport, or click the center to make the bot follow you.

> ⚠️ This update was tested solo, with no beta testers. Bugs are expected, so please report anything odd!

🎃 **Have a spooky, fun-filled Halloween, and enjoy your time with your bots!** 

---

## 🚀 Quick Start
> You can also add bots through the menu, but it is recommended to first use the console when opening the server to avoid errors and stop bots from wandering with `bot_zombie 1`. After that, add or remove bots freely from the menu.

1. **Start a Multiplayer game** on any map (Multiplayer only).
2. **Spawn a bot:** open the console and type `bot`
3. **Stop it from wandering:** `bot_zombie 1`
4. **Open the menu:** press **F6** (changeable in Options) or type `bot_customizer`
5. **Pick your language** in the Options tab, then close and reopen the menu.
6. Go to the **BOTS tab**, select a bot, and start customizing!

---

## ✨ Full Feature List

<details>
<summary><b>🧍 Bot Management</b></summary>

- Add and remove bots from the menu
- Save and load characters (Characters tab)
- Tip: add bots via console first so they don't wander before you customize them

</details>

<details>
<summary><b>👩👨 Appearance & Identity</b></summary>

- Change **model** with live preview, edit **bodygroups**
- Custom **name**, **name color** (gradients supported), **title**, full **bio / profile card**
- **Profile photo** (static or GIF), Polaroid-style frames
- Profile Sheet: age, height, profession, origin, trait
- 7 menu themes

</details>

<details>
<summary><b>😀 Expressions</b></summary>

- Quick **facial expression** sliders
- Best with models that support **Face Poser**; if a model doesn't, that's normal, not a bug

</details>

<details>
<summary><b>💬 Conversation</b></summary>

- Chat commands, 4 languages, personalities, memory of your name, teachable phrases, biography Q&A, RP roles, dating, famous names, singing and more (see Update Log)
- Conversation mode in Options: quiet, normal or commentator

</details>

<details>
<summary><b>🔊 Voice / VOX</b></summary>

- Built-in VOX lines and **custom audio support**
- **VOX wheel** on the **G** key, up to 2 pages

</details>

<details>
<summary><b>⚔️ Combat & AI Behavior</b></summary>

- **Hostile mode**, **Follow mode**, and **Ally mode** (no damage to you)
- Optional retaliation when attacked (disable in Options)
- Self-healing during fights
- - Improved firearm accuracy, ranged or close-range shooting
- Bots can attack NPCs when threatened
- Allied bots defend you when you are attacked
- Weapons or held props, up to **3 loadout slots**, plus a full **Inventory tab**

</details>

<details>
<summary><b>🎒 Items & Props</b></summary>

- Real weapon **or** decorative prop version
- Free-choice prop on your hand or the bot's hand
- **Always hold** mode
- Hold a mic or any prop while dancing with ACTMOD

</details>

<details>
<summary><b>🚗 World Interaction</b></summary>

- Bots enter your vehicle and talk to you inside it
- **Teleport wheel (T):** instant teleport or follow
- Door opening and navmesh pathing (experimental)
- **Freecam** for cinematic shots

</details>

<details>
<summary><b>💃 Dancing (ACTMOD)</b></summary>

- Full **ACTMOD** compatibility, combine with props while dancing

</details>

<details>
<summary><b>🔐 Server Permissions</b></summary>

- Admins choose who can use the menu and edit bots, to avoid griefing on public servers (experimental)

</details>

---

## 🎵 Adding Custom VOX Audio

1. Go to your Garry's Mod folder, usually:
   ```
   C:\Program Files (x86)\Steam\steamapps\common\GarrysMod\garrysmod
   ```
2. Create this folder structure (create any missing folders):
   ```
   sound\bot_customizer\voices
   ```
3. Drop your audio files in `voices`. **WAV recommended**, MP3 should also work.
4. Your files appear in the VOX system and on the **G** wheel (up to 2 pages).

---

## 🚪 Doors & Navigation (Experimental)

- Bots open doors and use the navmesh to reach you, but results depend on the map. They may get lost, stuck on stairs or glitch on some doors.
- Locked door: the bot searches for another exit. If there is none, it tries to unlock the only door in front of it.
- To let a bot unlock doors, give it an item that does it (keys SWEP, Sonic Screwdriver, etc.). It works best if the item's use is configured well. Without one, the bot tries the handle and gives up.
- Admins can run `bc_nav_debug` to see how a bot is following you.

---

## 🎥 Freecam Troubleshooting

- Issues with Freecam? As a last resort, restart the server.
- Stuck on the ground after leaving Freecam? Press **V**, float upward, then release it.

---

## ❓ FAQ

**Why is the menu in Portuguese by default?**
That's just the default language. Change it anytime in the **Options tab**, then close and reopen the menu so the translation applies fully.

**Did you use AI to make this?**
Yes. I used AI assistance mainly for the **Lua logic** behind more complex systems (bot combat AI, Freecam, dialogue, navigation, etc.). The original **idea, design direction, and structure** of the addon are entirely mine. This addon took over a month of continuous testing, fixing, and revising. It's not something you just generate and ship.

**Can I use an image/asset you used and you don't have rights to?**
If you're the original owner of any image used (like backgrounds) and want it removed or credited differently, just contact me. I'll remove or swap it, no problem.

**Can I suggest a feature or report a bug?**
Absolutely, suggestions and bug reports are welcome! Just keep in mind updates might take a while since I juggle other projects.

**Can I make my own improved version?**
Go for it! Just please credit the original idea/addon.

**Why did you make this?**
Honestly, I wanted bots for screenshots, videos, and roleplay, and just wanted something fun (and some company) in Garry's Mod. I figured other people probably wanted the same thing, so I released it.

---

## About & Credits

Created solo, with AI assistance on complex Lua logic (combat AI, Freecam, dialogue, navigation, and similar systems). Idea, design, and structure are original.

- **GitHub:** [LaryssaHtml](https://github.com/LaryssaHtml)
- **Instagram:** [@emotionalssciencegirl](https://www.instagram.com/emotionalssciencegirl/)
- **YouTube:** [Lyssa](https://www.youtube.com/@lary9lf)

Skull icon PNG sourced from rawpixel.com. Contact me for any credit/removal requests regarding other assets.
