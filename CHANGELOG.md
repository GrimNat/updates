# OmiLOTJ: what's new

Install: Mudlet > Package Manager > Install > OmiLOTJ.mpackage (over the old one). The version shows at the right end of the toolbar.

## v1.9.0 (2026-10-29)
- Guides: Help (toolbar) now starts with OMILOTJ GUIDES, a short how-to page for every tool we've built. Type 'guide' to open them, or 'guide <word>' (guide dossiers, guide arkrun, guide shipdb...).
- Dossiers fill themselves in with what the game tells you outright: someone introducing themself (or you to them), a dub, 'lookup' with a datapad (race, sex, level, clan and rank, and the whole databank file), 'locateship' owners (the ship goes into their file), 'memory' (names and how they look), and every name the Journal knows. Each file gets a contact log of when and where you met.
- Ship DB notes ships in space too: the ones you see out of the cockpit while flying (the bright yellow list) and every ship on 'radar', with the system and the planet they were near. New ones join the list for 'shipdb locate'.

## v1.8.2 (2026-10-29)
- The chat wrap fix from 1.8.1 really is in this one (the 1.8.1 download went out without it).

## v1.8.1 (2026-10-29)
- Fixed: chat tabs could wrap lines far too short (a few words per line in a wide box) when the chat's width was measured while Mudlet was still opening. The wrap now follows the chat box's real width (new lines; older lines keep their wrapping).

