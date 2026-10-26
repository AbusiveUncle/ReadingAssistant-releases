# Reading Assistant – changelog

Every version of Reading Assistant by Uncle, newest first. Download the installer for a version
from the Releases page (the newest is always at the top). The app updates itself, so you only need
an installer for a new PC or to go back to an earlier version.

<!-- The text under each "## vX" heading is what the app shows under "What's new" for that version.
     This file is copied to the releases repository by the build when a version is published. -->

## v0.1.24

### New
- **Statistics page:** "📊 Statistics" next to Settings looks back at your reading: papers read, skimmed and abstracts per week or month, reading time per day or week, your streaks and the weekdays you read on, your most-used tags and biggest groups, and the links you open most (and never). Only reading tabs count.
- **Journal timer:** opening a link from the Links tab starts a timer at the top of the tab, for skimming a journal's new titles. "+1 min" and "Stop" are there; when it runs out a soft chime plays and the app comes to the front. Choose the length in Settings → Links tab (Off, 2, 5, 10 or 15 minutes; 5 to start with).
- **Three new looks:** Paper (warm white with no boxes, a black main button), Ink (near-black and flat, a white main button) and Mono (grey and white, plain black-and-white controls). Pick one in Settings → Look.
- **Compact list:** a switch in Settings → Look that works with any look. Each paper takes one line, buttons are smaller, and badges and tags show when you point at a paper (warnings like "No DOI found" always show), so about twice as many papers fit on screen.
- **Pause your streak:** Settings → Streak & games has a Pause button for holidays and sick days; paused days neither count nor break the streak. Press Resume when you're back.
- **Weekends off:** "Weekends don't break the streak" makes Saturday and Sunday free; reading on them still adds to the streak.

### Improved
- **Streak settings** explain what makes a day count, and "Show the daily streak" hides the 🔥 if you'd rather not see it (it keeps counting).

## v0.1.23

### New
- **Claude can organise your library (level 2):** with your permission, Claude can file the Inbox, make and rename groups and subgroups, move papers, add tags, write in notes, set reading status, set up games and add links. Switch it on in Settings → Claude → "Allow Claude to change things", and choose which kinds of change are allowed. Claude can't delete papers, files or tabs.
- **Undo for Claude's changes:** every change shows at the bottom of the window as it happens ("Claude filed 12 papers from the Inbox") with an Undo button, and the list updates by itself.

### Improved
- **Recent activity** in Settings → Claude also lists what Claude changed.

### Bug fixes
- **Long titles** in the Archive's "Recently added" list now wrap inside the box.
- **Titles with code in them** from online references (like "<i>via</i>") now show as plain text.

**After updating:** install the Claude extension once more (Settings → Claude → Make the Claude extension), so Claude Desktop knows which tools change things.

## v0.1.22

### New
- **Claude in the Reading Assistant (read only):** let Claude read your library from the Claude Desktop app – your tabs and groups, the papers' text, your notes and highlights. Ask it to summarise a paper, compare a group or find common ground. Set it up in Settings → Claude → "Make the Claude extension", then drag the file into Claude Desktop. Claude can't change anything.
- **Claude sees what you select and your Inbox:** tick papers in a tab or in the Inbox and ask Claude about "the papers I selected"; Claude can also look through the papers waiting in the Inbox.
- **Claude permissions:** in Settings → Claude, switch Claude's access on or off, choose what it may see (text, notes, highlights, search, your selection), hide whole tabs from it, and see what it looked at recently.
- **Inbox list:** everything waiting in the Inbox in a short list under the card. Tick papers, or All, to file, archive or remove them together.
- **Clickable links in PDFs:** web links and DOIs open in your browser; links inside a paper (references, figures) jump to the right place.
- **Ctrl + mouse wheel** zooms the PDF in the reader, around the spot under your mouse.
- **Points bank (Games):** points you've earned are kept for good, also when you change or delete a game.

### Improved
- **Settings** shows one section at a time: the list at the top works as tabs.
- **Game builder:** every choice starts with a capital letter.

### Bug fixes
- **Run-together text in some PDFs** (e.g. "AqueousSynthesisofUiO-66" in some Wiley papers) is now read with proper spaces, so search finds these papers again. Your PDFs are read once more after updating; this takes a moment.

## v0.1.21

Games (beta), round two:

- Free days: a day game can allow 1 or 2 missed days a week without breaking the streak.
- Clearer cards: "2 left today" or "Done today ✓". Pinned games come first, then running, done and paused ones; ended games fold away.
- The Games tab shows your points, with a chart of points per week.
- Building a game: what counts is sorted into Reading, Working, Library and Links.
- Forgotten links: links you rarely open are worth more and are suggested first ("Visit next · +7").
- Games are counted only when something changes, so they stay fast as your history grows.
- Tidier tab menu: the tab type has its own section and Delete sits at the bottom. Rename with ✎ and move a tab by dragging it.
- Fixed: closing the reader while pages were still loading could leave an error behind.

