# San Mateo Science Center Noise Advocacy Website

Complete website documentation for the San Mateo Science Center HVAC noise complaint case against Longfellow Real Estate Partners at 901/951 Mariners Island Boulevard.

## 📋 Overview

This website provides comprehensive documentation, interactive tools, and technical resources for the ongoing low-frequency HVAC noise complaint affecting residents at 915 Shoreline Drive and surrounding Harbortown community.

## 🗂️ Website Structure

### Core Pages
- **index.html** - Homepage with interactive Google Maps showing HVAC sources
- **science_center_case.html** - Detailed case documentation
- **welcome_to_neighborhood.html** - Welcome letter to Longfellow
- **community_complaints.html** - Community feedback and survey results

### Interactive Tools
- **wall_transmission.html** - Low-frequency sound transmission visualizer
  - 900×700px canvas with phase-continuous wave animation
  - SignalScope CSV upload (source & receiver measurements)
  - Horizontally aligned dB(A) measurement boxes
  - 23 frequency buttons (6.3 Hz - 1000 Hz)
  - iMM-6C microphone limitation warnings
- **interactive_noise_map.html** - Google Maps with acoustic overlays
- **data_import.html** - SignalScope CSV data import tool
- **ansi_calculator_flowchart.html** - ANSI S12.9 Part 4 penalty calculator

### HVAC Technical Documentation
- **hvac_system_complete_schematic.html** - Complete system overview
- **hvac_system_schematic.html** - Simplified schematic
- **hvac_schematic_ashrae_annotated.html** - ASHRAE standard annotations
- **hvac_clean_schematic.html** - Clean diagram
- **hvac_diagram.html** - Alternative visualization

### Legal & Standards
- **ansi_s12_9_part_4.html** - ANSI acoustic standard documentation
- **penalty_application_guide.html** - How to apply tonal penalties
- **model_noise_ordinance.html** - Proposed ordinance improvements
- **comparative_standards.html** - Bay Area municipality comparison
- **pe_ethics_health_safety.html** - PE Canon of Ethics (health/safety)
- **potential_solutions.html** - Technical mitigation strategies
- **technical_resources.html** - Additional reference materials

## 🚀 Deployment

### Quick Start
1. Clone this repository
2. Upload all HTML files to your web server root directory
3. Access via: `https://yourwebsite.com/index.html`

### Requirements
- Web server with HTML support (Apache, Nginx, GitHub Pages, Netlify, etc.)
- Google Maps API key (for interactive maps)
- Modern web browser (Chrome, Firefox, Safari, Edge)

### Local Testing
```bash
# Simple HTTP server (Python)
python3 -m http.server 8000

# Or using Node.js
npx http-server
```

Then visit: `http://localhost:8000/index.html`

## 🔧 Configuration

### Google Maps API Key
Edit these files and add your API key:
- `index.html` (line ~820)
- `interactive_noise_map.html`

Replace:
```html
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap"></script>
```

## 📊 Features

### Acoustic Measurements
- Real SignalScope X data upload support
- A-weighted and C-weighted dB calculations
- 1/3 octave band analysis (6.3 Hz - 1000 Hz)
- Automatic ANSI S12.9 Part 4 tonal penalty calculation

### Interactive Visualizations
- Google Maps with HVAC source markers
- Noise contour circles (color-coded by intensity)
- Phase-continuous wave transmission through walls
- 3D building view with satellite imagery

### Technical Documentation
- Williams v. Invenergy case law analysis
- WHO Night Noise Guidelines
- San Mateo Municipal Code §7.16.040(m) nuisance statute
- Developer agreement breach documentation

## 📝 Key Technical Details

### Measurement Equipment
- **Microphone:** Dayton iMM-6C (calibrated 18 Hz - 20 kHz)
- **Software:** SignalScope X
- **Device:** iPad Air
- **Warning:** Frequencies below 18 Hz may not be reliable

### Measured Data
- **Exterior (Before Wall):** ~54.3 dB(A), 60.5 dB(C)
- **Dominant Frequency:** 200 Hz tonal peak
- **C-A Differential:** 6.2 dB (indicates low-frequency content)
- **Distance:** 585 feet from HVAC source

### Legal Framework
- San Mateo Municipal Code §7.30 (Noise Regulations)
- San Mateo Municipal Code §7.16.040(m) (Public Nuisance)
- San Mateo Municipal Code §27.02.060 (Equipment Screening)
- Code Enforcement Case: CE-2024-000294

## 📚 Documentation References

1. Agreement between Longfellow and Harbortown HOA (April 2022)
2. Colin Gordon Associates Noise Analysis (April 2022)
3. Colin Gordon Associates Noise Survey (July 2024)
4. Leventhall, H.G. "Low Frequency Noise and Annoyance" (2004)
5. ANSI/ASA S12.9-2016/Part 4 (R2025)
6. WHO Night Noise Guidelines for Europe (2009)

## 🎯 Project Goals

1. Document persistent low-frequency HVAC noise violations
2. Provide technical evidence of acoustic measurements
3. Demonstrate equipment screening requirement violations
4. Build community awareness and support
5. Push for municipal code enforcement

## 👤 Author

**Michael Zaller**  
915 Shoreline Drive  
San Mateo, CA 94404

**Case Details:**
- Date noise began: June 2024
- Code Enforcement Case: CE-2024-000294 (filed July 3, 2024)
- Affected properties: 915 Shoreline, 894 Wharfside, 884 Wharfside

## 📄 License

This documentation is provided for advocacy and educational purposes.

## 🔗 External Resources

- [San Mateo Municipal Code](https://law.cityofsanmateo.org/)
- [WHO Night Noise Guidelines](https://www.euro.who.int/en/publications)
- [ANSI Acoustical Standards](https://www.acousticalsociety.org/)
- [Williams v. Invenergy Case Law](https://casetext.com/case/williams-v-invenergy-llc)

## 📧 Contact

For questions about this case or website:
- Email: smnoise32@gmail.com
- Survey: https://www.surveymonkey.com/r/harbortown-noise

---

**Last Updated:** January 8, 2026  
**Version:** 2.0 - Complete rebuild with updated navigation
