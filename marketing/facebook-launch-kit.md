# CROWNLINGS — Facebook Page launch kit

Everything needed to stand up the Page. sIRImeta creates the Page itself (a Facebook
Page is tied to a real personal login, so that click stays with sIRImeta); everything
below is ready to paste in once it exists.

## 1. Create the Page

facebook.com → Menu → **Pages** → **Create new Page** →
- Page name: **CROWNLINGS**
- Category: **Video Game** (or "App Page" if Video Game isn't offered — pick whichever
  Facebook's picker actually shows first)
- Username to try, in order (first one available wins): `@PlayCrownlings`,
  `@CrownlingsGame`, `@Crownlings.the.game`

## 2. Profile picture & cover photo

Both are pre-composited and sitting in `marketing/assets/`:
- `fb_profile_1024.png` — 1024×1024. Facebook always displays this cropped to a
  circle, so the square corners never show.
- `fb_cover_1640x924.png` — 1640×924 (2x the recommended 820×462, for retina).

Just upload both as-is.

## 3. About / bio text

**Short bio** (Page's one-line summary):
> A desktop creature-raising game. Raise it kind, or watch it become something else. Coming to Steam.

**Thai line** (add to the same field or the "Our Story" long-form box):
> เกมเลี้ยงมอนสเตอร์บนเดสก์ท็อป เลี้ยงดีได้ร่างสดใส เลี้ยงพลาดได้อีกร่าง กำลังจะไปลง Steam

**Long About / Our Story:**
> CROWNLINGS is a desktop creature-raising game currently in development. Every
> crownling carries a dormant crown — raise it well and it grows into a bright,
> loyal companion; neglect it, or expose it to the wrong crown, and it awakens a
> corrupted form instead. Raise, evolve, breed bloodlines, and battle in async PvP.
> This page is where the game's progress gets shared first. Follow along, and
> Wishlist on Steam once the store page goes live.

## 4. First 3 posts (drafted, ready to paste)

**Post 1 — Pomlet reveal** (use `assets/img/bright_adult.png` from the site's `assets/img/`)
> ทำความรู้จัก "Pomlet" 👑 ตัวละครหลักของ CROWNLINGS เกมเลี้ยงมอนสเตอร์บนเดสก์ท็อปที่กำลังพัฒนาอยู่
>
> ทุกตัวมีมงกุฎที่หลับใหลอยู่ข้างใน — เลี้ยงดีแค่ไหน มงกุฎนั้นจะตอบสนองแบบนั้น
>
> กด Follow ไว้เลย แล้วจะทยอยโชว์พัฒนาการให้ดูเรื่อยๆ ครับ 🐾

**Post 2 — "5 Crowned Corruptions" carousel** (attach the 5 gallery images from
`assets/img/`: ember_adult, still_adult, riven_child, gorge_adult, sleep_child)
> ถ้าเลี้ยงพลาด... นี่คือสิ่งที่รอคุณอยู่ 🔥❄️⚡🟢🩸
>
> ธาตุเดียวกัน มงกุฎเดียวกัน แต่กลายพันธุ์ไปคนละทางเมื่อถูกครอบครองด้วยความมืด — Ember (ไฟ), Still (น้ำแข็ง), Riven Sky (สายฟ้า), Gorge (ความโกลาหล), The Sleepless (เลือด)
>
> ชอบร่างไหนที่สุด คอมเมนต์บอกกันหน่อย 👇

**Post 3 — Dev-progress teaser** (video: the same `assets/video/teaser.mp4` used
on the site, or a short capture of the Riven Sky / Gorge 3D models if a screen
recording is made from Godot)
> อัปเดตความคืบหน้า CROWNLINGS 🛠️
>
> ตอนนี้กำลังต่อยอดโมเดล 3D และระบบอีกหลายส่วนอยู่ ยังอีกไกลกว่าจะเสร็จ แต่ตั้งใจทำเต็มที่ทุกวัน
>
> ใครอยากตามดูพัฒนาการแบบใกล้ชิด กด Follow เพจนี้ไว้ได้เลยครับ จะมาอัปเดตเรื่อยๆ

## Notes / things to know before posting

- There's also a Discord now: https://discord.gg/dKuBJ2Vfy — mention/pin it alongside
  the Page (add it to the About text and maybe as the Page's action button) once it's
  renamed from Discord's default "เซิร์ฟเวอร์ของ Jakkkar" to CROWNLINGS with the same
  icon used here (`discord_icon_1024.png`).
- The video used on the site (`assets/video/teaser.mp4`) is a **cinematic lore
  teaser**, not gameplay/screen-capture footage — don't caption it as "gameplay."
- The Riven Sky and Sleepless gallery art shown here are the **child-stage** sprites
  (`riven_child.png`, `sleep_child.png`), not adult — the adult versions of those two
  specific forms still have a background-removal artifact (leftover checkerboard from
  the original AI generation) that resisted cleanup; the child-stage versions came out
  clean. Purely a cosmetic asset-pipeline issue, not a gameplay one — worth a proper
  re-export from source later if the adult art is needed for something bigger (e.g. a
  future Steam capsule).
- Once the Steam store page exists, add the real Wishlist link to both the Page's
  "Shop" / call-to-action button and pin a post announcing it.
