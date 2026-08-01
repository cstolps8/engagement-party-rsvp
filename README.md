# Engagement Party RSVP Website

A GitHub Pages site for our engagement celebration with RSVP collection powered by Google Forms + Google Sheets.

## ✨ What's included

- Flyer-inspired one-page event website
- Event details section
- RSVP section with:
  - **Direct RSVP button** (opens Google Form in new tab)
  - **Embedded Google Form** (optional)
- Safety/privacy notes for RSVP data storage
- Mobile-friendly responsive design

## 🚀 Deploy on GitHub Pages

1. Go to your repository **Settings** → **Pages**
2. Under **Build and deployment**:
   - **Source**: Deploy from a branch
   - **Branch**: `main`
   - **Folder**: `/ (root)`
3. Save and wait ~1–2 minutes
4. Your site URL will look like:
   `https://cstolps8.github.io/engagement-party-rsvp/`

## 📝 Connect your Google Form

Open `index.html` and replace the placeholders:

- `YOUR_GOOGLE_FORM_LINK`
- `YOUR_GOOGLE_FORM_EMBED_LINK`

### Get the right links

In Google Forms:
1. Click **Send**
2. For button link: copy the normal form URL
3. For embed: click **<> Embed HTML** and copy the `src` URL

## ✅ Recommended RSVP fields (for accurate guest list)

- Full name
- Email (or phone)
- Invite code / household code
- Can you attend? (Yes/No)
- Number attending
- Dietary restrictions
- Notes

## 🔐 Data safety checklist

- Keep responses in Google Sheets (not in your public GitHub repo)
- Enable 2FA on your Google account
- Restrict Sheet access to only you (or trusted co-host)
- Export CSV backups weekly (daily near RSVP deadline)

## 🎨 Customizing text

Update these in `index.html`:

- Couple names
- Event date/time
- Venue and address
- RSVP deadline
- Parking / logistics notes

---

If you want, I can also add:
- password-protected RSVP page flow
- invite-code validation via Apps Script
- automatic email confirmation after RSVP submission
