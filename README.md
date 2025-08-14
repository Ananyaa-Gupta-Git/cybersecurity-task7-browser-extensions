# Task 7: Browser Extension Security Audit

## Objective
Learn to identify and remove potentially harmful browser extensions to improve browser security.

## Tools Used
- Browser: Google Chrome
- Extension Manager: Chrome Extensions Manager (chrome://extensions/)

## Process Followed

### 1. Initial Extension Audit
- Opened Chrome extension manager
- Documented all installed extensions
- Total extensions found: 5

### 2. Extension Analysis
For each extension, I checked:
- Installation date and source
- Permissions granted
- User reviews and ratings
- Developer information
- Necessity and usage frequency

### 3. Suspicious Extensions Identified
One suspicious extension was identified during the audit:

| Extension Name | Reason for Suspicion | Action Taken |
|----------------|---------------------|--------------|
| ChatGPT search | Unknown installation (don't remember installing), requests broad site access permissions | Disabled then Removed |

### 4. Extensions Removed
- **ChatGPT search (v1.11)** - Removed due to:
  - Unknown installation source (user doesn't remember installing)
  - Requests permission to "Change your search settings to: chatgpt.com"
  - Has access to read and change data on websites
  - Potentially unwanted behavior (search hijacking)

### 5. Performance Assessment
After removing suspicious extensions:
- Browser startup time: Not specifically measured but no noticeable issues
- Page loading speed: No change observed
- Overall browser responsiveness: Normal operation maintained

## Key Security Findings

### Red Flags Identified
- **Unknown Installation**: ChatGPT search extension was present without user knowledge
- **Search Engine Modification**: Extension had permission to change default search settings
- **Broad Site Access**: Extension could read and change data on websites
- **Potential Browser Hijacking**: Search redirection capabilities pose security risk

### Best Practices Learned
- Regularly audit installed extensions (monthly recommended)
- Only install extensions from official Chrome Web Store
- Review permissions carefully before installation
- Remove extensions you don't remember installing
- Be cautious of extensions that modify search settings
- Check extension reviews and ratings before installing
- Monitor for unusual browser behavior

## Screenshots
- `extensions_present.png` - Screenshot of all extensions before audit
- `extension_1.png` - ChatGPT search extension details
- `extension_2.png` - ChatGPT search permissions page
- `extension_3.png` - Google Docs Offline extension details  
- `extension_4.png` - McAfee WebAdvisor extension details
- `extension_5.png` - PerfectPixel extension details
- `extension_6.png` - Video Speed Controller extension details
- `extension_disabled.png` - Screenshot showing ChatGPT search disabled
- `extension_reviews.png` - Chrome Web Store reviews for ChatGPT search
- `removing_extension.png` - Screenshot showing removal process
- `final_extensions.png` - Screenshot of extensions after cleanup

## Interview Questions Preparation

### 1. How can browser extensions pose security risks?
Browser extensions can pose significant security risks including data theft through excessive permissions, malicious code injection into web pages, privacy violations by tracking browsing habits, credential harvesting from login forms, providing backdoor access to systems, injecting unwanted advertisements, and browser hijacking by changing settings. The ChatGPT search extension I found demonstrated some of these risks by having broad site access and search modification capabilities.

### 2. What permissions should raise suspicion?
Suspicious permissions include "Access your data on all websites," reading browsing history, managing bookmarks, camera/microphone access when unnecessary, location access, and permission to change search settings. The ChatGPT search extension I removed had permission to change search settings and read/change website data, which are red flags for potentially unwanted behavior.

### 3. How to safely install browser extensions?
Safe installation practices include only using official browser stores, researching extensions through reviews and ratings, verifying developer reputation, carefully reading requested permissions, ensuring extensions are actively maintained, choosing popular well-reviewed extensions, reading privacy policies, and installing only necessary extensions.

### 4. What is extension sandboxing?
Extension sandboxing is a security mechanism that isolates extensions in restricted environments, limits system access, enforces permission models, prevents cross-extension interference, reduces attack surfaces, and runs extensions in separate processes from the main browser to contain potential damage.

### 5. Can extensions steal passwords?
Yes, extensions can steal passwords through form field access, keylogger functionality, DOM manipulation, cookie theft, credential manager access, network monitoring, and JavaScript injection. This is why reviewing permissions is crucial before installation.

### 6. How to update extensions securely?
Secure update practices include enabling automatic updates from official stores, monitoring update notifications, verifying update sources, reviewing new permissions, reading update notes, backing up browser data before major updates, and testing functionality after updates.

### 7. Difference between extensions and plugins?
Extensions use web technologies (HTML, CSS, JS) and are sandboxed with permission-based security, while plugins use native code with direct system access. Extensions extend browser functionality while plugins handle specific content types. Modern browsers favor extensions over plugins for security reasons.

### 8. How to report malicious extensions?
To report malicious extensions, visit the extension's page in Chrome Web Store and click "Report abuse," select appropriate categories, provide detailed descriptions with screenshots, and consider reporting to browser vendors' security teams for severe cases.

## Research Sources
- Chrome Extension Security Documentation
- Browser security best practices guides
- Chrome Web Store policies and guidelines
- Cybersecurity extension audit tutorials
- Extension permission analysis resources

## Conclusion
This security audit successfully identified and removed one suspicious extension (ChatGPT search) that was installed without my knowledge and had potentially risky permissions. The exercise demonstrated the importance of regular extension audits and careful permission review. Key learnings include the need for proactive extension management, understanding permission implications, and maintaining awareness of browser security risks.

The remaining extensions (Google Docs Offline, McAfee WebAdvisor, PerfectPixel, and Video Speed Controller) were verified as legitimate and necessary, with appropriate permissions for their functions.

---
*Task completed on: August 14, 2025*
*Browser used: Google Chrome*
