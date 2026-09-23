<h1 align="center">Hi 👋, I'm Ananya T</h1>
<h3 align="center">🚀 Passionate Computer Science Engineer</h3>
<br>
<div align="center">
<p>
  🎓 <b>BE CSE @ JSS College</b>
</p>

<p>
  💡 Exploring AI, Web Dev, and Cloud | Building cool things with code
</p>

<p>
  🌱 Always learning, always growing ☀️
</p>

</div>

---
Today 3:43 PM
proper code to make it correct the alignment is wrong

Yes — the cleanest way is to use a 2-column table, with the GIF on the right and your “About Me” content on the left.

Use this exact code:

<table>
<tr>
<td width="65%" valign="top">

<h3>🧠 About Me:</h3>

<ul>
  <li>🔍 I love solving real-world problems with <b>Data Analysis</b>, <b>AI/ML</b>, and <b>Cloud</b>.</li>
  <li>🤝 Collaborator by nature – I enjoy building and creating with like-minded techies.</li>
  <li>💬 Always open to discussing tech ideas, open-source, or creative hacks.</li>
  <li>🌐 Tech meetups, Hackathons, GSSOC – count me in!</li>
</ul>

</td>

<td width="35%" align="right" valign="top">

<img src="https://github.com/Anu142004/Anu142004/blob/main/coding-function-repeat-eat-sleep-7zxwkklr847mhchm.gif?raw=true" 
     alt="Coding Animation" 
     width="300">

</td>
</tr>
</table>
It will look approximately like:
🧠 About Me:                              ┌──────────────┐
                                         │              │
🔍 I love solving real-world problems   │     GIF      │
   with Data Analysis, AI/ML, and Cloud. │              │
                                         │              │
🤝 Collaborator by nature...             └──────────────┘
                                         
💬 Always open to discussing tech ideas...

🌐 Tech meetups, Hackathons, GSSOC...

Don't use:

<p align="right">

for the GIF in this case, because it makes the GIF a separate block and doesn't give you control over how the text sits beside it. The <table> gives you much better alignment in a GitHub README.

make the table to glow in neon colors and the table should be in the center

GitHub README does not reliably support CSS <style> blocks or CSS animations, so a true animated neon glow around a table may not render. But you can get a centered neon-style table using HTML with colored borders and emoji accents.

Try this:

<div align="center">

<table>
<tr>
<td width="65%" valign="middle">

<h3>🧠 About Me</h3>

<p>🔍 I love solving real-world problems with <b>Data Analysis</b>, <b>AI/ML</b>, and <b>Cloud</b>.</p>

<p>🤝 Collaborator by nature – I enjoy building and creating with like-minded techies.</p>

<p>💬 Always open to discussing tech ideas, open-source, or creative hacks.</p>

<p>🌐 Tech meetups, Hackathons, GSSOC – count me in!</p>

</td>

<td width="35%" align="center" valign="middle">

<img src="https://github.com/Anu142004/Anu142004/blob/main/coding-function-repeat-eat-sleep-7zxwkklr847mhchm.gif?raw=true"
     alt="Coding Animation"
     width="280">

</td>
</tr>
</table>

</div>
For a stronger neon look

You can use a neon-themed heading inside the table:

<h3>💜 🧠 About Me ⚡</h3>

However, if you specifically want cyan/purple neon glowing borders, GitHub Markdown won't reliably render custom CSS like:

box-shadow: 0 0 20px #00ffff;

So the safest GitHub-compatible approach is to create the neon border as an image/SVG and place your content over/around it.

add in the code

Yes. Put the neon styling directly into the code like this. This keeps the whole table centered, the GIF on the right, and gives the table a neon cyan/purple appearance.

<div align="center">

<table style="border: 2px solid #00FFFF; border-radius: 15px; box-shadow: 0 0 15px #00FFFF, 0 0 30px #8A2BE2;">

<tr>

<td width="65%" valign="middle" style="padding: 20px;">

<h3>🧠 About Me:</h3>

<p>
🔍 I love solving real-world problems with 
<b>Data Analysis</b>, <b>AI/ML</b>, and <b>Cloud</b>.
</p>