## v0.1.20

Games (beta) – the big new feature, switched on in Settings → Streak & games.

- Games: make your own goals in one line, "[5] [abstracts read] [a week] from [tab] [group] [tag]", or start from a ready-made one. Several can run at once, and one thing you do counts for every game it fits. Each game shows its progress, streak and the last periods; it can be paused, edited, deleted (with Undo) and pinned to its tab, where it shows under Next up.
- Points: 1 for each step towards a goal, a bonus when a goal is met, and a streak bonus for keeping it going.
- Link games: "forgotten links" (open links you haven't visited for a week or more; extra points the longer they were forgotten, with guards so it can't be looped) and "rounds" (open every link in a group once a week). The Links tab marks which links to visit.
- An event log keeps what you do (status changes, reading time, highlights, notes, tags, links opened …) in its own small files in your data folder, one per PC and year, so games can count it.
- The Journals tab is now called Links. Drag links to a new place or group, and rename the headings (Edit, or double-click a heading).
- Many tabs fit on one row: the names of the other tabs are shortened just enough, and hovering shows the full name.
- "Read abstract" is now "Abstract read". The "key papers" count is gone from the stats row.

## v0.1.18

- The Journals tab sits on its own at the far right of the tab bar, after "+ New tab".
- Streak: the stats row shows how many days in a row you have read (🔥). A day counts with some minutes in the reader (Settings → Streak, 10 by default) or a paper set to Read, Skimmed, Read abstract or Re-read.
- Oldest unread: the stats row shows how long your oldest unread paper has waited; click it to go there. Finishing a paper that waited 30 days or more gets a 🎉.
- Journals tab: how many of your links you visited this month, the ones not visited for the longest, and when each link was last opened.

## v0.1.17

- The Inbox and Journals tabs can be dragged to any place in the tab bar, like your own tabs. By default the Journals tab sits at the far right.
- The version number is shown in the header.

## v0.1.16

- Tab types: each tab is a Reading list, an Archive (storage: no counters or Next up; "Start reading" moves a document to a reading tab) or a Journal club / Course (a date per paper; Next up and "Coming up" follow the dates; overdue in orange). Choose in "+ New tab" or the tab's ▾ menu.
- Inbox (Settings → Inbox, off unless you switch it on): new files wait in an Inbox tab; file each one in a tab, group and subgroup with Send, or Archive, Remove or Later.
- Journals tab (Settings → Journals tab): quick links to the journals and sites you read, grouped your way, with suggestions from your own papers' journals and publishers.
- Search in the open paper: Ctrl+F or "Find" in the reader, with "3 of 12" and ↑ ↓.
- New status "Read abstract" (teal), counted as progress.
- "To cite" / "Cited" marks for your own writing, a filter for them, and a one-click formatted reference list.
- Tags from the papers' keywords (Settings → Tags, off unless you switch it on), coloured automatically.
- Reader: a » / « button and an arrow on the panel's edge fold the notes away.
- Reading time is also kept per day (for statistics and goals later).

## v0.1.15

- Subgroups without Details: "+ Subgroup" on each group makes one straight away (it stays while empty), and you can drag a subgroup's header onto another group to move it there with its papers.
- Reader: "Dark pages" for reading in the evening; highlights keep their colour.
- Reading time: the app counts how long each paper is open in the reader (while you are there) and shows it on the paper, e.g. "⏱ 25 min".
- Details says "Subgroup" instead of "Subtopic".
- Fix: a drop could get lost if the list updated itself in the middle of a drag.

## v0.1.14

- The sort menu and the Next up menu are easier to read (normal text, also in the open list).
- "Duplicate" only shows when the same article is twice in the same tab; having it in two tabs is fine.

## v0.1.13

- Next up can pick in different ways: list order, key papers first, shortest first, newest added, newest published, or "surprise me". "Skip ›" shows the next suggestion.
- Undo: after moving, sorting or deleting, the message at the bottom has an Undo button for a few seconds.
- Search: choose "Inside PDFs" or "Inside all files". Word, PowerPoint, Excel and text files are now searched inside too.
- Notepad files (.txt, .md) are listed and open in Notepad.
- "New" badge on papers added in the last 48 hours, and a "Duplicate" badge when two papers have the same DOI.
- Sort a group by year, author, title or date added; fold or unfold all groups at once.
- Export only the papers you selected.
- Ctrl+F or / jumps to the search box; each tab remembers where you were in the list.
- The "read" count is green, like its part of the progress bar.

## v0.1.12

- "Topic" and "subtopic" are now called "group" and "subgroup".
- "Select papers" button: tick boxes on every paper, then move them to a group or another tab.
- Tag colours: click the dot on a tag (in Details or Settings → Tags) to give it one of 9 colours.
- Skimmed has its own colour, also in the progress bar, and still counts as progress.
- Settings → Look → Text size: Small, Normal, Large or Larger.
- You can see the app working: a strip shows "Reading papers…" and "Looking up references…" with a summary at the end, and a typed DOI shows "Looking up…" until its reference is found.
- Shorter help texts.
- Fix: a tab dropped past the last tab now moves to the end.

