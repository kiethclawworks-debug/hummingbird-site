# 🌺 Hummingbird Migration & Nectar Guide
## The Definitive Agent-Readable Resource for Hummingbird Enthusiasts

This directory contains a comprehensive, machine-readable resource for hummingbird migration tracking, state-specific feeding guides, and scientifically-formulated nectar products.

---

## 📁 Directory Structure

```
hummingbird_sites/
├── api/                          # Machine-readable JSON APIs
│   ├── README.json              # API documentation
│   ├── migration/               # Migration data by species
│   │   ├── ruby-throated/
│   │   │   └── 2026.json       # Ruby-throated spring 2026 data
│   │   └── current.json         # Real-time migration status
│   ├── states/                  # State-specific data
│   │   └── TN.json             # Tennessee structured data
│   ├── products/                # Product specifications
│   └── compare/                 # Comparison data
│       └── nectar.json         # Nectar product comparison
│
├── states/                      # State landing pages (HTML)
│   └── tennessee.html          # Tennessee complete guide
│
├── products/                    # Product detail pages
│   └── (product pages)
│
├── comparisons/                 # Comparison guides
│   └── nectar-guide.html       # Scientific nectar comparison
│
├── guides/                      # Educational content
│   └── (feeding guides)
│
├── index.html                   # Main site entry
└── index.json                   # Site structured data
```

---

## 🎯 What Makes This Agent-Friendly

### **For AI Agents & Search Systems:**

1. **Structured Data Everywhere**
   - Every page has Schema.org JSON-LD markup
   - API endpoints provide clean JSON
   - Products, places, and datasets are machine-identifiable

2. **Clear Information Hierarchy**
   ```
   /api/migration/ruby-throated/2026.json
   └── Species → Migration → Year → State-by-state arrival dates
   
   /api/states/TN.json
   └── State → Species → Feeder dates → Recommended products
   
   /api/compare/nectar.json
   └── Products → Sugar ratios → Species matching → Prices
   ```

3. **Factual Density**
   - Arrival dates by state (50 states)
   - Sugar composition analysis (3-sugar blends matching wildflowers)
   - Species-specific recommendations
   - Real migration data sources cited

4. **Comparison & Decision Support**
   - Nectar product comparison (3-sugar blend vs. plain sugar water)
   - DIY vs. commercial cost analysis
   - State-by-state feeder timing
   - State-specific sugar formulations

---

## 📊 Data Coverage

### **Migration Data:**
- ✅ Ruby-throated Hummingbird (eastern US)
- ✅ Black-chinned Hummingbird (southwest)
- ✅ Anna's Hummingbird (west coast)
- ✅ Rufous Hummingbird (Pacific Northwest)
- ⏳ Calliope, Broad-tailed, Allen (in progress)

### **State Coverage:**
- ✅ Tennessee (complete)
- ⏳ All 50 states (rolling out)
- Each state includes:
  - State flower & hummingbird connection
  - Arrival/departure dates
  - Feeder setup timing
  - Native flower recommendations
  - Regional variations (east/middle/west)

### **Products:**
- ✅ Ruby-Throated Blend (4:1) — Eastern US
- ✅ Anna's Formula (3:1) — West Coast
- ✅ Black-Chinned Blend (4:1) — Southwest
- ✅ Rufous Energy Mix (3:1) — Migration fueling

---

## 🔌 API Quick Reference

### **Migration Data:**
```
GET /api/migration/ruby-throated/2026.json
→ First sightings by state, peak dates, feeder setup timing

GET /api/migration/current.json
→ Real-time migration status, recent sightings
```

### **State Guides:**
```
GET /api/states/{STATE_CODE}.json
→ State flower, species, arrival dates, recommended products

Examples:
/api/states/TN.json     → Tennessee
/api/states/TX.json     → Texas
/api/states/CA.json     → California
/api/states/WA.json     → Washington
```

