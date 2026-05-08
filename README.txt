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
