# CyberGator 🐊

**Threat Hunting & Threat Intelligence Platform**

A dual-purpose cybersecurity platform combining automated threat intelligence aggregation with AI-powered threat hunting hypothesis generation and comprehensive OSINT keyboard shortcuts for rapid IOC investigation.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-web-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

## 🚀 Features

### CyberGator - Threat Intelligence & Hunting

**Real-Time News Aggregation**
- **20+ RSS feeds** from trusted cybersecurity sources
- **Auto-refresh capability** for latest threat intelligence
- **Deduplication engine** removes redundant articles across sources
- **Live feed status** indicator showing connection health
- **Session caching** for fast page loads and offline viewing

**AI-Powered Threat Hunting Hypotheses**
- **Automated hypothesis generation** based on current threat landscape
- **10 unique hunting scenarios** per generation cycle
- **MITRE ATT&CK mapping** with TTPs (Tactics, Techniques, Procedures)
- **Actionable search guidance** for SOC analysts
- **Creative hunting strategies** including honeypots and deception

**Modern UX**
- **Cyberpunk aesthetic** with glowing effects and animations
- **Dark theme** optimized for extended monitoring sessions
- **Responsive design** works on desktop, tablet, and mobile
- **Card-based layout** for easy article scanning
- **Smooth animations** and visual feedback

### OSINTGator - Keyboard-Driven OSINT

**Instant OSINT Access**
- **26 OSINT tools** mapped to keyboard shortcuts (A-Z)
- **One-click/one-key access** to threat intelligence platforms
- **Visual keyboard layout** with color-coded categories
- **Tool descriptions** showing supported IOC types
- **Zero typing** required - just press a key

**Supported IOC Types**
- IP addresses
- Domains and URLs
- File hashes (MD5, SHA1, SHA256)
- ASNs and network ranges
- DNS records

## 🔧 Tools & Sources

### CyberGator News Sources

**Primary Threat Intelligence**
- Bleeping Computer
- The Hacker News
- Threatpost
- Dark Reading
- Krebs on Security

**Government & Industry**
- CISA Current Activity
- Security Week
- ZDNet Security
- CSO Online
- SC Magazine

**Vendor Intelligence**
- Sophos Naked Security
- Schneier on Security
- Infosecurity Magazine

**Specialized Coverage**
- CyberScoop
- Cybersecurity Dive
- Help Net Security
- Data Breach Today
- Bank Info Security
- Gov Info Security
- Healthcare Info Security

### OSINTGator Tool Matrix

#### Row 1 (Green) - Primary Intel Platforms
- **Q** - Talos Intelligence (IPs, Domains, Hashes)
- **W** - WHOIS (Domains)
- **E** - IPVoid (Domains)
- **R** - AlienVault OTX (IPs, Domains, Hashes)
- **T** - ThreatFox (IOCs, Hashes)
- **Y** - YARAify (Hashes)
- **U** - URLScan (URLs)
- **I** - IPinfo.io (IPs)
- **O** - Onyphe (IPs, Domains)
- **P** - Pulsedive (IPs, URLs)

#### Row 2 (Blue) - Search & Analysis
- **A** - AbuseIPDB (IPs)
- **S** - Shodan (IPs, Domains)
- **D** - DNSTrails/SecurityTrails (Domains, DNS)
- **F** - Fofa (IPs, Domains)
- **G** - GreyNoise (IPs)
- **H** - Hybrid Analysis (Hashes, URLs)
- **J** - JoeSandbox (Hashes, URLs)
- **K** - Kaspersky TI (IPs, Hashes)
- **L** - DNSlytics (IPs, Domains)

#### Row 3 (Purple) - Advanced Recon
- **Z** - ZoomEye (IPs, Domains)
- **X** - X-Force Exchange (IPs, Hashes)
- **C** - Censys (IPs, Domains)
- **V** - VirusTotal (IPs, Hashes, URLs, Domains)
- **B** - BGPView (ASNs, IPs)
- **N** - Netlas (IPs, Domains)
- **M** - Maltiverse (IPs, Hashes)

## 🛠️ Installation

### Option 1: GitHub Pages (Recommended)
Visit the live deployment: `https://indocanadian416.github.io/CyberGator/`

### Option 2: Local Deployment
```bash
# Clone the repository
git clone https://github.com/indocanadian416/CyberGator.git

# Navigate to directory
cd CyberGator

# Open index.html in your browser
open index.html
```

