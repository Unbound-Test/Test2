# Unbound Concierge Services - Coming Soon Website

## Files Included:

**Public Site (visible to anyone):**
- index.html (Coming Soon landing page)
- contact.html (General contact form for inquiries)

**Private Request Forms (direct links only - not linked from public site):**
- request-service.html (Vehicle & Home services form)
- request-travel.html (Travel planning form)

**Shared Files:**
- styles.css (All styling)
- logo.png (Your master logo with true black background)
- README.md (This file - setup instructions)

## Setup Instructions:

### Step 1: Upload to GitHub

1. Go to https://github.com/[your-username]/Unbound1
2. Click "Add file" → "Upload files"
3. Drag and drop ALL FILES:
   - index.html
   - contact.html
   - request-service.html
   - request-travel.html
   - styles.css
   - logo.png
   - README.md (optional)
4. Scroll down, add commit message: "Initial website upload"
5. Click "Commit changes"

### Step 2: Enable GitHub Pages (if not done already)

1. In your repository, click "Settings" (top menu)
2. Click "Pages" in left sidebar
3. Under "Build and deployment":
   - Source: "Deploy from a branch"
   - Branch: "main"
   - Folder: "/ (root)"
4. Click "Save"

### Step 3: Wait 2-3 Minutes

GitHub will build and deploy your site. Your site will be live at:
https://[your-username].github.io/Unbound1/

### Step 4: Set Up Formspree (Contact Forms)

You need to create THREE forms in Formspree:

**Form 1: General Contact (contact.html)**
1. Go to https://formspree.io and log in
2. Create form: "General Contact"
3. Copy form ID (looks like: xyzabc123)
4. Edit contact.html in GitHub, replace YOUR_FORM_ID

**Form 2: Vehicle & Home Services (request-service.html)**
1. Create form: "Service Requests"
2. Copy form ID
3. Edit request-service.html in GitHub, replace YOUR_VEHICLE_HOME_FORM_ID
4. Enable file uploads in Formspree form settings

**Form 3: Travel Planning (request-travel.html)**
1. Create form: "Travel Requests"
2. Copy form ID
3. Edit request-travel.html in GitHub, replace YOUR_TRAVEL_FORM_ID

All form submissions will go to hello@unboundconcierge.co.uk!

### Step 5: Private Request Forms - How to Use

**IMPORTANT:** The request forms (request-service.html and request-travel.html) are NOT linked from your public site. This is intentional for security.

**URLs will be:**
- Service requests: https://[username].github.io/Unbound1/request-service
- Travel requests: https://[username].github.io/Unbound1/request-travel

**Only share these links with trial advisors.** Anyone with the link can access the forms, but if their email isn't in your HubSpot contacts, you'll know they're not a trial participant and can ignore the submission.

**When onboarding trial advisors, send them:**
> Welcome to Unbound! Here are your request links:
> 
> **Vehicle/Home Services:** [your-url]/request-service
> **Travel Planning:** [your-url]/request-travel
> **Urgent:** WhatsApp [number]
> 
> Bookmark these for quick access!

### Step 5: Connect Custom Domain (When You Buy unboundconcierge.co.uk)

**In GitHub:**
1. Go to Settings → Pages
2. Under "Custom domain", enter: unboundconcierge.co.uk
3. Click Save
4. Wait for DNS check

**In GoDaddy:**
1. Go to DNS Management for unboundconcierge.co.uk
2. Add these records:

   A Records (all pointing to GitHub):
   - @ → 185.199.108.153
   - @ → 185.199.109.153
   - @ → 185.199.110.153
   - @ → 185.199.111.153

   CNAME Record:
   - www → [your-username].github.io

3. Wait 24-48 hours for DNS to propagate
4. Your site will be live at https://unboundconcierge.co.uk

GitHub will automatically generate FREE SSL certificate (HTTPS).

## Design Details:

**Structure:**
- **Public pages:** Coming Soon landing + General contact form
- **Private pages:** Service request form + Travel planning form (shared via direct links only)

**Colors:**
- Background: #000000 (pure black - makes logo float beautifully)
- Text: White (#FFFFFF)
- Accent/Buttons: #4A90E2 (professional blue)
- Button Hover: #5BA3F5 (lighter blue)

**Features:**
- Fully responsive (mobile, tablet, desktop)
- Large, impossible-to-miss buttons
- Clean, understated design matching your logo
- Professional blue accent color
- All forms send to hello@unboundconcierge.co.uk
- Company field for B2B contacts
- Travel form uses your refined question structure

**Messaging:**
- "Coming Soon" (not "Launching Soon")
- Tagline: "We Coordinate, Validate & Advocate"
- Description: "Expert lifestyle coordination for busy professionals"

**Security:**
- Request forms not linked from public site (access via direct URL only)
- Only trial advisors receive the links
- Email mismatch detection (if random person submits, their email won't be in your contacts)

## Need Help?

If anything doesn't work or you want to make changes, just ask!

---

**Current Status:** Ready to upload to GitHub!
