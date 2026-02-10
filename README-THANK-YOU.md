# Adding Custom Thank You Page (Public Contact Form Only)

## What's New:

✅ **Custom Thank You Page** - Professional branded confirmation for the public "Get In Touch" form
✅ **Private forms unchanged** - Service/Travel request forms keep default Formspree confirmation (internal use only)

## Files to Upload:

**NEW files:**
- thank-you.html (Confirmation page after contact form submission)
- contact.html (Updated with redirect to thank-you page)

**Keep your existing files:**
- index.html (unchanged)
- request-service.html (unchanged - internal use)
- request-travel.html (unchanged - internal use)
- styles.css (unchanged)
- logo.png (unchanged)

## Setup Instructions:

### Step 1: Update contact.html Before Uploading

Open `contact.html` and find this line:
```html
<input type="hidden" name="_next" value="https://yourusername.github.io/Unbound1/thank-you">
```

**Replace `yourusername` with your actual GitHub username.**

For example, if your GitHub username is `john-smith`:
```html
<input type="hidden" name="_next" value="https://john-smith.github.io/Unbound1/thank-you">
```

### Step 2: Upload to GitHub

1. Go to https://github.com/[your-username]/Unbound1
2. Click "Add file" → "Upload files"
3. Upload ONLY these two files:
   - **thank-you.html** (new file)
   - **contact.html** (replaces existing)
4. Commit message: "Added custom thank you page for contact form"
5. Click "Commit changes"

### Step 3: Test It

1. Wait 2-3 minutes for GitHub Pages to update
2. Go to your contact page: https://[username].github.io/Unbound1/contact
3. Fill out the form with test data
4. Submit
5. You should see your branded thank-you page (not Formspree's generic page)

## How It Works:

**Public Contact Form (contact.html):**
- User submits → Custom thank-you page ✅ Professional

**Private Request Forms (service/travel):**
- User submits → Default Formspree confirmation (fine for internal use)

## After Custom Domain Setup:

When you connect unboundconcierge.co.uk, update contact.html redirect:
- Change from: `https://yourusername.github.io/Unbound1/thank-you`
- To: `https://unboundconcierge.co.uk/thank-you`

---

**That's it!** Simple update, professional result for your public-facing form.
