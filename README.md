# Self-Annotate
Self Annotate - Draw on Pages

╔══════════════════════════════════════════════════════════════╗
║              SELF ANNOTATE — Chrome Extension v1.0           ║
║          Annotation Tool + Whiteboard for any webpage        ║
╚══════════════════════════════════════════════════════════════╝


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  WHAT'S INSIDE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ANNOTATION OVERLAY
  ──────────────────
  ✏️  Pen          — Smooth freehand drawing on any webpage
  ✨  Magic Pen    — Draws and fades away after 2 seconds
  🖊️  Highlighter  — Semi-transparent marker for highlighting text
  ➡️  Arrow        — Draw arrows to point at things
  ⬜  Rectangle    — Draw boxes around content
  ⭕  Circle       — Draw circles/ovals
  T   Text         — Type text directly onto the page
  🧹  Eraser       — Erase specific annotations
  ↩️  Undo         — Undo last annotation (also Ctrl+Z)
  🗑️  Clear All    — Remove all annotations from the page
  👁️  Hide/Show    — Temporarily hide annotations
  🤚  Scroll Mode  — Disable drawing to scroll freely
  ↔️  Rotate Bar   — Switch toolbar between horizontal/vertical
  🖥️  Whiteboard   — Open the floating Whiteboard window
  ✖   Close        — Hide toolbar (reopen with ✏️ FAB button)

  ANNOTATION TOOLBAR EXTRAS
  ─────────────────────────
  • 7 color swatches (Red, Amber, Green, Blue, Purple, White, Black)
  • Stroke width slider (thin to thick)
  • Draggable toolbar — move it anywhere on screen
  • Position memory — toolbar stays where you left it across pages

  WHITEBOARD (Floating Window)
  ─────────────────────────────
  ✏️  Pen / ✨ Magic Pen / 🖊️ Marker / ➡️ Arrow / ⬜ Rect / ⭕ Circle / T Text / 🧹 Eraser
  ↩️  Undo          — Undo last stroke
  🗑️  Clear Page     — Clear current whiteboard page
  ＋  New Page       — Add a new blank whiteboard page
  ↑↓  Prev/Next Page — Navigate between pages
  ⊞   All Pages      — Thumbnail view of all pages
  ✕   Delete Page    — Remove current page
  ⬇️  Export         — Save as PNG (current page) or PDF (all/selected pages)
  ‹›  Sidebar toggle — Hide/show the page sidebar
  BG  Background     — 5 background colors (Grey, White, Dark, Yellow, Green)
  • Resizable window — drag any edge or corner to resize
  • Draggable title bar — move window anywhere
  • Minimize — collapses to a tab at the bottom
  • Fullscreen — expands to fill the entire screen

  SETTINGS PANEL (⚙️ gear icon on toolbar)
  ─────────────────────────────────────────
  🌍 Language       — English (default) / বাংলা
  🎨 Theme          — ⚙️ Auto (default) / ☀️ Light / 🌙 Dark
       Auto = follows your Windows/browser dark mode setting
       (updates live when you change system theme)

  EXTENSION FEATURES
  ──────────────────
  🟢 Permanent ON/OFF toggle — click extension icon to turn on/off
       • OFF = does nothing (default for new install)
       • ON  = auto-injects on every page, every refresh, every tab
       • Green "ON" badge shows when active
  💾 Settings saved — theme & language saved in chrome.storage + localStorage
  📍 Toolbar position saved — last drag position remembered across pages
  🔄 Closed by default — toolbar hidden on each page, only ✏️ FAB shows


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  INSTALLATION — Chrome on Windows
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  STEP 1 — Download & Extract the ZIP
  ─────────────────────────────────────
  Download "self-annotate-v1.0.zip" from the GitHub Releases page.
  Right-click the ZIP → "Extract All..."
  Extract to a permanent folder, e.g.:
       C:\Users\YourName\Extensions\self-annotate\

  After extracting you should see these files inside the folder:
       manifest.json
       background.js
       content.js
       options.html
       icons\

  ⚠️  Do NOT delete this folder after install.
      Chrome loads the extension directly from this folder.

  STEP 2 — Open Chrome Extensions Page
  ──────────────────────────────────────
  Open Chrome. In the address bar type:
       chrome://extensions
  Press Enter.

  STEP 3 — Enable Developer Mode
  ────────────────────────────────
  Look at the top-right corner of the extensions page.
  Toggle ON the switch that says "Developer mode".
  New buttons will appear on the top-left.

  STEP 4 — Load the Extension
  ─────────────────────────────
  Click the "Load unpacked" button (top-left).
  In the folder picker, navigate to your extracted folder:
       C:\Users\YourName\Extensions\self-annotate\
  Select that folder (where manifest.json is visible) → "Select Folder".
  "Self Annotate" will now appear in your extensions list.

  STEP 5 — Pin the Extension
  ───────────────────────────
  Click the 🧩 puzzle/extensions icon in the Chrome toolbar (top-right).
  Find "Self Annotate" in the list.
  Click the 📌 pin icon next to it.
  The ✏️ pencil icon will now always show in your Chrome toolbar.

  STEP 6 — Turn It ON
  ─────────────────────
  Click the ✏️ Self Annotate icon in the Chrome toolbar.
  The icon badge will show green "ON".
  Open any webpage — a ✏️ button appears at the bottom-right corner.
  Click that button to open the annotation toolbar and start drawing!


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  HOW TO USE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  1. Click Self Annotate icon → turns ON (green badge)
  2. Go to any webpage (http/https)
  3. Click ✏️ FAB button (bottom-right corner)
  4. Annotation toolbar opens — start drawing!
  5. Click ⚙️ gear to change language or theme
  6. Click 🖥️ to open Whiteboard
  7. To stop drawing temporarily: click 🤚 Scroll Mode
  8. To hide toolbar: click ✖ Close (FAB remains)
  9. To turn off completely: click extension icon again


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  NOTES
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  • Works on any http/https webpage
  • Does NOT work on chrome:// pages or the Chrome Web Store
  • Annotations are NOT saved between page refreshes
    (Whiteboard drawings are also session-only)
  • Does NOT change or affect the webpage's own design/theme
  • Extension settings accessible via:
    chrome://extensions → Self Annotate → Details → Extension options

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
