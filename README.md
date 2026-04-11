# 💒 Wedding Invitation — Free Online Invite System

A beautiful, personalised wedding invitation website with guest name import from Excel.
**100% free** — hosted on GitHub Pages, zero ongoing cost.

---

## 📁 Files

| File | Purpose |
|------|---------|
| `index.html` | The invitation page guests will see |
| `admin.html` | Your private admin tool (run locally) |
| `guest_list_template.xlsx` | Download from admin to fill in names |

---

## 🚀 Deploy in 5 Minutes (Free)

### 1. Create GitHub account
Go to [github.com](https://github.com) → Sign up (free)

### 2. Create repository
- Click **New repository**
- Name it: `wedding-invite`
- Set to **Public**
- Click **Create repository**

### 3. Upload files
- Click **Add file → Upload files**
- Upload `index.html`
- Commit changes

### 4. Enable GitHub Pages
- Go to your repo **Settings**
- Scroll to **Pages** section
- Under Source: select **Deploy from branch**
- Branch: `main` / folder: `/ (root)`
- Click **Save**

### 5. Your live URL
After 2–3 minutes:
```
https://YOUR_USERNAME.github.io/wedding-invite/
```

---

## 👥 Generate Guest Links

1. Open `admin.html` in your browser (no server needed, just double-click)
2. Paste your GitHub Pages URL in Step 1
3. Download the Excel template, fill in guest names, save
4. Upload the Excel file
5. Map the name column
6. Click **Generate Invitation Links**
7. Copy links or export CSV / WhatsApp messages
8. Send each guest their unique link!

**Example link:**
```
https://yourname.github.io/wedding-invite/?name=John+Smith
```

The page greets them: *"Dear John Smith,"*

---

## ✏️ Customise the Invitation

Edit `index.html` and change:

| Line | What to change |
|------|---------------|
| `Aiden & Sophia` | Couple names |
| `14 June 2025` | Wedding date |
| `new Date('2025-06-14T16:00:00')` | Date for countdown |
| Venue details in the cards | Your actual venues |
| Google Forms `href` | Your RSVP form link |
| Dress code & table info | Your details |

---

## 📋 RSVP (Free — Google Forms)

1. Go to [forms.google.com](https://forms.google.com)
2. Create a form with fields: Name, Attending (Yes/No), No. of guests, Dietary
3. Click **Send → Link** → copy the link
4. In `index.html`, find `href="https://forms.google.com"` and replace with your form link

---

## 💡 Tips

- **Custom domain**: In GitHub Pages settings, you can add a free custom domain
- **WhatsApp**: Use the admin's "Export for WhatsApp" to get ready-to-paste messages
- **Test first**: Open `index.html?name=Your+Name` locally before going live
- **Privacy**: Keep `admin.html` on your local computer — don't upload it to GitHub

---

## 🆓 Cost Breakdown

| Service | Cost |
|---------|------|
| GitHub Pages hosting | FREE |
| Google Forms (RSVP) | FREE |
| Google Fonts | FREE |
| SheetJS (Excel library) | FREE (open source) |
| Custom domain (optional) | ~$10/year if you want one |

**Total: $0** 🎉

---

*Made with ❤️ for a beautiful wedding day*
