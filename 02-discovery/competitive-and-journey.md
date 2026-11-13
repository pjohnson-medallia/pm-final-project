# Competitive Analysis & Journey Map

> **Module 2 · Lab 2 — ★ Deliverable 2.** Repo file `02-discovery/competitive-and-journey.md` — part of your submission.
> Do the lab in the **Module 2 · Exercise 2 Guide** (linked from the Module 2 deck), then click **⬇ Download .md** — it saves as this exact file. Commit it here.
> It becomes the **Competitive Analysis & Journey Map** slide of your Module 6 final deck. Builds on your `ai-synthesis.md` and your Module 1 `problem-hook.md`.

## Responses

- **Role, who are you solving for?:** _(not filled in)_
- **Goal, what is this user ultimately trying to achieve?:** _(not filled in)_
- **Friction, the main barrier (moment of misery) stopping them:** _(not filled in)_
- **External tools the user is forced to use:** _(not filled in)_
- **The process, the 3–5 manual steps they take:** _(not filled in)_
- **Core frustration, where the process feels most "broken":** _(not filled in)_
- **The evidence, a quote or behavior from the research:** _(not filled in)_
- **Journey map, a shareable link or the map file you committed:** _(not filled in)_

---

## Future-State Journey Map: Delivery Driver

**Persona:** A delivery driver with three years on the platform who completes stops in the field, often in bad conditions.
**Goal:** Mark each stop delivered quickly, so he can move on to the next one. *(Inferred from the research.)*
**Friction:** Marking a stop delivered takes three taps across three screens, "in the rain, at a doorstep, with a package in one hand," so he has started texting his dispatcher instead (UXR-01, BUG-2055).
**Strategy:** Reclaim operational simplicity by stripping away legacy noise and ensuring the tool is the fastest for everyday work.

### Journey

#### 1. Start the shift (UXR-11, BUG-2079)
- **User action:** Taps Start Route on the home screen → route loads immediately.
- **Internal state:** Confident, not hunting menus → starts the day without friction.
- **Pain point addressed:** Core actions buried 2-3 levels deep → Start Route sits up front.

#### 2. Complete at the door (UXR-01, BUG-2055)
- **User action:** Taps one large Mark Delivered button → stop completes in one tap.
- **Internal state:** Hands full, rain falling, but unworried → stays in the app, stops texting.
- **Pain point addressed:** Three taps across three screens → single tap completes delivery.

#### 3. Confirm and capture proof (UXR-07, BUG-2061)
- **User action:** Snaps one photo; upload retries itself → no repeat attempts needed.
- **Internal state:** Certain it worked → stops second-guessing and retaking photos.
- **Pain point addressed:** Silent upload failures, no confirmation → visible success status on every photo.

#### 4. Move on (UXR-01, UXR-09, UXR-12)
- **User action:** Glances at the next stop and drives → no manifest or message needed.
- **Internal state:** Trusts the app as the only record → drops paper and WhatsApp backups.
- **Pain point addressed:** Texting the dispatcher as the real system → status reaches the board automatically.

### Competitive advantages over the manual workaround
1. **Faster than texting:** One tap beats composing a message → delivery recorded in seconds.
2. **Trustworthy record:** Completion logs status automatically → dispatchers stop relying on WhatsApp.
3. **No duplicate effort:** Photo retries and confirmation → no retakes, screenshots, or paper backups.

### Notes
- The value prop references "admin users," but this persona is a frontline driver. Align the wording before external use.
- Stages 3 and 4 depend on reliability fixes (BUG-2061, BUG-2072), not only complexity reduction.
- Internal states in Stages 2 and 4 are inferred; the research documents the friction and the workaround, not post-fix sentiment.
