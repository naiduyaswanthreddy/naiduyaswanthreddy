<!-- ===================================================== -->
<!--                     HERO SECTION                      -->
<!-- ===================================================== -->

<div align="center">

<h1>Naidu Yaswanth Reddy</h1>

<p>
  <b>
    <span id="typing-text"></span>
  </b>
</p>

<script>
  const roles = [
    "Building real systems, end to end.",
    "Student engineer focused on execution.",
    "Learning by shipping, improving by iteration."
  ];

  let roleIndex = 0;
  let charIndex = 0;
  let deleting = false;
  const speed = 80;

  function typeEffect() {
    const el = document.getElementById("typing-text");
    if (!el) return;

    if (!deleting && charIndex <= roles[roleIndex].length) {
      el.innerText = roles[roleIndex].substring(0, charIndex++);
    } else if (deleting && charIndex >= 0) {
      el.innerText = roles[roleIndex].substring(0, charIndex--);
    }

    if (charIndex === roles[roleIndex].length) deleting = true;
    if (charIndex === 0 && deleting) {
      deleting = false;
      roleIndex = (roleIndex + 1) % roles.length;
    }

    setTimeout(typeEffect, deleting ? speed / 2 : speed);
  }
  typeEffect();
</script>

<br/>

<img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=flat-square&color=444" />

</div>

---

## About Me

I’m a computer science student who prefers **building over talking**.  
I learn by designing systems, shipping features, breaking them under real use, and fixing what matters.

I care about:
- clear ownership  
- pragmatic tradeoffs  
- code that survives scale and failure  

No fluff. Just output.

---

## Tech Stack

<div align="left">

<img src="https://skillicons.dev/icons?i=python,java,cpp,javascript,sql" /><br/>
<img src="https://skillicons.dev/icons?i=react,nodejs,express,fastapi" /><br/>
<img src="https://skillicons.dev/icons?i=mongodb,postgresql,mysql,firebase" /><br/>
<img src="https://skillicons.dev/icons?i=git,github,docker,aws,gcp,linux" />

</div>

---

## GitHub Stats

<div align="left">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=github_dark&hide_border=true" />

<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=github_dark&hide_border=true" />

</div>

---

## Featured Projects

### Project Name
**Problem:** What real-world or technical pain point existed.  
**Solution:** What you built and the key architectural or technical choices.  
**Impact:** What shipped — performance gains, users served, reliability improved.

> Tech: React, Node.js, Database  
> Repo: https://github.com/YOUR_USERNAME/project-name

---

### Project Name
**Problem:** Manual, slow, or error-prone workflow.  
**Solution:** Automated or scalable system with clear ownership.  
**Impact:** Reduced latency, fewer failures, measurable efficiency.

> Tech: Python, FastAPI, MongoDB  
> Repo: https://github.com/YOUR_USERNAME/project-name

---

### Project Name
**Problem:** Needed reliability under concurrency or failure.  
**Solution:** Designed retries, observability, and recovery paths.  
**Impact:** Stable behavior under load and edge cases.

> Tech: Python, Docker, Monitoring  
> Repo: https://github.com/YOUR_USERNAME/project-name

---

## Contact / Links

- GitHub: https://github.com/YOUR_USERNAME  
- LinkedIn: https://linkedin.com/in/YOUR_PROFILE  
- Email: your.email@example.com  

---

<sub>Focused on building. Iterating relentlessly.</sub>
