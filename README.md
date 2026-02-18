# Anne Schuchman Website

## Files Included:
- index.html (homepage)
- publications.html (publications page)
- writing.html (writing placeholder)
- contact.html (contact form)
- style.css (all styling)
- author-photo.jpg (your Italy photo)

## To Set Up:

### Option 1: GitHub Pages (FREE & EASIEST)
1. Create a GitHub account if you don't have one
2. Create a new repository called `anneschuchman.github.io`
3. Upload all these files to that repository
4. Go to Settings > Pages and enable GitHub Pages
5. Your site will be live at https://anneschuchman.github.io
6. Then point your domain (anneschuchman.com) to GitHub Pages:
   - In Hover, add these DNS records:
     - A record: 185.199.108.153
     - A record: 185.199.109.153
     - A record: 185.199.110.153
     - A record: 185.199.111.153
     - CNAME record: www.anneschuchman.com pointing to anneschuchman.github.io

### Option 2: Netlify (FREE & EASY)
1. Go to netlify.com and sign up
2. Drag and drop this entire folder into Netlify
3. Your site goes live instantly
4. Connect your anneschuchman.com domain in Netlify settings

### Option 3: Traditional Hosting
1. Buy hosting from Bluehost, SiteGround, etc. ($5-10/month)
2. Upload these files via FTP or their file manager
3. Point your domain to their nameservers

## Contact Form Setup:
The contact form uses Formspree (free for 50 submissions/month):
1. Go to formspree.io and sign up
2. Create a new form
3. Copy your form endpoint (looks like: https://formspree.io/f/abc123xyz)
4. In contact.html, replace `YOUR_FORM_ID` with your actual form ID

## Colors Used:
- Mediterranean Blue: #2C5F7C
- Ocean Green: #4A8B8A
- Deep Purple: #6B5B95
- Light Blue: #A8DADC

## To Update:
- Just edit the HTML files in any text editor
- Upload the changed files to wherever you're hosting

Questions? The site is fully functional and ready to go live!