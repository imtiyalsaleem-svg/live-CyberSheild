# CyberShield — Information Security Dashboard

This project is a full-featuredShield Information Security Operations Center dashboard. It includes a responsive and visually striking interface with live monitoring, alerts, network statistics, password strength analysis, security checklist, activity log, vulnerability status, and encoding/decoding tools.

---

## Features

### 1. Real-Time Clock and Live Monitoring
- Shows local time and UTC time in header and footer.
- Live monitoring indicator with blinking animation.

### 2. Alert Bar
- Horizontally scrolling alerts with different severity levels (Critical, Warning, Info).
- Uses CSS animations for smooth scrolling.

### 3. Statistics Overview
- Displays real-time animated counters for active threats, attacks blocked, nodes monitored, vulnerabilities, and active sessions.

### 4. Global Threat Map
- Visual representation with animated threat origin dots using CSS and JavaScript.

### 5. Network Monitor
- Bandwidth, packets/sec, average latency, uptime stats.
- Animated line chart with SVG showing network data trends.

### 6. Password Strength Analyzer
- Interactive input with strength meter bars.
- Validates password on length, uppercase, lowercase, numbers, symbols, and common words.
- Shows estimated crack time.

### 7. Security Checklist
- Interactive checklist to track security tasks.
- Priority badges with color coding.
- Mark items as done with checkmark animations.

### 8. Live Activity Log
- Real-time log of security events with color-coded severity tags.

### 9. Vulnerability Status
- Progress bars for different vulnerability levels and types.

### 10. Encode / Decode Utilities
- Supports Base64, ROT13, Hex, and Binary encoding and decoding.

---

## Technologies Used

- **HTML5:** Markup and structure.
- **CSS3:** Styling, layout with CSS Grid & Flexbox, animations, and custom properties (variables).
- **JavaScript:** Dynamic data handling, animations, interactive features.
- **SVG:** For network chart visualization.
- **Google Fonts:** 'Share Tech Mono', 'Orbitron', and 'Rajdhani' for the cyber aesthetic.

---

## Usage Instructions

1. Save the entire code as `index.html`.
2. Open the file in a modern web browser.
3. Interact with the dashboard:
   - See live updating stats and clock.
   - Scroll through alerts.
   - Use the password strength tool by entering text.
   - Encode or decode text with utility buttons.
   - Check and uncheck in the security checklist.
   - Watch animated threat map and network chart.
   - View live activity logs dynamically added.

---

## File Contents Summary- **HTML:** Structure of dashboard with sections like header, alert bar, main content (stats, tools, logs), footer.
- **CSS:** Embedded in `<style>`, defining color scheme, layout grids, typography, animations, and responsiveness.
- **JavaScript:** Embedded in `<script>`, handling clock updates, counters, network chart SVG path animation, threat map dots, activity logs, password strength checking, encode/decode functions, and checklist interactivity.

---

## Customization Tips

- Change colors and theme in CSS root variables (`:root`).
- Adjust alert messages and log events in JS arrays (`logEvents` and alert bar content).
- Modify checklist tasks in `checkItems` JS array.
- Extend encoding methods or add further security tools via JS.
- Update font families via Google Fonts link in `<head>` section.

---

## License

This project is provided for educational and demonstration purposes without warranty.

---

## Contact & Support

Reach out to your internal security or development teams for further customization or deployment.

---

Thank you for exploring CyberShield — your central hub for cyber defense visibility.
