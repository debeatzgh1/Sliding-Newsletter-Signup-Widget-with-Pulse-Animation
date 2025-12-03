<iframe src="https://debeatzgh.wordpress.com/2025/08/18/%f0%9f%9a%80-sliding-newsletter-signup-widget-with-pulse-animation-free-code-demo/" width="100%" height="400" frameborder="0" allowfullscreen></iframe>
<!-- Sliding Newsletter Signup Widget with Pulse Animation -->
<style>
  /* Floating circular button */
  #newsletterBtn {
    position: fixed;
    top: 65%;
    right: 20px;
    background-color: #16a34a;
    color: white;
    border-radius: 50%;
    width: 55px;
    height: 55px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 22px;
    cursor: pointer;
    z-index: 9999;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    transition: background 0.3s ease;
    animation: pulse 2s infinite;
  }
  #newsletterBtn:hover {
    background-color: #0f9a2a;
  }

  /* Pulse animation */
  @keyframes pulse {
    0% { transform: scale(1); box-shadow: 0 0 0 0 rgba(22, 163, 74, 0.7); }
    70% { transform: scale(1.05); box-shadow: 0 0 0 15px rgba(22, 163, 74, 0); }
    100% { transform: scale(1); box-shadow: 0 0 0 0 rgba(22, 163, 74, 0); }
  }

  /* Sliding panel */
  #newsletterPanel {
    position: fixed;
    top: 0;
    right: -420px; /* Hidden off-screen */
    width: 400px;
    max-width: 95%;
    height: 100%;
    background: #fff;
    box-shadow: -4px 0 15px rgba(0,0,0,0.2);
    z-index: 10000;
    display: flex;
    flex-direction: column;
    transition: right 0.4s ease;
  }

  /* Header with close button */
  #panelHeader {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #16a34a;
    color: white;
    padding: 12px;
    font-size: 18px;
  }
  #closePanel {
    background: red;
    border: none;
    color: white;
    font-size: 16px;
    padding: 4px 10px;
    border-radius: 4px;
    cursor: pointer;
  }

  /* Iframe inside panel */
  #newsletterPanel iframe {
    border: none;
    flex: 1;
    width: 100%;
  }

  /* Background overlay */
  #overlay {
    display: none;
    position: fixed;
    top: 0; left: 0;
    width: 100%; height: 100%;
    background: rgba(0,0,0,0.4);
    z-index: 9998;
  }
</style>

<!-- Floating Button -->
<div id="newsletterBtn" title="Subscribe">
  ✉️
</div>

<!-- Overlay -->
<div id="overlay"></div>

<!-- Sliding Panel -->
<div id="newsletterPanel">
  <div id="panelHeader">
    <span>Subscribe for Updates</span>
    <button id="closePanel">X</button>
  </div>
  <iframe src="https://mailchi.mp/dda1a453c7bd/ai-decoder" loading="lazy"></iframe>
</div>

<script>
  const btn = document.getElementById("newsletterBtn");
  const panel = document.getElementById("newsletterPanel");
  const closeBtn = document.getElementById("closePanel");
  const overlay = document.getElementById("overlay");

  btn.addEventListener("click", () => {
    panel.style.right = "0";
    overlay.style.display = "block";
  });

  closeBtn.addEventListener("click", closePanel);
  overlay.addEventListener("click", closePanel);

  function closePanel() {
    panel.style.right = "-420px";
    overlay.style.display = "none";
  }
</script>
<iframe class="BLOG_video_class" allowfullscreen="" youtube-src-id="dIpri8oC1tM" width="320" height="266" src="https://www.youtube.com/embed/dIpri8oC1tM"></iframe>




# Sliding Newsletter Signup Widget with Pulse Animation

🔔 A sleek and modern floating button + sliding panel widget for newsletter subscriptions.  
Built with **HTML, CSS, and JavaScript**.

---

