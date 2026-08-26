# Beta Alpha Psi Website Maintenance Guide

This document contains pre-formatted code snippets for maintaining the chapter website. When updating pages, copy the appropriate block below, update the text/image references, and paste it into the respective `.html` file.

---

## 1. Add a New Officer Card (`officers.html`)

Paste this inside the `<div class="space-y-6">` container in `officers.html`:

\`\`\`html
<div class="bg-white p-6 rounded-lg shadow-sm border border-slate-200 flex items-center gap-6">
    <img src="photo-filename.jpg" alt="Officer Name" class="w-32 h-32 rounded-full object-cover">
    <div>
        <h3 class="text-xl font-bold text-uni-blue">Full Name</h3>
        <p class="text-uni-gold font-semibold">Position Title</p>
        <p class="text-slate-600 text-sm">Short biography text goes here.</p>
    </div>
</div>
\`\`\`

---

## 2. Add a New Partner Card (`partners.html`)

Paste this inside the `<div class="space-y-6">` container in `partners.html`:

\`\`\`html
<div class="bg-white p-6 rounded-lg shadow-sm border border-slate-200 flex items-start gap-6">
    <img src="logo-filename.png" alt="Company Name" class="w-32 h-32 object-contain">
    <div>
        <h3 class="text-xl font-bold text-uni-blue">Company/Firm Name</h3>
        <p class="text-uni-gold font-semibold mb-2">Sponsorship Tier (e.g., Gold Sponsor)</p>
        <p class="text-slate-600 text-sm mb-3">Brief description of the firm and partnership opportunities.</p>
    </div>
</div>
\`\`\`

---

## 3. Standard Navigation Bar (`<nav>`)

If a new page is added to the website, update the `<nav>` block across **all** `.html` files with this standard structure:

\`\`\`html
<nav class="flex justify-between items-center py-4 px-10 bg-uni-blue text-white shadow-lg">
    <div></div> 
    <div class="space-x-8 font-medium">
        <a href="index.html" class="hover:text-uni-gold">Home</a>
        <a href="about.html" class="hover:text-uni-gold">About</a>
        <a href="partners.html" class="hover:text-uni-gold">Professional Partners</a>
        <a href="officers.html" class="hover:text-uni-gold">Officers</a>
        <a href="news.html" class="hover:text-uni-gold">Updates</a>
        <a href="https://forms.cloud.microsoft/Pages/ResponsePage.aspx?id=IX3zmVwL6kORA-FvAvWuz3b-U0qCSDdJm7ptEq2Wx_hUNlZaWUJYVTlRRjlJTDA4T1dMRlA2M1hPRi4u" target="_blank" class="hover:text-uni-gold">Alumni Network</a>
        <a href="apply.html" class="bg-white text-uni-blue px-5 py-2 rounded font-bold hover:bg-slate-100">Apply</a>
    </div>
</nav>
\`\`\`

---

## 4. Best Practices for Media
* **Officer Photos:** Crop images to a square aspect ratio before uploading. Standard format: `jpg` or `png`.
* **Partner Logos:** Prefer transparent `.png` files so logos blend cleanly into card backgrounds.
