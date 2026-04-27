# Later.com — Week 1 Schedule Runbook

**Goal:** queue all 4 carousel posts to Instagram, then mirror to Facebook via Later's "Duplicate" feature. Total time: ~20–25 minutes hands-on.

**Compressed schedule (already approved):**
| Post | Title | Schedule (AEST) |
|---|---|---|
| 1 | Sydney vs Melbourne · Senior Dev Salaries 2026 | **Sat 25 Apr · 5:00 pm** |
| 2 | 5 Red Flags in a Tech Interview | **Sun 26 Apr · 9:00 am** |
| 3 | Placement Win · Senior Backend Engineer | **Sun 26 Apr · 4:00 pm** |
| 4 | Take-home Tasks Are Killing Aussie Tech Hiring | **Mon 27 Apr · 7:00 am** |

---

## One-time setup (do this once before Post 1)

1. Open `https://app.later.com/9EP1J/schedule/calendar` in Chrome.
2. At the top of the calendar, **click the Instagram profile chip** (`aussiete...`, the one with the IG icon, NOT the FB icon). It should have a checkmark when active. This makes Instagram the default profile for the next composer.
3. Dismiss any marketing popups (NPS survey, "Fresh supplies" promo, etc.) by clicking the × on each.

---

## Per-post flow (repeat 4 times)

### General steps

1. Click **`+ Create Post`** (purple button, top-left of calendar).
2. Modal opens. Confirm the profile chip at top says **`@aussietechtalent` · Instagram** (with the IG icon). If it says Facebook, close the modal, click the IG profile chip on the calendar, then re-open Create Post.
3. **Drag and drop** the 7 PNG slides for the post (in order, slide 01 → 07) onto the media area on the left. Or click **Add Media** → **Upload from device** and select all 7 PNGs together. Later will arrange them as a carousel automatically.
4. **Verify slide order**: covers should be slide 1, CTAs slide 7. If a slide is out of order, drag to reorder in Later.
5. **Open the caption file** (paths below) in your text editor, **copy the entire contents** (caption + hashtags), paste into Later's "Post Caption" field.
6. **Set the schedule time** — click the date/time at the top of the modal, pick the date and time per the table above (AEST).
7. **Verify Auto Publish is ON** — the lightning-bolt indicator at the top should be lit. If it's off, switch it on so Later actually publishes (not just notify-and-forget).
8. Click the purple **`Schedule Post`** button bottom-right.
9. Modal closes. The post should now appear as a pink/orange block on the calendar at the scheduled time.

### Post 1 — Mon Market Monday · Sydney vs Melbourne
**Schedule:** Sat 25 Apr · 5:00 pm AEST
**PNGs to upload (in order):** open this folder and select all 7 in the file picker:
`/AussieTechTalent/CurrentMonth/Week1/Ready/Post01_Designs/`
- `Post01_Slide_01_Cover.png`
- `Post01_Slide_02_Sydney.png`
- `Post01_Slide_03_Melbourne.png`
- `Post01_Slide_04_TheCatch.png`
- `Post01_Slide_05_ContractRates.png`
- `Post01_Slide_06_OurTake.png`
- `Post01_Slide_07_CTA.png`

**Caption file** (copy whole contents): `/AussieTechTalent/CurrentMonth/Week1/Ready/Post01_Mon_MarketMonday_caption.txt`

> ⚠ Salary figures are time-sensitive. The post-1 caption itself is narrative-only — the salary numbers live on the carousel slides. The slides match your published RATES PDF: $170–200k Sydney, $145–175k Melbourne. Already verified.

### Post 2 — Wed Wisdom Wednesday · 5 Red Flags
**Schedule:** Sun 26 Apr · 9:00 am AEST
**PNGs:** `/AussieTechTalent/CurrentMonth/Week1/Ready/Post02_Designs/Post02_Slide_01_Cover.png` through `Post02_Slide_07_CTA.png`
**Caption file:** `/AussieTechTalent/CurrentMonth/Week1/Ready/Post02_Wed_WisdomWednesday_caption.txt`

### Post 3 — Fri Featured Friday · Placement Win
**Schedule:** Sun 26 Apr · 4:00 pm AEST
**PNGs:** `/AussieTechTalent/CurrentMonth/Week1/Ready/Post03_Designs/Post03_Slide_01_Cover.png` through `Post03_Slide_07_CTA.png`
**Caption file:** `/AussieTechTalent/CurrentMonth/Week1/Ready/Post03_Fri_FeaturedFriday_caption.txt`

> The caption already includes the composite-account framing line at the bottom. Don't strip it.

### Post 4 — Sun Story Sunday · Take-home Tasks
**Schedule:** Mon 27 Apr · 7:00 am AEST
**PNGs:** `/AussieTechTalent/CurrentMonth/Week1/Ready/Post04_Designs/Post04_Slide_01_Cover.png` through `Post04_Slide_07_CTA.png`
**Caption file:** `/AussieTechTalent/CurrentMonth/Week1/Ready/Post04_Sun_StorySunday_caption.txt`

---

## Mirror to Facebook (after all 4 IG posts are queued)

1. On the Later calendar, click on a scheduled IG post (a pink/coloured block).
2. The post detail panel opens. Look for a **`Duplicate`** or **`Copy to`** option (typically three-dot menu or right-click).
3. Choose to copy to the **Aussie Tech Talent · Facebook** profile.
4. Later opens a new composer pre-filled with the same media + caption, scoped to FB.
5. **For Facebook**: change Post Type to "Page Post" if not already (FB's default).
6. Schedule for the same time as the IG post (or 5–10 min offset if you want to avoid identical-timestamp duplicates).
7. Click Schedule Post.
8. Repeat for Posts 2, 3, 4.

If "Duplicate" isn't visible: open each post fresh, switch profile to Facebook in the composer, drag in the same PNGs, paste caption, schedule. ~3 min per FB post.

---

## After everything is queued

- Calendar should show 4 IG posts + 4 FB posts (8 pink/coloured blocks total) on Sat 25 / Sun 26 / Mon 27.
- Quota indicator top-right should read **26 Instagram Posts Left** (was 30, used 4).
- Tell me "all 4 queued" and I'll mark the cycle as in-flight in memory. Friday 5pm AEST scheduled task will then update Leads_Log with the published rows automatically.

---

## If something goes wrong

- **A post fails to publish:** Later sends an email + dashboard notification. Common causes: IG token expired (re-authorise in Later → Social Profiles), or media format issue (carousels need every image at the same aspect ratio — ours are all 1080×1350 so they should be fine).
- **A slide's order is wrong on the live IG post:** delete the IG post, redo via Later (Later doesn't let you reorder after publish).
- **The caption is wrong on the live post:** edit on Instagram directly — Later doesn't let you edit a published caption.
- **You change your mind on a schedule:** open the queued post in Later, click the date/time, change it. Drag-on-calendar also works.
