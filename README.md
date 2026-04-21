# 🕹️ Joystick Tester

A web-based joystick and gamepad input tester built with pure HTML/CSS/JS using the [Gamepad API](https://developer.mozilla.org/en-US/docs/Web/API/Gamepad_API). Styled like Windows' **joy.cpl** with a square crosshair pad, vertical sliders, and a 3×3 grid POV hat indicator. No dependencies, no build step.

---

## Quick Start

### Run Online (GitHub Pages)

Host this on GitHub Pages for free:

1. [Create a new GitHub repository](https://github.com/new)
2. Name it `joystick-tester`
3. Upload `index.html` and `README.md`
4. Go to **Settings → Pages** → Deploy from branch `main` → Save
5. Your site will be live at `https://YOUR-USERNAME.github.io/joystick-tester/`

### Run Locally

No build or server required—open directly in your browser:

```bash
# Just open the file
open index.html

# Or serve locally for better compatibility
python3 -m http.server 8080
# Visit http://localhost:8080
```

---

## Features

- **joy.cpl-style UI** — square X/Y pad with grid, vertical Z/throttle slider, 3×3 hat switch indicator
- **Auto-detects device type** — flight sticks and joysticks get single-stick layout; gamepads get dual-stick layout
- **Configurable axis mapping** — assign any axis to X, Y, Z, or hat switches
- **Hat switch support** — single-axis POV hat decoding with proper center and 8-direction detection
- **Multiple devices** — connect and test multiple controllers simultaneously
- **All raw axes displayed** — with labels showing which role each axis plays
- **Event log** — connect/disconnect history

## Supported Devices

- **Flight Sticks** — Thrustmaster T16000M, VKB Gladiator, Virpil MongoosT-50
- **HOTAS** — Thrustmaster Warthog, Saitek X-52/X-55/X-56, Winwing
- **Gamepads** — Xbox Series, PlayStation DualSense, Switch Pro
- **Racing Wheels** — Logitech G29/G923, Thrustmaster T300
- **Generic USB/Bluetooth** — any HID-compliant joystick or gamepad

## Browser Support

Works in any modern browser with Gamepad API support:
- ✅ Chrome / Edge
- ✅ Firefox
- ✅ Safari 16.4+
- ✅ Opera

> **Note:** Browsers require at least one button press to activate a gamepad for security reasons.

---

## License

MIT — use freely for personal or commercial purposes.