### Option 3: Web Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Then navigate to http://localhost:8000
```

## 📖 Usage

### CyberGator Mode

**Viewing Threat Intelligence**
1. Page loads automatically with latest 15 news articles
2. Articles displayed by newest first
3. Click article titles to read full stories
4. Use refresh button (bottom) to fetch latest feeds

**Generating Hunting Hypotheses**
1. Click "Generate Threat Hunting Hypothesis" button
2. Wait 1-2 seconds for AI processing
3. Review 10 generated hypotheses with:
   - **Hypothesis statement**: What to hunt for
   - **Unconventional insight**: Why this matters now
   - **TTPs**: MITRE ATT&CK techniques involved
   - **Search guidance**: Where/how to look
   - **Out-of-box ideas**: Creative detection strategies
4. Implement hypotheses in your SIEM/EDR platform

### OSINTGator Mode

**Keyboard Navigation**
1. Click "OSINTGator" tab in navigation
2. Press any letter key (A-Z) to open that tool
3. Or click on visual keyboard buttons
4. Tool opens in new tab for investigation

**Tool Selection Strategy**
- **IPs**: Start with A (AbuseIPDB), G (GreyNoise), Q (Talos)
- **Domains**: Try W (WHOIS), E (IPVoid), D (DNSTrails)
- **Hashes**: Use V (VirusTotal), T (ThreatFox), Y (YARAify)
- **URLs**: Check U (URLScan), H (Hybrid Analysis)
- **Advanced recon**: S (Shodan), C (Censys), Z (ZoomEye)

## 🎯 Use Cases

### Threat Hunting Operations
- **Daily hypothesis generation** for proactive hunting
- **News-driven hunting** based on emerging threats
- **Creative detection ideas** beyond standard playbooks
- **MITRE ATT&CK alignment** for structured hunting

### Incident Response
- **Rapid IOC pivoting** via OSINTGator keyboard shortcuts
- **Multi-source validation** of indicators
- **Threat context gathering** from aggregated news
- **Campaign tracking** through related articles

### Security Operations Center (SOC)
- **Morning briefings** with latest threat intelligence
- **Shift handover context** from recent news
- **Alert enrichment** using OSINT tools
- **Threat landscape awareness** for analysts

### Threat Intelligence Analysts
- **News aggregation** from 20+ trusted sources
- **Trend identification** through hypothesis patterns
- **IOC research workflow** optimization
- **Intelligence product generation** based on current events

### Security Researchers
- **Emerging threat tracking** via real-time feeds
- **Multi-platform correlation** for IOC analysis
- **Hypothesis testing** against current threat data
- **Tool discovery** through OSINTGator collection

## 🔍 Technical Details

### CyberGator Architecture
- **Client-side processing** - no backend required
- **RSS2JSON proxy** for CORS bypass on RSS feeds
- **Session storage** for caching (persists during browser session)
- **Timeout handling** (5s per feed) for reliability
- **Deduplication algorithm** using normalized URLs and title matching
- **Fallback mechanism** to cached data on fetch failures

### Hypothesis Generation Logic
- **Article sampling**: Top 10 most recent articles
- **Pattern templates**: 10 unique hypothesis scenarios
- **Context enrichment**: Links hypotheses to specific articles and dates
- **TTP mapping**: Associates with MITRE ATT&CK techniques
- **Search strategies**: Provides actionable detection queries
- **Creative elements**: Includes honeypot and deception ideas

### OSINTGator Implementation
- **Keyboard event listeners** for global key capture
- **Access keys** for button-based navigation
- **Tab isolation** - tools open in new browser tabs
- **Visual feedback** with hover effects and color coding
- **Mobile responsive** with touch-friendly buttons

## 🎨 Design Philosophy

### Visual Theme
- **Cyberpunk aesthetic** with cyan/purple neon accents
- **Orbitron font** for headers (futuristic feel)
- **Open Sans font** for readability in content
- **Glassmorphism effects** on cards and panels
- **Animated scanlines** and glow effects
- **Color psychology**: Green (safe), Blue (info), Purple (advanced)

### User Experience
- **Zero-friction navigation** between modes
- **Keyboard-first design** for power users (OSINTGator)
- **Progressive enhancement** - works without JavaScript for basic viewing
- **Performance optimization** with caching and timeouts
- **Accessibility** with ARIA labels and keyboard navigation

## 🌐 Browser Compatibility

- Chrome/Edge (Chromium) 90+
- Firefox 88+
- Safari 14+
- Opera 76+

**Requirements**:
- JavaScript enabled
- Session storage support
- Modern CSS support (flexbox, grid)

## 📱 Responsive Design

- **Desktop (1024px+)**: 3-column news grid, full keyboard layout
- **Tablet (768px-1023px)**: 2-column grid, wrapped keyboard
- **Mobile (<768px)**: Single column, stacked keyboard layout

## 🔐 Privacy & Security

- **No telemetry** - zero tracking or analytics
- **Client-side only** - no data sent to servers (except RSS proxies)
- **No authentication** - no accounts or login required
- **Session storage** - data cleared when browser closes
- **HTTPS links** - all OSINT tools use secure connections

## 🤝 Contributing

Contributions welcome! Areas for improvement:
- Additional RSS feed sources
- Enhanced hypothesis generation templates
- More OSINT tool integrations
- UI/UX refinements
- Performance optimizations
- Export features (PDF, JSON)

## 📝 License

MIT License - free for personal and commercial use.

## 👤 Author

**Pratik Goswami**
- GitHub: [@indocanadian416](https://github.com/indocanadian416)
- Role: Threat Researcher & Hunter

## 🙏 Acknowledgments

- All cybersecurity news sources and RSS feed providers
- [RSS2JSON](https://rss2json.com/) for CORS proxy service
- OSINT tool providers for free threat intelligence platforms
- Cybersecurity community for continuous threat intelligence sharing

## 📊 Statistics

- **News Sources**: 20 RSS feeds
- **OSINT Tools**: 26 platforms
- **Coverage**: Global cybersecurity threat landscape
- **Hypothesis Templates**: 10 unique scenarios
- **Update Mechanism**: Real-time with auto-refresh
- **Articles Displayed**: Up to 15 most recent

---

**Built with ❤️ for threat hunters and security analysts**

*Stay vigilant. Hunt proactively. Investigate efficiently.*