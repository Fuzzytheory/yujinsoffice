# StarzX Torchlight Casting Call

_Started 2026-06-18 02:37 UTC_

---

## User

Create a casting call for StarzX Torchlight Feature film, check out our backstage post: https://www.backstage.com/casting/starzx-3174209/?role_id=5553414&role_id=5553415&role_id=5553416&role_id=5553419&role_id=5553418&role_id=5553417

Here are the infos.

logline
A K-pop superfan manipulates her way into a college dance group days before their shot at becoming trainees. Her devotion quickly turns into something far more dangerous.

XENI : An obsessive K-pop devotee with unsettling precision and hidden talent. Volatile, calculating and deeply fixated on becoming a member of the Starzx K-pop group.

Sierra : Sharp, controlling leader of the STARZX K-pop group. Disciplined, strategic, and relentlessly ambitious. The group’s lead dancer and choreographer. Role contains possible minor stunts.

Zara - Korean or Korean American. Quietly observant and difficult to read, Zara rarely gets caught up in drama or emotion. She approaches everything with discipline and practicality, always focused on the work and the process itself. 
 
Alison — The strongest vocalist/singer in StarzX. Charismatic, outspoken, and fiercely protective of the group, she trusts her instincts and isn't afraid to call out problems long before everyone else sees them.

Tristin: Warm and magnetic. In charge of styling, making her an excellent team player of StarzX. A sort of “yes man” within the group.
 
Rachel - Social and refreshingly honest. Rachel joined StarzX for friendship, not fame. As the group becomes consumed by ambition, she's the first to question whether the dream is worth what it's costing them.
 
Kevin — Effortlessly kind, he is lifelong K-pop fan who values friendship over status, Kevin represents the community and joy that first drew people to the culture. As his best friend Xeni becomes consumed by ambition, he's one of the first people to recognize she's losing herself.

## Assistant

I'll look at your brand assets and pull the logistics from the Backstage post first.

_[tool: view_image]_

_[tool: list_files]_

_[tool: web_fetch]_

_[tool: view_image]_

_[tool: image_metadata]_

The Korean filename is causing tool access issues — let me copy it to a safe name.

_[tool: copy_files]_

_[tool: run_script]_

The filename uses decomposed Unicode jamo. I'll copy it via script.

_[tool: run_script]_

I can see both assets — the chrome/liquid-metal aesthetic from the KitKat reference and the silver StarzX wordmark. One technical snag: your logo file's name uses characters my tools can't read, so I'll need it re-uploaded. A few questions before I build:

_[tool: questions_v2]_

## User

Questions answered:
- logo_reupload: uploads/logo_reupload-1781751495984.png
- format: Instagram post / story / could be multiple decks 
- logistics: submission deadline and how to apply

- role_details: Kevin is the only one male/ rest of them are female : all role age can be 18-25
- tone: Mostly bright/dreamy K-pop glam
- variations: Three directions side by side
- contact: backstage link!

## Assistant

_[tool: view_image]_

_[tool: image_metadata]_

Logo's transparent and clean. Setting up the project.

_[tool: copy_files]_

_[tool: update_todos]_

Now building the full casting-call set — three directions, each a 4-card Instagram carousel.

_[tool: dc_write]_

_[tool: update_todos]_

_[tool: show_html]_

I'll take one quick look to confirm the chrome treatment renders, then hand off.

_[tool: save_screenshot]_

_[tool: save_screenshot]_

_[tool: get_webview_logs]_

_[tool: eval_js]_

_[tool: eval_js]_

_[tool: show_html]_

_[tool: eval_js]_

Now it's rendering (12 cards, logo loaded). Let me check the three cover cards.

_[tool: multi_screenshot]_

All three directions render cleanly — chrome type, logo, and the bright→dark spectrum all working. Handing off.

_[tool: ready_for_verification]_

Done. **StarzX Casting Call.dc.html** — three Instagram-ready directions side by side, each a 4-card carousel (Cover · XENI lead · the Group · How to Apply) at 1080×1080:

