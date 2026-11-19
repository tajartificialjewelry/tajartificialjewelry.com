TAJ ARTIFICIAL JEWELRY - WEBSITE + DASHBOARD FOR GITHUB PAGES
==============================================================
This version works on GitHub Pages. The dashboard saves your changes straight into
your GitHub repository, and GitHub Pages then updates the live website.
No PHP, no server and no database needed.

STEP 1 - UPLOAD THE FILES TO YOUR REPOSITORY
1. Open your repository on github.com.
2. Click "Add file" > "Upload files".
3. Drag ALL the files and folders from this zip (index.html, admin, data, uploads,
   favicon.png, og-image.png, taj-logo.png, robots.txt, sitemap.xml) into the page.
   (Unzip it first on your computer.) Click "Commit changes".
4. Old files with the same names are replaced. You may delete the old "images" folder.
5. Repository Settings > Pages: make sure the source is "Deploy from a branch",
   branch "main", folder "/ (root)". Wait 1 to 2 minutes and open your website.

STEP 2 - CREATE A GITHUB TOKEN (needed only ONE time)
GitHub only lets a dashboard change your files if you give it permission. This is done with a token.
You do it once. After that you log in with your email and password only.
EASIEST WAY: the setup page of the dashboard has a gold button "Open GitHub to create the token".
It opens GitHub with the name, expiry and permission already filled in. You only have to:
1. Under "Repository access" choose "Only select repositories" and pick your website repository.
2. Scroll down and click "Generate token".
3. Copy the long code that starts with github_pat_ (GitHub shows it only once).
(The same page as a link: https://github.com/settings/personal-access-tokens/new?name=Taj%20dashboard&description=Taj%20website%20dashboard&expires_in=366&contents=write )

STEP 3 - FIRST-TIME LOGIN SETUP (one time)
1. Open  https://YOUR-WEBSITE/admin/   (for example https://tajartificialjewelry.com/admin/).
2. You will see "Create your login". Enter your email, the password from your private notepad file
   (login-details.txt, which is NOT part of this website folder), the repository name (optional) and the token.
   The repository name is the last part of your website link on GitHub: github.com/yourname/my-website -> my-website.
   You can leave the repository name empty: the dashboard finds your website repository by itself.
   If it cannot decide, it shows a list and you choose your website repository from it.
   Your GitHub username is found automatically from the token.
3. Click "Create my login". The dashboard opens.

STEP 4 - EVERY DAY
1. Open  https://YOUR-WEBSITE/admin/  and log in with your email and password.
2. Manage everything: Products (with photos, SEO title and description), Slider, Design,
   Reviews, FAQ, Settings, SEO, Policies, Backup.
3. Click "Save changes" (or "Save product" for a new product).
   The dashboard saves to GitHub and your live website updates in about 1 to 2 minutes.
   Photos can take a minute longer to appear.
4. At the bottom right you can "Change password" or "Log out".

IMPORTANT - OPEN THE DASHBOARD WITH https://
The login needs a secure connection. Always open  https://YOUR-WEBSITE/admin/  (with https). If the address starts with http:// the login cannot work and the dashboard will tell you to open the https address.
If you use a custom domain: GitHub > Settings > Pages > tick "Enforce HTTPS" (it can take up to 24 hours after adding the domain until the option works).

RECOVERY CODE (so you can always reset your password)
- First time setup now shows a recovery code once. Write it in your private notepad file.
- If you already have a login: open the dashboard, press "Recovery code" at the bottom right, create the code and write it down.
- Forgot the password? On the login page click "Forgot password? Use my recovery code", enter your email, the recovery code and a new password.
- Lost both the password and the recovery code? Use "I have my GitHub token instead" (make a new token as in Step 2).
- Emailing a code is not possible on GitHub Pages (it has no server to send emails). The recovery code does the same job.

HOW SAVING WORKS
- Choosing photos is instant. The photos and all your changes are sent to GitHub together in ONE step when you press "Save changes" (or "Save product"), so saving is fast.
- After saving, the dashboard shows "Waiting for the website to update..." and then "Live" when your website really shows the change. GitHub itself needs about 1 to 2 minutes to publish; we cannot make that part faster.
- Visitors see your new products as soon as the change is live, even if their browser has an old copy of the page.
- If the message "Live" never comes, open GitHub > Settings > Pages and check that the source is branch "main" and folder "/ (root)".

DASHBOARD LINK
The dashboard is not shown to visitors. There is no public link to it on the website.
A "Dashboard" button appears at the bottom of the website only on a device where you have logged in. Anyone else can only reach it by typing /admin/ and still needs your email and password.

GOOD TO KNOW
- The dashboard page is visible to everyone, but nobody can log in or change anything without your email and password.
- Your GitHub token is saved in the repository only in a locked form (admin/vault.json). Only your password opens it, so keep a LONG, strong password and never share it. Do not choose a short or easy password.
- Do not tick "Keep me logged in" on a shared or public computer. Press "Log out" when finished.
- FORGOT THE PASSWORD? On the login page click "I have my GitHub token instead". Enter your email, a new password and your GitHub token (if you no longer have it, make a new token as in Step 2). Your old password stops working.
- Unpublished drafts are kept only in the browser you used. Always press Save when you finish.
- Download a backup from the Backup tab now and then. GitHub also keeps the full history of every change.
- Keep the repository Public (free GitHub Pages needs a public repository).
- In Dashboard > SEO set "Website address" to your real live address.
- Replace the sample customer reviews (Ayesha, Sana) with real ones or delete them, and edit the Privacy and
  Delivery text to your real policies (Dashboard > Policies).

AFTER GOING LIVE (for Google)
- Create a free Google Search Console account, add your website and submit its sitemap.xml.
- Create a Google Business Profile for your shop in Faisalabad.

URDU MEIN KHULASA
1. Is zip ki saari files apni GitHub repository mein upload (Commit) karein.
2. GitHub se "Fine-grained token" banayein (sirf apni repository, Contents: Read and write) aur copy kar lein. Ye sirf ek dafa chahiye.
3. Apni-website/admin/ kholen, email, password (login-details.txt se), GitHub username, repository ka naam (alag alag boxes mein) aur token dalein. Phir har dafa sirf email aur password se login hoga.
4. Dashboard se badlav karein aur "Save changes" dabayein. 1-2 minute mein website update ho jati hai.
5. Password lamba aur mazboot rakhein aur kisi ko na dein.