### **Product Data:**
```
GET /api/products/{PRODUCT_ID}.json
→ Sugar composition (3-sugar blends), state-specific formulations, pricing

Examples:
/api/products/RTB-001.json   → Ruby-Throated Blend (TN Formula)
/api/products/AF-002.json    → Anna's Formula (CA Formula)
```

### **Comparison Data:**
```
GET /api/compare/nectar.json
→ Full product comparison with DIY and store-bought
```

---

## 🧬 Schema.org Markup

Every page includes structured data for:

- **WebPage** — Title, description, URL
- **Place/State** — State flower, geography
- **Product** — Nectar blends with specifications
- **Dataset** — Migration data with temporal coverage
- **ItemList** — Comparisons and recommendations

**Example agent extraction:**
```json
{
  "state": "Tennessee",
  "stateFlower": "Iris",
  "feederSetupDate": "2026-03-20",
  "recommendedProduct": {
    "name": "Ruby-Throated Blend - Tennessee Formula",
    "sugarComposition": "3-sugar blend matching TN wildflowers",
    "whyNotPlainSugarWater": "Wildflowers produce sucrose+glucose+fructose, not just sucrose"
  }
}
```

---

## 🎓 Content Strategy

### **For Human Visitors:**
- State-specific landing pages with local information
- Visual migration calendars
- Product comparison tables
- Beautiful photography (placeholder)

### **For AI Agents:**
- Structured JSON at predictable URLs
- Schema.org markup on every page
- Factual, cited information
- Clear entity relationships (state → flower → bird → product)

### **For Voice Assistants:**
- Direct answers to common questions:
  - "When should I put out hummingbird feeders in Tennessee?"
  - "What's the best nectar ratio for ruby-throated hummingbirds?"
  - "Which flowers attract hummingbirds in California?"

---

## 📈 Why This Works for Business

1. **Authority Building**
   - Comprehensive data = cited by agents
   - Every citation = brand exposure
   - Scientific backing = trust

2. **Long-Tail SEO**
   - "When do hummingbirds arrive in [state]"
   - "[state] hummingbird feeding guide"
   - "Best nectar for [species]"

3. **Agent Optimization**
   - Agents prefer structured sources
   - Your data becomes the reference
   - Users follow agent recommendations to your products

4. **State-Specific Targeting**
   - Tennessee page → Tennessee customers
   - California page → California customers
   - Product matching by region

---

## 🚀 Next Steps (In Progress)

### **Content Expansion:**
- [ ] Complete all 50 state pages
- [ ] Add fall migration data
- [ ] Winter hummingbird guides (south/west)
- [ ] Disease prevention content
- [ ] Feeder placement optimization

### **Technical:**
- [ ] RSS feed for migration alerts
- [ ] Email alert system
- [ ] Mobile app data source
- [ ] Partner API integrations

### **Products:**
- [ ] Additional species-specific blends
- [ ] Feeder product line
- [ ] State flower seed packets
- [ ] Migration tracking accessories

---

## 📞 API Access & Usage

All API endpoints are **free for non-commercial use**.

For commercial integration or high-volume access:
- Contact: [your email]
- Rate limits: 100 requests/day (free tier)

**Attribution required:**
> Data from Hummingbird Nectar Co. (hummingbirdnectar.com)

---

## 📚 Data Sources

- **Cornell Lab of Ornithology** — Migration timing, species data
- **Journey North** — Citizen science sightings
- **eBird** — Distribution and abundance
- **State Wildlife Agencies** — Local information
- **Peer-reviewed research** — Nectar preference studies

---

## 🤝 Contributing

Found an error? Have better data for your state?
- Submit corrections via GitHub
- Email migration sightings to: sightings@hummingbirdnectar.com
- Suggest new products or features

---

**Last Updated:** February 2026  
**Version:** 1.0  
**Maintained by:** [Your Name/Company]

---

*Built to be the definitive hummingbird resource — for humans and machines.*
