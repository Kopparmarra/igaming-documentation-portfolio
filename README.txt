iGaming Documentation Portfolio - Malta/MGA version with interactive simulation

Open index.html in a browser.

Structure:
- Overview
- Playable Slot Prototype
- Game Rules / Paytable
- Payout Logic / RTP
- Simulation / RTP Verification
- Technical Game Specification
- Compliance Documentation – Sample Jurisdiction: Malta / MGA
- QA / Test Evidence

The simulation page lets the user run the sample slot logic repeatedly, defaulting to 1,000 spins.
Theoretical weighted-pool RTP: 96.18%

Note:
The compliance page is a documentation sample only and not legal advice.


Added in this version:
- Win distribution chart (No win / Push / each payout multiplier)
- Jackpot and rare-win timeline
- Jackpot KPI
- Highest single payout KPI


Added in v3:
- Key result figures moved directly under the Run simulation controls
- Win distribution and jackpot timeline moved above the detailed tables
- Cumulative RTP chart moved higher on the page


Added in v4:
- Cumulative RTP chart moved directly below the key figures
- KPI cards made much smaller
- Distribution and jackpot timeline placed side by side
- Simulation page compressed so the main dashboard fits much better above the fold


Added in v5:
- Win distribution and Jackpot timeline aligned in the top chart grid
- Equalized chart area heights for the two side-by-side visualizations


Added in v6:
- Reworked Win distribution and Rare wins / jackpot as matched visualization cards
- Removed oversized blank jackpot chart state and replaced it with a cleaner empty-state message
- Improved bar chart labels and reduced visual clutter


Added in v7:
- Playable prototype page updated so the full slot game is visible directly in the embedded frame
- Increased embedded game height and centered the live demo


Added in v8:
- On the Playable Prototype page, the live demo is now shown before the Scope table
- Sidebar order updated to Demo > Scope > Limitations


Added in v9:
- Reduced the black frame area around the embedded slot
- Moved the slot game higher up inside the embedded prototype
- Reduced the embedded demo height to better fit the visible game


Added in v10:
- Official MGA references added to the Compliance Documentation page
- Includes Regulatory Framework, Compliance Audit Manual, System Audit/System Review references,
  System Documentation Checklist, Player Protection Directive and RTP update


Added in v11:
- Improved readability of the "No rare wins" state in the Rare wins / jackpot card
- Darker, larger empty-state text and more useful supporting note


Added in v12:
- Replaced the large empty-state box in Rare wins / jackpot with a simpler centered timeline message
- Made the supporting note shorter and more subtle


Added in v13:
- Reworked the Rare wins / jackpot empty state with a simpler pill message
- Uses normal Arial/Helvetica-style font in the chart text
- Shorter, more neutral supporting note


Added in v14:
- Simplified the Rare wins / jackpot empty state further
- Replaced centered large text with a small left-aligned status pill
- Reduced chart height and made the supporting note smaller and less cramped


Added in v15:
- Replaced the SVG-based "no rare events" text with a normal HTML banner using standard readable font
- Kept the timeline clean underneath the banner
- Improved note text readability


Added in v16:
- Fixed Rare wins / jackpot logic so the "No rare events in this run" banner is only shown when there are actually no rare events
- Banner visibility is now controlled explicitly between simulation runs


Added in v17:
- Rare wins / jackpot card now keeps a fixed height whether or not a rare event occurs
- Added a fixed-height banner slot above the timeline so the layout no longer jumps between simulation runs


Added in v18:
- Executive summary on Overview
- Documentation deliverables table
- Clearer note about weighted-pool RTP vs exact strip RTP
- Simulation timeline changed from jackpot-only focus to High-impact timeline (46x+), with jackpot still shown separately
- Expected frequency table added
- Compliance page made more cautious
- MGA rules-availability note added
- System review readiness added to compliance matrix

Expected frequency values used:
- 46x+ high-impact win: 3.470 per 1,000 spins
- 172x+ rare win: 0.183 per 1,000 spins
- 572x jackpot: 0.000751 per 1,000 spins
- 572x jackpot approx. 1 per 1,331,000 spins


Added in v19:
- Removed the "Open prototype in new tab" link from the Playable Prototype page
- Changed the area around the embedded slot to a beige background
- The slot game itself remains unchanged inside the iframe