1. **Dream Chrome** — daylight sky, liquid-silver Bodoni italic, airy K-pop glam
2. **Pearl Zine** — pearl paper, blown-up Anton poster type, chrome sticker accents
3. **Midnight Torchlight** — night sky + spotlight, elegant Cormorant silver — the thriller edge

All use your StarzX logo and the chrome motif. Every card is directly editable — click any text to retype.

Two things to fill in when you're ready: the **deadline** (I left "add date" placeholders) and confirm the Backstage URL. Pick a direction and I'll polish it, build the matching 1080×1920 Story versions, or split into more carousel cards.

## User

Found issues — fixing…

## Assistant

Verifier's right — Kevin clips off the Group cards and covers overflow. Tightening the sizing.

_[tool: str_replace_edit]_

The atomic batch failed on one mismatched string. Let me read the file to get exact strings, then do the overflow fix and the tweak system together.

_[tool: read_file]_

Got it — consolidating into one strong KitKat-referenced design (sky blue + glossy candy-red chrome), pairing Xeni & Sierra, grouping the rest, dialing Torchlight down, and wiring three expressive tweaks (palette / title emphasis / sparkle). The silver and midnight explorations live on as palette options.

_[tool: dc_write]_

I'll verify the new single design renders and the tweaks drive the CSS variables.

_[tool: show_html]_

_[tool: eval_js]_

No overflow on any card; vars applied. Let me see the cards and confirm a palette tweak drives the recolor.

_[tool: multi_screenshot]_

Looks on-point — candy-sky blue, glossy red liquid-chrome headlines, silver StarzX logo, Torchlight dialed down, Xeni & Sierra paired, the rest grouped. All four cards fit with zero overflow.

Done. Rebuilt **StarzX Casting Call.dc.html** as one focused carousel:

- **Color** now references the KitKat shot — bright sky-blue backgrounds with clouds, glossy candy-red liquid-chrome type, silver StarzX logo.
- **Xeni & Sierra** share one "The Leads" card (devotion vs. discipline); **Zara, Alison, Tristin, Rachel, Kevin** share "The Group."
- **Torchlight** is de-emphasized — the logo is the hero, Torchlight a small secondary wordmark.
- **Tweaks panel** (3 expressive controls): **Palette** (Candy Sky / Liquid Silver / Midnight — your earlier silver & dark explorations live on here), **Title Emphasis** (Subtle / Balanced / Bold for the Torchlight word), **Sparkle** (stars on/off).

Still open: drop in a real **deadline** (placeholder "add date") and confirm the Backstage URL. Want me to also generate 1080×1920 Story versions?

_[tool: ready_for_verification]_

_[tool: snip]_

Done — design rebuilt and tweaks wired. Ending my turn while the verifier checks in the background.

## User

none of the three concepts are my taste. Re create everything, use these elements are reference in tone of the background. use san-serif fonts and readable

## Assistant

_[tool: view_image]_

_[tool: view_image]_

_[tool: view_image]_

These three set a clear new tone: a dark, dreamy K-pop-concert glow — lavender/pink lightstick ocean, holographic shimmer, jewel glass. I'll rebuild around the actual reference images as backgrounds, with readable sans-serif text in frosted-glass panels.

_[tool: copy_files]_

_[tool: dc_write]_

_[tool: show_html]_

_[tool: eval_js]_

Group card overflows 59px. Tightening its panel, and checking the backgrounds render.

_[tool: str_replace_edit]_

_[tool: multi_screenshot]_

Looking sharp — concert-glow photo backdrops, frosted-glass panels, clean readable sans-serif, lavender accents. Let me confirm the Group card no longer overflows.

_[tool: eval_js]_

Content genuinely runs long. Trimming card + panel padding and gap.

_[tool: str_replace_edit]_

_[tool: eval_js]_

Number isn't budging — likely a stale preview. Forcing a reload and inspecting what actually overflows.