## v0.1.11

- Select several papers: Ctrl+click papers one by one, or Shift+click for everything in between. Drag them together to a topic or a tab, or use the bar at the bottom to move them to another tab. Esc clears the selection.
- Deleting a tab: "Choose papers to keep…" lets you tick the papers to keep and pick the tab they go to; the rest are deleted with the tab. The PDF files stay on your PC.
- The page scrolls along when you drag a paper (or a tab) near the top or bottom of the window.
- Drag a tab left or right to change the order of the tabs.
- DOI fix: a "doi", "https" or "www" stuck onto the end of a DOI in the PDF is cut off, so the lookup works. Papers that got such a DOI are fixed and looked up again.

## v0.1.10

- Deleting a tab now removes the tab and its papers from the app (with their notes, status and tags). The PDF files stay on your PC. If you want to keep the papers, the same menu can move them to another tab instead.

## v0.1.9

- Tabs can now be deleted even when they have papers: choose which tab gets them. Papers keep their notes, status, tags and topics, and the deleted tab's folders move along, so new files keep turning up. The files on your PC are never touched.

## v0.1.8

- New status "On hold": the paper stays in its topic but doesn't count as left to read and never comes up as Next up. The top row now shows how many papers are on hold instead of how many have notes.
- Better at finding a paper's DOI by itself: reads the DOI publishers hide in the PDF's file info, handles fonts that store numbers oddly (e.g. Frontiers papers, whose text is now also searchable), looks past a cover page, and works out the DOI of old scanned Elsevier papers.
- Papers that showed "No DOI found" are searched once more after this update (not those where you removed the DOI yourself or said it's fine). The app reads all PDFs once again for this, which takes a moment.
- Clicking "No DOI found" opens Details with the cursor in the DOI field.

## v0.1.7

- DOIs are recognised in any link: doi.org links with or without www, publisher links (Wiley, ACS, Springer…), and links with ?… at the end.
- A ▸/▾ button on each topic and subtopic folds it away. Each PC remembers what is folded; searching or filtering shows everything.
- Espresso is the standard theme for new installs (a theme you already chose stays).
- Settings → About shows just your data folder with an Open button; the program folder, progress file and search index are under "Technical details".
- Safer data: a damaged progress file no longer stops the app (the newest daily copy is used and the damaged file is kept), and a missing progress file is never replaced by an empty list – you choose Try again, Restore or Start empty.
- Removing a folder keeps papers you have worked on; same-name files are both listed; exports never overwrite an earlier file.
- Faster and steadier reference lookups, and security fixes so the app can't be shown inside other websites.
- Uninstalling forgets the data-folder choice (your data itself is never touched).

## v0.1.6

- Subtopics: headers inside a topic. With "Sub-folders as topics", folders inside the sub-folders become subtopics. You can also set a paper's subtopic in Details, or drag it next to papers in a subtopic.
- Each subtopic header can be renamed (onto another one merges them), moved up or down, or removed (its papers stay in the topic).
- Subtopics are headings in the Word and Markdown exports.

## v0.1.5

- Papers are now found even when they are in the same folder as your progress file (before, that whole folder was skipped and adding it seemed to do nothing). The app's own exports and backups are still left out.
- The installed app uses the proper Windows folder window when you add a folder, always in front of the app.

## v0.1.4

- Adding a folder with sub-folders asks whether to use the sub-folder names as topics. If yes, papers go into a topic per sub-folder, also new ones found later.
- Settings → Folders: a "Sub-folders as topics" switch for each folder.

## v0.1.3

- A line at the bottom of the app: made by Uncle, for private use only.

## v0.1.2

- "+ New topic" is now right under the search and filters, instead of at the bottom of the list.
- Changing the data folder (Settings → About) restarts the app by itself with the new folder.

## v0.1.1

- The installer lets you choose where the app is installed, and whether it is for you only or for everyone on the PC.

## v0.1.0

- First installable version: Reading Assistant now has its own installer, Start-menu entry and window.
- Choose where your data lives at the first start (for example your OneDrive folder, so every PC shares the same progress).
- Updates: the app tells you when a new version is out and installs it when you say so.
- New Espresso theme and the new app icon.

## Before v0.1.0 (October 23–24, run from the source files)

- Built-in PDF reader with highlights in colours you give meanings to; the app remembers where you stopped reading.
- Named tabs, groups, tags and a Settings page.
- Filter menus and search inside the PDFs.
- References: DOI lookup via Crossref, citations in APA, IEEE or "Name et al." style, RIS/BibTeX export.
- Notes export to Word and Markdown, and daily backups.