Added in v20:
- Cumulative RTP chart now starts from spin 10
- Y-axis is fixed to 0%–160%
- Gridlines are fixed at 0, 40, 80, 120 and 160 percent
- This prevents early outliers from distorting the chart


Added in v21:
- Cumulative RTP chart Y-axis changed from 0%–160% to 0%–300%
- This reduces clipping while still keeping the chart stable
- Chart still starts at spin 10


Added in v22:
- QA page renamed to Verification
- QA checklist replaced by a traceability-focused Verification page
- Navigation updated from QA to Verification
- Overview wording updated from QA evidence to verification evidence


Added in v23:
- Playable slot prototype now resets on page load
- Starting balance is always 1000
- Starting bet size is always 10
- Previous localStorage bet size/statistics are cleared for a consistent portfolio demo


Added in v24:
- Simplified Key results to focus on Simulated RTP, Theoretical RTP, Difference and Spins
- Removed Total wagered, Total returned, Wins, Pushes, Jackpots and Highest single payout from the top KPI row
- Detailed results remain visible in the charts and tables below


Added in v25:
- Key result boxes made slightly wider with fixed widths
- Top KPI row now uses fixed-width columns so labels fit more reliably
- Desktop layout stays fixed-width while mobile still collapses responsively


Added in v26:
- Key result boxes widened again
- KPI labels now wrap normally instead of being clipped
- Fixed-width layout preserved on desktop


Added in v27:
- Difference KPI now changes color based on result
- Positive difference = subtle green tint
- Negative difference = subtle red tint
- Neutral difference = neutral styling


Added in v28:
- Fixed Difference KPI coloring by using the actual simulatedRtp property in the render function
- Difference card now gets positive/negative/neutral classes correctly on every simulation run


Added in v29:
- Removed the top Difference KPI card
- Simulated RTP KPI now gets subtle green/red/neutral styling based on whether it is above or below Theoretical RTP
- Top KPI row now contains Simulated RTP, Theoretical RTP and Spins


Added in v30:
- Removed the top Spins KPI card
- Key results now show only Simulated RTP and Theoretical RTP
- Spins remains visible in the controls above


Added in v31:
- Fixed simulation render after removing the Spins KPI
- Removed the obsolete kpi-spins update call
- Made setText() safe when optional UI elements are missing


Added in v32:
- Fixed Simulated RTP red/green state by ensuring both the card ID and JS state function are present
- Added stronger CSS overrides for positive/negative/neutral RTP state


Added in v33:
- Removed the large black outer background around the slot prototype
- Outer area now uses a light beige tone so only the actual gameboard stays dark
- Added a small "96% RTP" badge above the machine
- Softened the machine shadow slightly


Added in v34:
- Removed the small 96% RTP badge from the slot prototype itself
- Updated the Prototype page heading to: Playable Slot Prototype (96% RTP)


Added in v35:
- Fully removed leftover 96% RTP badge markup and CSS from slot-prototype.html
- Kept RTP information only in the Playable Prototype page heading


Added in v36:
- Added cache-busting query string to the prototype iframe: slot-prototype.html?v=36
- This forces browsers/GitHub Pages to load the updated slot file without the old RTP badge


Added in v37:
- Moved Log and Copy Log into centered controls directly below the slot machine
- Replaced fixed-position debug buttons with clean inline buttons
- Increased log window readability: larger font size, more padding, better line spacing
- Added cache-busting iframe source: slot-prototype.html?v=37


Added in v38:
- Log and Copy Log buttons reinforced as centered controls under the game
- Increased debug button size slightly
- Increased log panel text to 14px with more line spacing and padding
- Added cache-busting iframe source: slot-prototype.html?v=38


Added in v39:
- Removed Log and Copy Log completely from the playable slot prototype
- Removed debug log box and related debug functions
- Added cache-busting iframe source: slot-prototype.html?v=39


Added in v40:
- Removed the explanatory beige note box from the Simulation page
- Simulation page now flows directly from controls to Key results


Added in v41:
- Removed the specific "New runs update..." note from the Simulation page using a targeted match


Added in v42:
- Removed the RTP comparison sidebar link
- Removed the RTP comparison table from the Simulation page
- Removed obsolete JS updates for the deleted RTP comparison fields


Added in v43:
- Removed the separate Rules / Paytable page
- Removed Rules from the main navigation
- Removed the Rules card from the Overview page
- Updated internal evidence references to use Payout Logic / RTP instead
- Renumbered remaining overview cards/page kickers for a tighter structure
