# San Mateo Science Center HVAC Noise Documentation Website

Complete advocacy website documenting HVAC noise issues at San Mateo Science Center (Buildings 901 & 951, Mariners Island Boulevard).

## Website Structure

### Main Pages
- **index.html** - Homepage with interactive Google Maps, case overview
- **welcome_to_neighborhood.html** - Complete narrative timeline and community story
- **community_complaints.html** - Detailed timeline with measurement methodology analysis
- **potential_solutions.html** - Comprehensive mitigation strategies ($400K-800K budget analysis)

### NEW: Interactive Noise Map
- **interactive_noise_map.html** - Full-featured noise analysis tool with:
  - Google Maps integration with satellite view
  - Drag-and-drop SignalScope X CSV upload
  - Real-time noise contour visualization (100 dB to 35 dB)
  - Measurement markers with color-coding (violation/compliant/tone)
  - ANSI S12.9 penalty calculator
  - Frequency filtering (low/mid/high/63Hz)
  - Tone detection visualization
  - Export measurements to CSV
  - Building impact analysis
  - 5 sample measurements pre-loaded

### Technical Documentation  
- **hvac_clean_schematic.html** - Clean HVAC system diagram
- **hvac_schematic_ashrae_annotated.html** - ASHRAE RP-526 annotated analysis with 7 specific failure modes
- **ansi_s12_9_part_4.html** - Measurement standards explanation
- **penalty_application_guide.html** - Character penalty calculation guide
- **technical_resources.html** - Equipment specifications and standards

### Legal/Regulatory
- **comparative_standards.html** - Bay Area municipal noise ordinance comparison
- **model_noise_ordinance.html** - Proposed SMMC 7.30 improvements
- **science_center_case.html** - Case documentation and legal framework

### Tools
- **data_import.html** - SignalScope X CSV import tool for documenting measurements

## Key Features

### Interactive Noise Map (NEW!)
The **interactive_noise_map.html** page provides a comprehensive noise analysis platform:

**Visualization Features:**
- Dual HVAC point sources (Buildings 901 & 951)
- Noise contours from 100 dB @ source to 35 dB limit
- Color-coded by severity (purple → red → yellow → green)
- Dashed line shows 35 dB(A) residential limit
- Real-time measurement markers with status indicators

**Data Upload & Analysis:**
- Drag-and-drop SignalScope X CSV files
- Automatic location tagging
- Tone detection highlighting
- ANSI S12.9 Part 4 penalty application (+5 dB tonal, +5 dB LF)
- Frequency filtering (all/low/mid/high/63Hz only)
- Export all measurements to CSV

**Display Controls:**
- Toggle noise contours on/off
- Toggle measurement markers
- Toggle HVAC source markers
- Show city jurisdiction boundaries
- Filter for tones only
- Apply/remove character penalties

**Pre-loaded Sample Data:**
- Property line measurement (48 dB(A) ground level)
- 915 Shoreline Dr 3rd floor (58 dB(A) + tone)
- Multiple residential measurements
- Shows realistic distribution of noise impact

### ASHRAE RP-526 Integration
The **hvac_schematic_ashrae_annotated.html** page provides professional acoustic analysis based on:
- Schaffer, M.E. (2005). *A Practical Guide to Noise and Vibration Control for HVAC Systems*, Second Edition
- Documents 7 specific failure modes with chapter/page references
- Visual diagram with problem annotations
- Establishes technical credibility for case

### Complete Navigation
All pages include consistent vertical navbar with **14 links** including:
1. Home
2. Welcome to the Neighborhood
3. A Community Responds
4. Potential Solutions
5. Comparative Standards
6. Import Data
7. **Interactive Noise Map** ← NEW
8. ANSI S12.9 Part 4
9. Penalty Guide
10. Model Ordinance
11. HVAC System
12. HVAC ASHRAE Analysis
13. Technical Resources
14. Case Documentation

### Professional Formatting
- Optimized for 1920x1080 displays
- Mobile responsive with collapsible navigation
- Print-friendly
- Accessible design
- Google Maps API integrated

## Technical Highlights

- **Budget Context:** $400K-800K mitigation = 1.8-3.6% of $22M project
- **Measurement Methodology:** Ground-level vs. upper-floor assessment (15-20 dB difference)
- **Character Penalties:** +5 dB tonal, +5 dB low-frequency per ANSI S12.9 Part 4
- **Clear Documentation:** 204+ days without resolution
- **Interactive Mapping:** Real-time noise propagation visualization with dual point sources

## Interactive Map Features Detail

### Noise Contours
Based on point source inverse square law: L2 = L1 - 20*log10(r2/r1)

- 100 dB(A) @ 10 ft (3m) - Source level
- 60 dB(A) @ 100 ft (30m) - Near field
- 55 dB(A) @ 177 ft (54m) - Moderate impact
- 50 dB(A) @ 315 ft (96m) - San Mateo limit
- 45 dB(A) @ 561 ft (171m) - Reduced impact
- 40 dB(A) @ 1000 ft (305m) - Low impact
- 35 dB(A) @ 1778 ft (542m) - Typical residential limit (dashed)

### Measurement Markers
- **Red (📱)**: Tone detected - indicates pure tone or narrow-band noise
- **Orange (📱)**: Violation - exceeds 50 dB(A) limit
- **Green (📱)**: Compliant - within limits

### SignalScope X Integration
Compatible with SignalScope X Pro CSV exports:
- 1/3 octave band frequency data
- A-weighted and C-weighted levels
- Time-stamped measurements
- GPS coordinates (manual entry in this version)

## Usage

1. Open index.html in web browser
2. Navigate using left sidebar menu
3. Try **Interactive Noise Map** for full analysis tools:
   - Upload your own SignalScope measurements
   - Visualize noise propagation
   - Apply ANSI penalties
   - Export results
4. Google Maps API key included for map functionality
5. All pages cross-referenced with internal links

## Browser Compatibility

- Chrome/Edge: Full support including drag-and-drop
- Firefox: Full support
- Safari: Full support
- Mobile: Responsive design works on all devices (touch-friendly controls)

## New in This Version

✅ **Interactive Noise Map** with Google Maps integration
✅ Drag-and-drop CSV upload functionality  
✅ Real-time noise contour visualization
✅ ANSI S12.9 penalty calculator
✅ Frequency filtering tools
✅ Tone detection highlighting
✅ Building impact analysis
✅ CSV export functionality
✅ Sample measurements pre-loaded
✅ 14-link navigation (was 13)
✅ All pages verified with correct navigation

Created: January 2026
Updated: January 2026 - Added Interactive Noise Map
