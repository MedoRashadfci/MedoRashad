# Cybersecurity Engineering Portfolio Blueprint

Welcome to your new professional Cybersecurity Portfolio! This template is designed specifically for cybersecurity professionals, penetration testers, and security analysts to showcase their skills, labs, and certifications cleanly and interactively.

## 📁 File Structure

```text
cybersec-portfolio/
│
├── index.html            # Main HTML file (Content and Structure)
├── css/
│   └── style.css         # Styling, dark theme, and animations
├── js/
│   └── script.js         # Interactivity (navbar, smooth scroll, mobile menu)
├── assets/
│   ├── images/           # Place your profile picture here
│   └── certificates/     # Place your certification badge graphics here
└── README.md             # This instruction file
```

## 🛠️ How to Customize

Follow these simple steps before uploading to GitHub Pages or your web host:

### 1. Update Personal Information (`index.html`)

Open `index.html` in an editor. Press `Ctrl + F` (or `Cmd + F`) and search for `[` or `[Your Name]` to find placeholder text easily.

* **`<title>` & Logo**: Change `[Your Name]` in `<title>` and `<div class="logo">` strings.
* **Hero Section**: Update the `<h1>` glitch text and the paragraph below it. Update the resume download link `<a href="assets/[Your_CV.pdf]">`.
* **About Me**: Update the text paragraph with your personal story. Modify the terminal box (`visitor@sys:~$ whoami`) location and education.
* **Social Links**: At the bottom of `index.html` (Contact section), replace `[Your LinkedIn URL]`, `[Your GitHub URL]`, etc., with your actual profile links. 
* **Contact Email**: Update `mailto:[Your_Email@protonmail.com]`.

### 2. Update Assets & Images

* **Profile Picture**: Put your picture in `assets/images/` and name it `profile-placeholder.jpg` OR update the `<img id="profile-pic" src="...">` path in `index.html`.
* **Resume/CV**: Place your PDF resume in the `assets/` folder and update the link in the Hero section.
* **Certifications**: Save your digital badges to `assets/certificates/` and update the `src` attribute for the certificate images in the `Certifications` section.

### 3. Customize Content

* **Skills**: Edit the `<ul>` and `<span class="tag">` elements under the Core Competencies section to match your exact toolset and expertise.
* **Projects / Writeups**: The Projects section includes 3 sample projects. Replace "Active Directory Lab", descriptions, and tool lists. Ensure you put the correct `[GitHub Repo URL]` in the anchor tags `<a href="...">`.
* **Experience**: Update the Timeline format with your own job history, titles, and bullet points.

### 4. PGP Key (Optional)

In the `index.html` contact section, there is a placeholder `<pre>` tag for a PGP Public Key. If you allow encrypted communications, paste your public key block there. If not, simply delete the `<div class="pgp-block">` block.

## 🚀 Deployment (GitHub Pages)

This template requires zero build steps because it's built with pure Vanilla HTML/CSS/JS.

1. Create a new repository on GitHub named `your-username.github.io`.
2. Upload these files directly to the root of that repository.
3. Your site will go live at `https://your-username.github.io`.

## 🎨 Design Guide & Adjustments (`css/style.css`)

If you want to change the color scheme, edit the CSS variables at the very top of `css/style.css`:

```css
:root {
    --accent-green: #00ff88;  /* Change to desired primary color */
    --accent-blue: #00b8ff;   /* Change to desired secondary color */
}
```

Good luck on the job hunt! Stay secure. 🚀
