# Extension Analysis Report

## Extension Inventory

### Extension 1: ChatGPT search
- **Developer:** chatgpt.com
- **Version:** 1.11
- **Installation Date:** Unknown (suspicious - user doesn't remember installing)
- **User Rating:** 3.3/5 stars
- **Number of Users:** 5,000,000+ users (from Chrome Web Store)
- **Size:** < 1 MB
- **Permissions Requested:**
  - [x] Change your search settings to: chatgpt.com
  - [x] Read and change all your data on websites you visit
  - [x] Access automatically on chatgpt.com/*
  - [ ] Camera access - No
  - [ ] Microphone access - No
  - [ ] Location access - No
  - [ ] Manage bookmarks - No
  - [ ] Modify cookies - No

**Risk Assessment:** HIGH
**Action Taken:** Removed
**Notes:** User doesn't remember installing this extension. Has broad permissions to modify search settings and access website data. Potential browser hijacking risk.

---

### Extension 2: Google Docs Offline
- **Developer:** Google (Installed by default)
- **Version:** 1.94.1
- **Installation Date:** Default installation
- **User Rating:** N/A (Official Google extension)
- **Number of Users:** Default installation
- **Size:** < 1 MB
- **Permissions Requested:**
  - [x] Read and change all your data on docs.google.com
  - [x] Read and change all your data on drive.google.com
  - [ ] Camera access - No
  - [ ] Microphone access - No
  - [ ] Location access - No
  - [ ] Manage bookmarks - No
  - [ ] Modify cookies - No

**Risk Assessment:** LOW
**Action Taken:** Keep
**Notes:** Official Google extension for offline document access. Necessary permissions for functionality.

---

### Extension 3: McAfee® WebAdvisor
- **Developer:** McAfee
- **Version:** 8.1.0.7038
- **Installation Date:** Added by third-party (antivirus installation)
- **User Rating:** N/A
- **Number of Users:** Unknown
- **Size:** 23.9 MB
- **Permissions Requested:**
  - [x] Read and change all your data on websites you visit
  - [x] Automatically allow access on all sites
  - [ ] Camera access - No
  - [ ] Microphone access - No
  - [ ] Location access - No
  - [ ] Manage bookmarks - No
  - [ ] Modify cookies - No

**Risk Assessment:** MEDIUM
**Action Taken:** Keep (Security software)
**Notes:** Legitimate security extension from McAfee. Large file size but provides web protection.

---

### Extension 4: PerfectPixel by WellDoneCode
- **Developer:** WellDoneCode
- **Version:** 2.2.0.8
- **Installation Date:** User installed for web development
- **User Rating:** Available on Chrome Web Store
- **Number of Users:** Unknown
- **Size:** 2.9 MB
- **Permissions Requested:**
  - [x] Read and change all your data on websites you visit (On all sites)
  - [ ] Camera access - No
  - [ ] Microphone access - No
  - [ ] Location access - No
  - [ ] Manage bookmarks - No
  - [ ] Modify cookies - No

**Risk Assessment:** LOW-MEDIUM
**Action Taken:** Keep
**Notes:** Web development tool for pixel-perfect design. Broad permissions but legitimate use case.

---

### Extension 5: Video Speed Controller
- **Developer:** Unknown (Chrome Web Store)
- **Version:** 0.9.2
- **Installation Date:** User installed for video control
- **User Rating:** Available on Chrome Web Store
- **Number of Users:** Unknown
- **Size:** < 1 MB
- **Permissions Requested:**
  - [x] Read your browsing history
  - [x] Read and change all your data on websites you visit (On all sites)
  - [ ] Camera access - No
  - [ ] Microphone access - No
  - [ ] Location access - No
  - [ ] Manage bookmarks - No
  - [ ] Modify cookies - No

**Risk Assessment:** MEDIUM
**Action Taken:** Keep
**Notes:** Useful for video playback control. Browsing history access is somewhat concerning but within expected functionality.

---

## Risk Assessment Criteria

### High Risk Red Flags
- Unknown or suspicious developer
- Requests excessive permissions
- Poor or no user reviews
- Recently installed without user knowledge
- Suspicious behavior or pop-ups
- Not available on official extension store

### Medium Risk Indicators
- Requests more permissions than necessary
- Few user reviews or ratings
- Older extension with no recent updates
- Generic or poorly written description

### Low Risk Signs
- Well-known developer
- Minimal, relevant permissions
- Good user reviews and ratings
- Regular updates
- Clear, professional description

## Summary
- **Total Extensions Analyzed:** 5
- **High Risk Extensions:** 1 (ChatGPT search - Removed)
- **Medium Risk Extensions:** 2 (McAfee WebAdvisor, Video Speed Controller - Kept)
- **Low Risk Extensions:** 2 (Google Docs Offline, PerfectPixel - Kept)
- **Extensions Removed:** 1
- **Extensions Kept:** 4

## Key Findings
1. **Suspicious Installation**: ChatGPT search extension was present without user knowledge
2. **Permission Concerns**: Several extensions had broad website access permissions
3. **Legitimate Tools**: Most extensions serve legitimate purposes for productivity and security
4. **Third-party Installations**: McAfee extension was bundled with antivirus software
