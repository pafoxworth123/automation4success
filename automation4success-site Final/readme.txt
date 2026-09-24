====================================
Automation4Success — Deployment Guide
====================================

This folder contains your complete website files:
- index.html
- style.css
- favicon.ico
- /images/
- README.txt

------------------------------------
🚀 Option 1: Quick Upload via Netlify
------------------------------------
1. Go to: https://app.netlify.com/drop
2. Drag and drop the *contents* of this folder (not the ZIP itself) into the window.
3. Netlify will automatically deploy your site and give you a live URL like:
   https://automation4success.netlify.app

4. To connect your custom domain:
   - Go to your Netlify dashboard.
   - Click "Site Settings" → "Domain Management" → "Add custom domain".
   - Enter: automation4success.com
   - Follow Netlify’s instructions to verify via DNS.

5. In Cloudflare DNS:
   Create a CNAME record:
     Name: automation4success.com
     Target: automation4success.netlify.app
     Proxy: DNS Only (gray cloud)

6. After propagation, your domain will show your Netlify site automatically.
   HTTPS is handled automatically by Netlify with Let's Encrypt.


---------------------------------------------
🌐 Option 2: Deploy via Cloudflare Pages
---------------------------------------------
1. Go to: https://dash.cloudflare.com
2. On the left menu, click **"Workers & Pages"** → **"Create a new Project"**.
3. Choose **"Upload Assets"** (not "Connect to Git").
4. Drag and drop the *contents* of this folder.

5. When prompted for project name:
   Use: automation4success

6. After upload, Cloudflare will create a subdomain:
   https://automation4success.pages.dev

7. To connect your custom domain:
   - Go to **"Custom Domains"** tab inside your Cloudflare Pages project.
   - Click **"Set up a custom domain"** → enter `automation4success.com`.
   - Cloudflare automatically adds or suggests the DNS records.
   - If not, manually add a **CNAME** record:
       Name: automation4success.com
       Target: automation4success.pages.dev
       Proxy: Proxied (orange cloud ON)

8. Wait a few minutes for DNS propagation.
   You’ll get automatic HTTPS and a valid SSL certificate.

------------------------------------
📧 Support Info
------------------------------------
Business name: Automation4Success
Email: info@automation4success.com
Phone: (972) 850-8399
URL: https://automation4success.com
