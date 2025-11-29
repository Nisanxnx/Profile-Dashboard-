# age dekhe nin screenshot 


# profile ss 1

<p align="center">
		<img align="center" alt="PNG" src="https://i.imgur.com/RT2978S.jpeg"/>
<h1 align='center'>

# profile ss 2

<p align="center">
		<img align="center" alt="PNG" src="https://i.imgur.com/29nFPmu.jpeg"/>
<h1 align='center'>

# profile ss 3

<p align="center">
		<img align="center" alt="PNG" src="https://i.imgur.com/6G1iXsC.jpeg"/>
<h1 align='center'>
  
# How to Host Your Website on InfinityFree (Step by Step)

This guide will help you host your profile/portfolio website on InfinityFree for free.  

---

## 1. Prepare Your Website Files
Make sure you have all your files ready in a folder:

- `index.html` (your profile page)
- `style.css` (all styles)
- `projects.html` (if you have a projects page)
- `projects.css`
- `contact.html` (if any, without Formspree if you removed it)
- `contact.css`
- `music.mp3` (if you have background music)
- `images/` folder for all images

**Important:** Keep file names lowercase and paths correct.  

---

## 2. Sign Up on InfinityFree
1. Go to [InfinityFree](https://infinityfree.net)
2. Click **Sign Up** and register using your email (`nisaneditz@gmail.com`).
3. Verify your email.  

---

## 3. Create a Hosting Account
You have two options:

**A. Free Subdomain (Easiest)**  
1. Go to **Client Area → Create Account → Subdomain**  
2. Choose a free subdomain like `yourname.epizy.com`  
3. Click **Create Account**

**B. Custom Domain**  
1. Use your own domain.  
2. Change nameservers to:

ns1.infinityfree.com ns2.infinityfree.com

3. After DNS propagates, go to **Client Area → Create Account → Custom Domain** → enter your domain.  

**Note:** DNS propagation can take 1–24 hours.  

---

## 4. Upload Your Files
InfinityFree provides two ways:

### A. File Manager (Easy)
1. Client Area → Manage Account → Open Control Panel → File Manager
2. Go to `/htdocs` folder
3. Upload all your website files here (`index.html`, `style.css`, etc.)  

### B. FTP (Recommended for large files)
1. Install [FileZilla](https://filezilla-project.org/)
2. Get FTP details from **Client Area → Manage Account → FTP Details**
3. Connect using:

Host: ftpupload.net Username: epiz_xxxxx Password: <your password> Port: 21 Remote Path: /htdocs

4. Upload all your files to `/htdocs`  

**Important:** `/htdocs` is your website root. `index.html` must be directly inside `/htdocs`.

---

## 5. Add SSL (Optional but Recommended)
1. Client Area → Free SSL Certificates
2. Select your domain/subdomain → Generate SSL
3. Follow instructions to install.  

---

## 6. Test Your Website
- Open your subdomain: `https://yourname.epizy.com`
- Check that all pages load properly:
- `index.html` → profile
- `projects.html` → projects
- `contact.html` → contact (without Formspree if removed)
- Background music on profile page should autoplay (browser-dependent).  

---

## 7. Notes & Tips
- InfinityFree limits file size (~10MB per file)
- Background music works best if small and hosted in `/htdocs`
- Modern browsers may block autoplay; profile page music may require first click
- Keep all relative paths correct for CSS, JS, images, and audio
- Use external CDN for large media if needed  

---

## 8. Recommended Folder Structure
/htdocs index.html style.css projects.html projects.css contact.html contact.css music.mp3 /images profile.jpg background.jpg
---

## 9. Common Issues
- **Index page not loading:** make sure it’s `index.html` in `/htdocs`
- **FTP not connecting:** check Client Area FTP credentials
- **Music not autoplaying:** browser may block it, use muted or user interaction workaround
- **SSL not working:** nameservers may not have fully propagated

---

Now your portfolio/profile website is live on InfinityFree! 🚀
