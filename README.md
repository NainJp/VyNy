# VyNy — Ear First Computing

> Hear what matters — without looking at the screen.

VyNy reads your notifications, messages, and events out loud with synthesized speech — so your eyes stay on the world, not your screen. From everyday life on the move to deep focus at your desk, it all runs on one idea: **ears first**.

VyNy is an umbrella for more than one thing, and they are not the same kind of project. Some are **products** we build with a roadmap; others are **Lab** experiments we share as-is.

---

## Projects

### Products

Actively developed, with a roadmap and support.

| Platform | For | Status | Get it |
|---|---|---|---|
| **VyNy for Android** | Everyday & on the move — notifications, messages, and the time read aloud on any Bluetooth earphone | Available | [Google Play](https://play.google.com/store/apps/details?id=jp.nain.aplay&utm_source=github&utm_medium=readme&utm_campaign=vyny_android) |
| **VyNy for iOS** | The same, on iPhone | Planned | Coming soon |

### Lab

Experimental side projects. Shared **as-is, with no support** and no guarantee of fixes or updates. Use at your own discretion.

| Platform | For | Status | Get it |
|---|---|---|---|
| **VyNy for Mac** | Developer focus — hear when Claude Code finishes, breaks, or needs you, so you stop polling the screen | Available | [Releases](../../releases) — download the latest `.dmg` |

---

## VyNy for Mac (Lab)

> Keep coding. Hear when Claude Code is done — stop polling the screen.

**Today, VyNy for Mac speaks Claude Code's status out loud** — when a run finishes, when it's waiting on your input, or when it breaks — so you don't have to keep glancing back at the screen while it works. Kick off a long run, switch to something else, and let your ears tell you the moment it needs you. Running several sessions at once? You can't watch them all — so let them speak.

### Why

Watching Claude Code work means babysitting a screen — is it done? stuck? waiting on me? Polling for that is pure focus tax, and it gets worse the more sessions you run in parallel. VyNy speaks the four events that actually interrupt you — **Completion, Error, Reply, Urgent** — the instant they happen, so you keep your eyes on real work and come back only when it matters.

### How it works

| Element | Detail |
|---|---|
| **On-device TTS** | Speech is synthesized on your device. Your text is never sent to an external server. |
| **4-event model** | Claude Code's activity is normalized into just four classes: Completion / Error / Reply / Urgent. |
| **3 modes** | Desk / Run / Walk switch the speaking behavior to fit what you're doing. |

### Install

> Provided as-is. No support or warranty — see [SUPPORT.md](SUPPORT.md).

1. Download the latest `.dmg` from [Releases](../../releases).
2. Open the DMG and drag **VyNy** into your **Applications** folder.
3. Launch it. The build is notarized by Apple, so it should open directly. If a warning appears, go to **System Settings → Privacy & Security** and choose **Open Anyway**.

---

## Feedback

- **Bug reports** → [Issues](../../issues) (please follow the template and include reproduction steps)
- **Questions, ideas, requests, chat** → [Discussions](https://github.com/NainJp/VyNy/discussions)

Replies are best-effort and not guaranteed — especially for Lab projects.

---

## Support

See [SUPPORT.md](SUPPORT.md) for the full policy.