## 📌 Live Preview
👉 [View Demo](https://beatzde4.blogspot.com/p/animation-for-button-fade-slide-in.html)

## 🖼 Thumbnail
![Thumbnail](https://debeatzgh.wordpress.com/wp-content/uploads/2025/08/amodernflat-styleillustrationofanotificationbellwithglowinghighlightssurroundedbyabstractshapespaperenvelopesanddigitalicons28emailmessageupdate293314991682681990671.jpg)

---

## 🚀 Features
- Floating pulse animation button  
- Sliding panel with overlay  
- Mailchimp iframe integration  
- Preloader animation included  

---

## 📂 Setup
1. Clone this repo  
   ```bash
   git clone https://github.com/your-username/sliding-newsletter-widget.git

# 🚀 DeBeatzGH – AI Tools & Side Hustle Hub  

![DeBeatzGH Thumbnail](https://debeatzgh.wordpress.com/wp-content/uploads/2025/08/designamodernminimalisticdesignfeaturinganai-themedicon28likeabraincircuitorrobot29overlaidwithdebeatzghoraitoolshustles6089986211026037047.jpg)  

## 🌟 About  
Welcome to **[DeBeatzGH](https://debeatzgh.wordpress.com/)** — your go-to hub for **AI tools, side hustle strategies, blogging resources, and digital growth guides**.  

Our platform is built to help **students, creators, startups, and professionals** unlock the power of AI, monetize their skills, and thrive in today’s digital economy.  

### ✨ What You’ll Find  
- 💡 Explore **AI prompts, tools, and hacks**  
- 📈 Discover **side hustle strategies & online income ideas**  
- ✍️ Access **blogging & digital business guides**  
- 🚀 Stay ahead with **regular updates and fresh insights**  

---

## 👉 Get Started  
🔥 **Start your journey today → [Visit DeBeatzGH](https://debeatzgh.wordpress.com/)**  

---

<!-- README: DebeatzGH Digital Store (HTML-friendly for GitHub) -->
<div align="center">
  <a href="https://www.socialcreator.com/debeatzgh" target="_blank" rel="noopener">
    <img
      src="https://debeatzgh.wordpress.com/wp-content/uploads/2025/08/designadigitalproductse-commerceonlinedeals3545265155247625100.jpg"
      alt="DebeatzGH Digital Store"
      style="max-width:100%; border-radius:16px;"
    />
  </a>

  <h1 style="margin-top: 14px;">DebeatzGH Digital Store</h1>
  <p style="max-width:780px;">
    Your hub for AI insights, tech tutorials, side-hustle playbooks, and productivity tools.
    Learn, build, and launch digital projects faster.
  </p>

  <!-- CTAs -->
  <p>
    <a href="https://www.socialcreator.com/debeatzgh" target="_blank" rel="noopener"
       style="display:inline-block; padding:10px 16px; margin:4px; border-radius:999px; text-decoration:none; font-weight:600; border:1px solid #2563eb;">
      🚀 View Live App
    </a>
    <a href="https://github.com/debeatzgh1/Personal-Portfolio-site-" target="_blank" rel="noopener"
       style="display:inline-block; padding:10px 16px; margin:4px; border-radius:999px; text-decoration:none; font-weight:600; border:1px solid #111827;">
      ⭐ Star this Repo
    </a>
  </p>
</div>

<hr/>

<h2>Overview</h2>
<p>
  <strong>DebeatzGH</strong> helps beginners and creators build profitable digital assets:
  blogs, affiliate funnels, AI-assisted content, and more. Explore tutorials, tools, and
  ready-to-use components to speed up your workflow.
</p>

<h2>Features</h2>
<ul>
  <li><strong>AI & Tech Learning:</strong> Bite-sized guides for modern tools and workflows.</li>
  <li><strong>Side-Hustle Playbooks:</strong> Practical steps to validate and launch ideas.</li>
  <li><strong>Productivity Toolkit:</strong> Reusable widgets, templates, and scripts.</li>
  <li><strong>Beginner-Friendly:</strong> Clear explanations, curated resources, and examples.</li>
</ul>

<h2>Quick Start</h2>
<ol>
  <li>Clone:
    <pre><code>git clone https://github.com/debeatzgh1/Personal-Portfolio-site-</code></pre>
  </li>
  <li>Enter folder:
    <pre><code>cd debeatzgh</code></pre>
  </li>
  <li>Install deps (adjust to your stack):
    <pre><code># Node
npm install
npm run dev

# or Python
pip install -r requirements.txt
python app.py</code></pre>
  </li>
  <li>Open in browser:
    <pre><code>http://localhost:3000</code></pre>
  </li>
</ol>

<h2>Project Links</h2>
<ul>
  <li>🌐 Live App: <a href="https://www.socialcreator.com/debeatzgh" target="_blank" rel="noopener">socialcreator.com/debeatzgh</a></li>
  <li>🖼️ Thumbnail: <a href="https://debeatzgh.wordpress.com/wp-content/uploads/2025/08/designadigitalproductse-commerceonlinedeals3545265155247625100.jpg" target="_blank" rel="noopener">View image</a></li>
</ul>

<h2>Contributing</h2>
<p>
  Contributions are welcome! Open an issue for bugs or ideas. For changes, fork the repo,
  create a feature branch, and submit a pull request.
</p>

<h2>License</h2>
<p>
  Released under the <a href="./LICENSE">MIT License</a>.
</p>

<hr/>

<div align="center">
  <p><em>If this project helps you, consider giving it a star. It really helps! ⭐</em></p>
  <p>
    <a href="https://www.socialcreator.com/debeatzgh" target="_blank" rel="noopener"
       style="display:inline-block; padding:10px 16px; margin-top:6px; border-radius:10px; text-decoration:none; font-weight:600; border:1px solid #2563eb;">
      Open DebeatzGH Now →
    </a>
  </p>
</div>