<p>
🤝 Collaborator by nature – I enjoy building and creating 
with like-minded techies.
</p>

<p>
💬 Always open to discussing tech ideas, open-source, 
or creative hacks.
</p>

<p>
🌐 Tech meetups, Hackathons, GSSOC – count me in!
</p>

</td>

<td width="35%" align="center" valign="middle" style="padding: 15px;">

<img src="https://github.com/Anu142004/Anu142004/blob/main/coding-function-repeat-eat-sleep-7zxwkklr847mhchm.gif?raw=true"
     alt="Coding Animation"
     width="280">

</td>

</tr>

</table>

</div>

Note: GitHub may strip style, box-shadow, and other CSS from README HTML. If that happens, the border/glow won't appear even though the HTML is correct.




---

### 🛠️ Tech Stack:
<p align="center">
  <img src="https://skillicons.dev/icons?i=java,python,aws,vercel,git,github,vscode,html,css,js,sql,mangodb" />
</p>

---

### 🌐 Connect with Me:
<p align="center">
  <a href="https://dev.to/ananya14"><img src="https://skillicons.dev/icons?i=devto" /></a>
  <a href="https://www.linkedin.com/in/ananya-t-52a82524a/"><img src="https://skillicons.dev/icons?i=linkedin" /></a>
  <a href="https://stackoverflow.com/users/25868913"><img src="https://skillicons.dev/icons?i=stackoverflow" /></a>
  <a href="https://www.behance.net/ananyat1"><img src="https://skillicons.dev/icons?i=behance" /></a>
  <a href="https://medium.com/@14ananya.anna"><img src="https://skillicons.dev/icons?i=medium" /></a>
</p>

<p align="center">
  <a href="https://www.codechef.com/users/anu0814"><img src="https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white" /></a>
  <a href="https://www.hackerrank.com/profile/14ananya_anna"><img src="https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white" /></a>
  <a href="https://leetcode.com/u/user8879xw/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=LeetCode&logoColor=black" /></a>
  <a href="https://www.hackerearth.com/@ananyaevara/"><img src="https://img.shields.io/badge/HackerEarth-323754?style=for-the-badge&logo=HackerEarth&logoColor=white" /></a>
</p>

---

### 📈 GitHub Stats:
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Anu142004&show_icons=true&theme=radical" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Anu142004&layout=compact&theme=radical" />
  <br>
  <img src="https://streak-stats.demolab.com?user=Anu142004&theme=dracula&exclude_days=Sun" />
</p>

---

### 🏅 Achievements & Badges:
<details>
  <summary>🏆 Holopin Badges</summary>
  <a href="https://holopin.io/@anu142004">
    <img src="https://holopin.me/anu142004" alt="Holopin Badges" />
  </a>
</details>

<details>
  <summary>🛡️ TryHackMe Badge</summary>
  <img src="https://tryhackme-badges.s3.amazonaws.com/14ananyaanna08.png" alt="TryHackMe Badge" />
</details>

<details>
  <summary>🪶 GSSOC 2024 Badges</summary>
  <div align="center">
    <img src="https://raw.githubusercontent.com/GSSoC24/Postman-Challenge/main/docs/assets/Postman%20White.png" width="100px" />
    <img src="https://raw.githubusercontent.com/GSSoC24/Hack-Web3Conf/refs/heads/main/assets/Hack-Web3Conf%202024%20Badge%20(2).png" width="100px" />
    <img src="https://raw.githubusercontent.com/GSSoC24/Postman-Challenge/main/docs/assets/1.png" width="100px" />
    <img src="https://raw.githubusercontent.com/GSSoC24/Postman-Challenge/main/docs/assets/2.png" width="100px" />
    <img src="https://raw.githubusercontent.com/GSSoC24/Postman-Challenge/main/docs/assets/3.png" width="100px" />
    <img src="https://raw.githubusercontent.com/GSSoC24/Postman-Challenge/main/docs/assets/4.png" width="100px" />
    <img src="https://raw.githubusercontent.com/GSSoC24/Postman-Challenge/main/docs/assets/5.png" width="100px" />
  </div>
</details>

---
