# Charm.io GTM System - Image Assets

## Image Inventory

### 1. value-vs-ease.png
**Title:** ICP Prioritization Matrix  
**Subtitle:** Strategic Value vs Ease of Penetration

**Description:**  
Strategic prioritization matrix used to evaluate and rank Ideal Customer Profiles (ICPs) based on two key dimensions:
- **Y-axis (Strategic Value):** Measures contract size and long-term potential of each ICP
- **X-axis (Ease of Penetration):** Reflects how easy it is to reach/engage the customer (message fit, persona accessibility)

**Quadrants:**
- **Top-Left (Blue) — High Strategic Value, Low Ease:** Retailers, Brands, Investors
- **Bottom-Right (Yellow) — Low Strategic Value, High Ease:** eComm SaaS, 3PLs, Agencies
- **Top-Right (Green) — High Strategic Value, High Ease (Ideal Zone):** Currently empty
- **Bottom-Left (Red) — Low Strategic Value, Low Ease:** Not occupied

**Key Insights:**
- Retailers and Brands ranked highest in strategic value (biggest revenue potential, harder to penetrate)
- 3PLs, SaaS, and Agencies were easier to penetrate (lower barrier, good for quick wins)
- Goal: Move more ICPs toward the top-right "high value, easy to penetrate" zone

---

### 2. volume-vs-conversion.png
**Title:** ICP Segmentation Chart  
**Subtitle:** Weekly Active Leads vs Conversion Rate

**Description:**  
Strategic segmentation and performance analysis mapping ICPs across two dimensions:
- **X-axis:** Weekly Active Leads (volume/reach potential)
- **Y-axis:** Conversion Rate (efficiency/quality of leads)

**Quadrants:**
1. **Top-Left: High Conversion, Targeted Volume**
   - ICPs: Agencies, SaaS, 3PLs
   - High efficiency, low-to-moderate volume
   - Lower contract values due to perceived simplicity

2. **Top-Right: High Conversion, Outbound Led**
   - ICPs: SaaS, Agencies, 3PLs (outbound motion)
   - Same ICPs as top-left but acquired via outbound efforts

3. **Bottom-Left: Long Cycle, High Value**
   - ICPs: Retailers, Brands, Investors
   - Low volume, very long sales cycles, high contract value
   - Complex use cases: due diligence, competitive intelligence, brand discovery

4. **Bottom-Right: High Volume, Selective**
   - ICPs: Retailers, Brands
   - High volume, selective conversion (lower rate but scalable)
   - Still high-value contracts when converted

**Right-Side Panels:**
- **Primary Converting Channel:** Email (teal) and LinkedIn (purple)
- **Sales Motion Preference:** Inbound for smaller ICPs, Outbound for larger/higher-value ICPs
- **Bubble Size:** Larger = Higher Contract Value

---

### 3. intent-vs-volume.png
**Title:** Signal Prioritization Matrix  
**Subtitle:** Buyer Intent vs Signal Volume

**Description:**  
Matrix for prioritizing leads based on signal strength:
- **Y-axis (Vertical):** Buyer Intent — How strong or direct the buyer's intent is
- **X-axis (Horizontal):** Signal Volume — How many signals/actions indicate interest

**Quadrants:**
- **Top-Left: High Intent, Low Volume → Immediate Outreach**
- **Top-Right: High Intent, High Volume → Immediate Outreach**
- **Bottom-Left: Low Intent, Low Volume → Deprioritize**
- **Bottom-Right: Low Intent, High Volume → Nurture**

**Signal Types & Placement:**

| Signal Type | Quadrant | Why? |
|-------------|----------|------|
| Demo Request Inbound | Top-Left | Very high intent — they want to see the product now |
| Contact Us Form Inbound | Top-Left | Direct inquiry = high intent |
| Free User Login Inbound | Top-Right | High engagement + repeated use = strong intent + high volume |
| Event Attendee Outbound | Top-Right | Attended event → active interest; likely multiple touchpoints |
| Company News Outbound | Bottom-Left | Passive consumption — no real commitment |
| White Paper Inbound | Bottom-Right | Downloaded content = interest, but not ready to buy |
| Anon Web Visitor Inbound | Bottom-Right | Visited site anonymously — researching or browsing |

