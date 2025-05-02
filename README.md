

# 🛑 OG-Studios-Speed-Limits

**Author:** OGDev Studios
**Script Name:** `OG-Studios-Speed-Limits`
**Type:** Visual/Immersion Add-on
**Framework:** FiveM / GTA V
**Status:** Plug-and-play ✅

---

## 📋 What Is This?

**OG-Studios-Speed-Limits** is a simple and immersive script that places **speed limit signs** across roads in your GTA V/FiveM map. Whether you're looking to:

* Add realism to driving RP
* Help traffic cops with ticket RP
* Reinforce legal speed zones
* Create more immersive environments

This script gives your map that "lived-in" feel — without being heavy or complex.

---

## 🪧 Features

* 🛣️ Places visible **speed limit sign props** along roads
* ⚙️ Fully configurable sign types and positions
* 🧊 Uses GTA V-native props (lightweight and efficient)
* 🔧 Easily add, move, or remove signs using coordinate lists
* 🚓 Great for **LSPD/BCSO traffic enforcement roleplay**

---

## 🧩 Configuration

Signs are placed by spawning map objects using coordinates and models. You can change:

* Sign model (e.g., `prop_sign_road_01`, `prop_sign_freewayentrance`)
* Placement coords
* Rotation to match road angles

Example object spawn:

```lua
local sign = CreateObject(GetHashKey("prop_sign_road_01a"), x, y, z, false, false, true)
SetEntityHeading(sign, heading)
FreezeEntityPosition(sign, true)
```

---

## 📦 Installation

1. Download or clone the script:

   ```
   git clone https://github.com/SheLovesLqwid/OG-Studios-Speed-Limits
   ```
2. Drop the folder into your `resources` directory.
3. Add it to your `server.cfg`:

   ```bash
   ensure OG-Studios-Speed-Limits
   ```
4. Adjust placements if needed in the config or script file.

---

## 🔗 GitHub Repository

📂 [https://github.com/SheLovesLqwid/OG-Studios-Speed-Limits](https://github.com/SheLovesLqwid/OG-Studios-Speed-Limits)

---

## 📢 Promo / Announcement Message

Here’s something you can post in your Discord server or FiveM resource channel:

---

🛑 **OG-Studios-Speed-Limits** – New Release!
Add **immersive speed limit signs** all over your map for realism, traffic RP, or just aesthetics.

🚗 Great for civilian driving, LEO speed enforcement, and immersive traffic stops.
🧩 Easy config – plug-and-play with editable coordinates & props.
⚡ Lightweight and client-friendly.

📥 Download now:
👉 [Click Me!!!](https://github.com/SheLovesLqwid/OG-Studios-Speed-Limits)