_[tool: show_html]_

_[tool: eval_js]_

Stale reading — after reload the Group card fits (overflow 0). All four cards are clean. Handing off.

_[tool: ready_for_verification]_

Recreated from scratch in the concert-glow direction your references point to:

- **Backgrounds** are the real reference images — the lavender lightstick ocean (cover + apply), holographic CDs (the leads), and jewel glass (the group) — darkened for legibility.
- **Frosted-glass panels** hold all copy (a nod to the glass-block + CD shimmer), with **clean sans-serif type** (Space Grotesk + Archivo), white text, lavender accents — readable over the busy imagery.
- Same structure: Cover · Xeni & Sierra · The Group · Apply. Silver StarzX logo kept; Torchlight stays understated.
- **Tweaks panel**: **Accent** (Lavender / Hot Pink / Ice Blue), **Panel** (Frosted Glass / Solid Dark / Minimal), **Glow** (on/off).

Still to fill in: the real **deadline** (placeholder "add date"). Want me to spin up 1080×1920 Story versions of these too?

## User

Delete the logo of starzX, and just unify with the fonts that u did, but in all caps. show me a different more modern simple font.

## Assistant

I'll delete the logo, replace it with a text wordmark in all caps, and switch the display font to a cleaner modern one (Sora) so you can see it across the whole set. Let me check the current file first since you edited the logo in the editor.

_[tool: grep]_

No override block — the editor tweaks lived on the `<img>`, which I'm removing anyway. Deleting both logos, dropping in a `STARZX` wordmark, and switching the display font to **Sora** (modern, simple, geometric) across the set.

_[tool: str_replace_edit]_

_[tool: dc_html_str_replace]_

_[tool: show_html]_

_[tool: multi_screenshot]_

Logo's gone, replaced by a clean **STARZX** wordmark in **Sora** (modern geometric sans), all caps, and the whole set now uses Sora for display type. Quick overflow check then done.

_[tool: eval_js]_

All four cards fit cleanly. Done — the StarzX image logo is removed and replaced with a **STARZX** text wordmark in all caps, and I switched the display font to **Sora** (a modern, simple geometric sans) across the whole set, with Archivo still handling body copy. The wordmark is now the hero on the Cover with "Torchlight" understated beneath it.

If Sora isn't the vibe, easy swaps in the same modern-simple family: **Outfit**, **Manrope**, or **Sora** → say the word and I'll switch it.

## User

can u export these separately in png format?

## Assistant

Yep — I'll export each card as a full-resolution 1080×1080 PNG.

_[tool: save_screenshot]_

_[tool: eval_js]_

Found it — DC mounts under `#dc-root > .sc-host`. Re-running with correct ancestor walk.

_[tool: save_screenshot]_

Blank — my ancestor mutations fought the DC host. Let me inspect the live geometry before re-trying.

_[tool: eval_js]_

The host got hidden. Let me reload clean and verify a corrected isolation actually sizes the card before exporting.

_[tool: show_html]_

_[tool: eval_js]_

Card now renders at full 1080×1080. Exporting all four.

_[tool: save_screenshot]_

_[tool: image_metadata]_

_[tool: show_html]_

The saved files came out at pane size (909×525) — clipped, not full cards. I'll capture each card in tiles at full scale and stitch them into true 1080×1080 PNGs.

_[tool: save_screenshot]_

_[tool: run_script]_

_[tool: view_image]_

_[tool: image_metadata]_

Clean 1080×1080, no visible seams. Removing the earlier clipped files, restoring your live view, and packaging the four PNGs for download.

_[tool: delete_file]_

_[tool: show_html]_

_[tool: present_fs_item_for_download]_

Exported — four separate **1080×1080 PNGs** (Cover, Xeni & Sierra, The Group, Apply), ready to post. Download card is above.

## User

Export this design as an editable PPTX: StarzX Casting Call.dc.html

## Assistant

_[tool: snip]_

_[tool: snip]_

_[tool: show_to_user]_