## v1.8.0 (2026-10-29)
- Dossiers (new toolbar button): your own file on each person, like a records database. Clan, rank, profession, who they work for, race, base, plus lists of other names, disguises you've seen, restrung armor looks, ships, shops and notes. You fill it in as you work things out; nothing fills itself in.
- Every entry remembers when you wrote it and where you were, and is tagged IC (learned in play), PUB (public) or OOC (don't use it in character). Changing someone's clan keeps the old one as history.
- Clues next to what you wrote: where the Ship DB saw each of their ships (which pads), the shop catalog's stock, and what your recordings hold (lines by or about them, also under each disguise, memory notes, thoughts).
- Ship DB lookups work now: it reads the real locateship answer (owner, dock, planet), waits for each lookup to finish before starting the next (sending the next one early cut every lookup off), and tries again after 'no record found' or an interruption. Ships whose earlier lookups got nothing are looked up again by 'shipdb locate'.
- Search finds people by any ship, disguise, name or note. 'dossier <name> ship = <ship>' adds things from the command line; Journal person pages get an 'open dossier' link. Dossiers stay on your PC: they're never shared.

## v1.7.1 (2026-10-29)
- Fixed: the Utilities button didn't open on screens where the toolbar is narrow (the version number sat on top of it). The buttons now shrink to fit.
- Fixed: a long hail could get the next game message stuck onto its end in the hail window (like 'You are too close to ... to make the jump to lightspeed!').
- Fixed: toolbar buttons often needed two or three clicks. A click while a panel is still sliding now waits its turn instead of being ignored, and the button lights up the moment you click it.

## v1.7.0 (2026-10-29)
- Ark Run: choose what to gather (crate, wireless, test results, crystal chips, frozen organisms, the tunnel credit, Arkanian diamonds, blue diamonds, lommite) in Utilities > Ark Run or with 'arkrun gather <kind> on|off'. Start takes the shortest loop for what's switched on.
- Ark Run: type your locker number in the box on the Ark Run page (or 'arkrun locker <n>'). Each player sets their own; too-heavy pickups go there and the pickaxe comes from it.
- Not gathering crates: the run goes straight away and, after the loop, waits for the city's reset line before going again.

## v1.6.0 (2026-10-29)
- Ship maps mark the rooms that matter: cockpits yellow 'C', turrets red 'T', engine rooms green 'E' (rooms the game tags [ENGINE], or with Engine in the name).
- Every ship already on your map gets marked when Mudlet starts, and every ship of a class shares the marks.

## v1.5.0 (2026-10-29)
- Clan private datanet: 'dncrawl MS private' (any clan you belong to) also saves the members-only pages, kept apart in their own folder and marked with the character who read them.
- Datapad: members-only pages show in orange under their clan, in a MEMBERS ONLY section below the public pages.
- Ark Run: no more lommite digging in the tunnel (the blue diamond digs stay), and after emptying your pockets into the locker it takes your comlinks back out, so you can still hear and talk.
- Ship pictures: the Naboo N-1 Starfighter now has one under its map, and the LAAT/s Gunship's picture shows up (its name was wrong).
- Ship DB: every ship you pass (pads, hangars, the view from your cockpit) is noted quietly with where it was seen. 'shipdb locate' (or Utilities > Ship DB) runs locateship on the new ones, from anywhere; owners are kept as a history, so a sold ship shows who had it before. 'shipdb owner <name>' lists what someone owns.

## v1.4.1 (2026-10-29)
- Fixed: in space the ship bar flickered over the bottom of the game text (and its scrollbar) about once a second.

## v1.4.0 (2026-10-29)
- Themes: framed map, chat, bottom and ship bars plus matching toolbar colours, one look per class (combat, piloting, engineering, bounty hunting, smuggling, leadership, espionage, slicer, medical, science, force) or the plain datapad look.
- The theme follows your main class (the cyan one in 'score' or 'levels'); pick any other with 'theme <name>' or Utilities > Themes. The ship bar's frame only shows while you're in a ship.
- Click the version number on the toolbar: what's new, and an instant check for updates.

## v1.3.0 (2026-10-29)
- Ship pictures on the map: a top-down drawing of the ship sits under its map, lined up with the rooms (you see the Flashfire with you in its cockpit).
- Drawn so far: Flashfire, Star Commuter shuttle, JumpMaster 5000, YT-1000, Star Galleon, LAAT/s, Vigo gunship. 'shipmap art nudge <east> <north>' fine-tunes the spot.
- Aboard a ship the map zooms in so the ship fills it, and zooms back out when you leave ('shipmap zoom off' to stop it, 'shipmap zoom <n>' for n rooms across).

## v1.2.4 (2026-10-29)
- Recordings skip the whole login screen (account, passwords, character list): they start right after your last password, at the Message of the Day or 'Reconnecting'.

## v1.2.3 (2026-10-29)
- Recording (rec) starts by itself every time Mudlet starts; 'rec off' stops it until the next start. Your login is never recorded.
- Update check the moment you log in (your first room in the game), then every 15 minutes from there.

## v1.2.2 (2026-10-29)
- Update window: the buttons show each step (Downloading... / Installing... / Updated), extra clicks are ignored while it works, and it closes by itself when done.
- Buttons with nothing to do are greyed out instead of disappearing; the map asks for a second click before it replaces yours.

## v1.2.1 (2026-10-29)
- Updates are also checked when you connect and every 15 minutes, not only when Mudlet starts. 'Later' means no reminder for that version until you restart Mudlet.

## v1.2.0 (2026-10-29)
- Ship map areas are named after the ship's class ('Star Commuter 2000 Transport'), not each ship: one area per class, all its ships share it.
- Old per-ship areas (PUB04, PUB10, PUB29, your own ships) are folded into their class areas by themselves when Mudlet loads.
- A class's blueprint is learned from the map as soon as you board one, even right after Mudlet starts.

## v1.1.0 (2026-10-29)
- Ship maps: one blueprint per ship class. Board any ship of a mapped class (every Star Commuter shuttle, every Flashfire) and its whole map is drawn at once.
- Map a new class once (board, 'map start', walk it, leave) and it works in every ship of that class. Blueprints come with updates.
- Utilities > Ship Maps lists the blueprints; 'shipmap' does the same in the main window.

## v1.0.0 (2026-10-28)
- Version numbers: shown on the toolbar (click for this list).
- Updates from inside Mudlet: new versions and maps are offered in a pop-up when the profile loads ('omiupdate' checks now). This is the last package you install by hand.
- Utilities button: Fly Loop (your own ship, any two planets, landing pads), Landing Pads list, Ark Run controls.
- Hail pop-up: ship hails open a movable window in the middle of the screen; reply from it. 'hails' opens it.
- Bank: 'bank list' now works with any prompt (it waited for one particular prompt before).
- Landing pads are learned whenever you type 'land <planet>' in orbit without a pad ('pads' lists them).