**Sales Motion Legend:**
- **Inbound (Teal):** Prospects who initiated contact (demo request, white paper download)
- **Outbound (Purple):** Prospects reached out to by sales/marketing team

**Strategic Takeaways:**
- Focus on Top Quadrants First: Demo Request, Contact Us Form, Free User Login
- Leverage Event Attendees: Treat like inbound high-intent leads
- Nurture Lower-Intent Leads: Automated campaigns for white paper downloaders and anonymous visitors
- Avoid Wasting Time on Company News Readers: Unless part of broader account-based strategy

---

### 4. Signal-Based-Workflow.png
**Title:** Signal-Based Lead Management Workflow

**Description:**  
Comprehensive B2B lead management and sales engagement workflow integrating:
- Inbound and outbound leads
- AI-powered enrichment/classification
- Intent-based routing
- Multi-channel outreach
- CRM logging

**6 Phases:**

**Phase 1: Lead Sources**
- **Inbound (via HubSpot):** Demo Request, Contact Us Form, White Paper Download, Free User Sign-in, RB2B Anon Web Visitor
- **Outbound (via Clay + Apollo):** Events Portal, Cold Prospecting Lists, Market Intelligence, Re-Engage

**Phase 2: Enrichment & Classification**
- Tools: Clay, Apollo, OpenAI
- Processes: Firmographic enrichment, ICP classification, Generative AI messaging, Contact data validation

**Phase 3: Intent vs Fit Decision**
- Evaluates each lead on Intent (likelihood to buy) and Fit (ICP match)
- **High Intent (Green):** Immediate Action → Demo booking + AE nurture
- **Medium Intent (Cyan):** SDR nurture sequence
- **Low Intent (Yellow):** SDR outbound sequence
- **Disqualified (Red):** Label and log

**Phase 4: Sales Engagement**
- Tools: Instantly, HeyReach, LinkedIn
- Multi-channel touchpoints: Email, LinkedIn, Phone
- High Intent → AE Nurture + Demo on AE Calendar
- Medium/Low Intent → SDR Nurture/Outbound Sequences

**Phase 5: Conversion & Logging**
- **Interested (Green):** Log activities, reporting, data labeling in HubSpot
- **Not Interested (Red):** Label "Not Interested" → logged in HubSpot
- **No Response (7 days):** Re-enter cycle or move to re-engagement
- **Churned (90 days):** Move to "Re-Engage" bucket

**Phase 6: CRM & Analytics**
- All activities logged in HubSpot
- Full audit trail, performance metrics, continuous improvement

**Toolstack:**
- Lead Capture & CRM: HubSpot
- Enrichment & Classification: Clay, Apollo, OpenAI
- Intent Scoring: Custom logic
- Outreach Automation: Instantly, HeyReach, LinkedIn
- Scheduling: AE Calendar integration
- Analytics & Logging: HubSpot

---

### 5. system-flow.png
**Title:** GTM System Toolstack

**Description:**  
Collage of integrated tools and platforms used in the GTM system:

**Visible Tools:**
- **HubSpot:** CRM, marketing automation, sales tools
- **Clay:** Data enrichment and contact/profile management
- **Instantly:** Cold email outreach automation
- **Octoparse:** Web scraping and data extraction
- **Profiles:** Identity management / CRM feature
- **Apollo:** B2B contact database and intent signals
- **OpenAI:** Generative AI for messaging and classification

**Use Context:**
- Sales development rep (SDR) workflows
- Lead generation & enrichment pipelines
- Marketing tech stack integrations

---

## Usage Notes

- All images are stored in this directory: `/public/assets/images/charm-gtm-system/`
- Reference in Next.js using: `/assets/images/charm-gtm-system/[filename]`
- Images are displayed on the case study page: `/projects/charm-gtm-system`
