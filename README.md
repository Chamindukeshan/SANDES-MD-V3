<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" style="transform: rotate(180deg);">

<a href="https://11b7b8ad44be8f66.app.lowcloud.co/">
  <img src="https://upld.zone.id/uploads/d4i0x5iq/sandes-md-v2.webp" alt="SANDES MD V3 Logo" width="700px">
</a>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=34&pause=1000&color=1E7BFF,36D4FF,8AA3C7&center=true&vCenter=true&width=900&height=70&lines=⚡+SANDES+MD+V3;🚀+Lightning+Fast+Response;🔒+Secure+%26+Private;🧩+120%2B+Commands;🎛️+Next+Generation+UI" alt="Typing Animation">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-v3.0.0-1E7BFF?style=for-the-badge&logo=semver&logoColor=white">
  <img src="https://img.shields.io/badge/License-MIT-2ECC71?style=for-the-badge&logo=opensourceinitiative&logoColor=white">
  <img src="https://img.shields.io/badge/Node.js-20+-339933?style=for-the-badge&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/Status-Active-FFD700?style=for-the-badge&logo=statuspage&logoColor=black">
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/isurahupa-tech/SANDES-MD-V3?style=for-the-badge&logo=github&color=FFD700">
  <img src="https://img.shields.io/github/forks/isurahupa-tech/SANDES-MD-V3?style=for-the-badge&logo=github&color=36D4FF">
  <img src="https://img.shields.io/github/issues/isurahupa-tech/SANDES-MD-V3?style=for-the-badge&logo=github&color=FF5733">
  <img src="https://img.shields.io/github/contributors/isurahupa-tech/SANDES-MD-V3?style=for-the-badge&logo=github&color=1E7BFF">
</p>

<div align="center" style="margin:30px 0;">
  <p><b>🍴 Fork The Repository</b></p>
  <a href="https://github.com/isurahupa-tech/SANDES-MD-V3" target="_blank">
    <img src="https://img.shields.io/badge/Fork%20Repo-1E7BFF?style=for-the-badge&logo=github&logoColor=white" height="55">
  </a>
</div>

<div align="center">
  <p><b>Pair and Get The Session ID 🔮</b></p>
  <a href="https://11b7b8ad44be8f66.app.lowcloud.co/" target="_blank">
    <img src="https://img.shields.io/badge/Get%20Session-2ECC71?style=for-the-badge&logo=whatsapp&logoColor=white" height="55">
  </a>
</div>

<div align="center" style="display:flex; justify-content:center; flex-wrap:wrap; gap:25px; margin-top:25px;">
  <div style="background:#0A3FBF; color:white; padding:25px; border-radius:20px; width:270px; box-shadow:0px 8px 20px rgba(0,0,0,0.25); font-size:15px; text-align:center;">
    <h3>Lightning Fast ⚡</h3>
    <p>Ultra-fast responses with near-zero delay.</p>
  </div>
  <div style="background:#1E7BFF; color:white; padding:25px; border-radius:20px; width:270px; box-shadow:0px 8px 20px rgba(0,0,0,0.25); font-size:15px; text-align:center;">
    <h3>Secure & Private 🔒</h3>
    <p>Robust privacy features that keep your data to yourself.</p>
  </div>
  <div style="background:#36D4FF; color:#03060F; padding:25px; border-radius:20px; width:270px; box-shadow:0px 8px 20px rgba(0,0,0,0.25); font-size:15px; text-align:center;">
    <h3>Next Generation UI 🎛️</h3>
    <p>Sleek, modern, and easy to use. 120+ commands ready to go.</p>
  </div>
</div>

<div align="center" style="margin-top:40px;">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=28&pause=1000&color=1E7BFF,36D4FF,FFD700,2ECC71&center=true&vCenter=true&width=700&height=50&lines=Deploy+SANDES+MD+V3+Now+🚀;No+Coding+Required+💻;Run+Your+Bot+In+Minutes+⚡&gradient=true" alt="Deploy Banner">
  <br><br>
  <a href="https://dashboard.heroku.com/new?template=https://github.com/isurahupa-tech/SANDES-MD-V3" target="_blank">
    <img src="https://img.shields.io/badge/Deploy%20on%20Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white" height="65">
  </a>
  &nbsp;&nbsp;
  <a href="https://railway.app" target="_blank">
    <img src="https://img.shields.io/badge/Deploy%20on%20Railway-7E22CE?style=for-the-badge&logo=railway&logoColor=white" height="65">
  </a>
  &nbsp;&nbsp;
  <a href="https://replit.com/" target="_blank">
    <img src="https://img.shields.io/badge/Deploy%20on%20Replit-F26207?style=for-the-badge&logo=replit&logoColor=white" height="65">
  </a>
</div>

---

## 📦 Deploy Steps

1. Fork the repository or download the zip.
2. Pair your WhatsApp number and get the session ID from the [pair web](https://11b7b8ad44be8f66.app.lowcloud.co/).
3. Add the workflow below as `.github/workflows/node.yml`, then push to `main`.
4. Check the GitHub Actions tab. A green run means the bot is online.

### GitHub Workflow

```yaml
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main

concurrency:
  group: ${{ github.workflow }}-${{ github.ref }}
  cancel-in-progress: true

jobs:
  build:
    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install --legacy-peer-deps

    - name: Start application
      run: npm start
```

---

🐞 **Found a Bug?**

If you run into a bug or any issue while using this project, please choose one of these options:

- Open an issue on the GitHub repository.
- Contact the maintainer directly on WhatsApp.

<p align="center">
<a href="https://wa.me/94787518010" target="_blank" rel="noopener noreferrer">
<img
alt="Chat on WhatsApp"
src="https://img.shields.io/badge/Chat%20on%20WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"
/>
</a>
</p>

<details>
<summary>🎀 <strong>Special Thanks to</strong></summary>

Thanks to everyone who has supported, inspired, and contributed to this project, directly and indirectly.

**MR.SANDES 🍒**: the lead developer of this project.

</details>

<div align="center">

<a href="https://github.com/sandesissu7-collab">
  <img src="https://upld.zone.id/uploads/d4i0x5iq/sandes-md-v2.webp" width="80px" style="border-radius:50%;" alt="MR.SANDES"/>
  <br />
  <sub><b>MR.SANDES 🍒</b></sub>
</a>

<br><br>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" style="transform: rotate(180deg);">

<p><b>© 2026 SANDES MD V3 | MADE BY MR.SANDES 🍒 | ALL CREDITS GO TO MR.SANDES 🍒</b></p>

</div>
