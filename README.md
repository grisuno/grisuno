# grisun0
is come back: I am a security researcher who secures algorithms against decoherence

hackTheBox: https://app.hackthebox.com/teams/overview/6429

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![image](https://github.com/user-attachments/assets/1b5049b8-3aad-40d1-89eb-642941ff13a1)
 [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Y8Y2Z73AV) [![committers.top badge](https://user-badge.committers.top/chile/grisuno.svg)](https://user-badge.committers.top/chile/grisuno)


![grisUN0](https://github.com/user-attachments/assets/5437120e-7ddc-45e3-9fd6-0163351c3fb2)


> Security researcher who secures algorithms against decoherence.
> The biggest threat isn't adversarial attacks — it's the $10B compute budget that trains models in the wrong phase space.

I work at the intersection of **offensive security**, **post-quantum cryptography**, and **physics-inspired machine learning**. My research treats neural network training as a condensed matter phenomenon — where grokking is a phase transition, not just loss minimization.

📖 **Book:** [A Unified Theory of Hypercomplex Systems](https://doi.org/10.5281/zenodo.20778397) — 11 chapters, 245 trajectories, 5 physical systems under one phase diagram.

---

## 🔬 Research — ML as Condensed Matter

| Project | Description | Chapter | Links |
|---|---|---|---|
| [strass_strassen](https://github.com/grisuno/strass_strassen) | Algorithmic crystallization: κ=1 separates crystal from glass (AUC=1.000, 60 runs). 7K downloads. | Ch 1 | [DOI](https://doi.org/10.5281/zenodo.18072858) |
| [dirac](https://github.com/grisuno/dirac) | Dirac equation as polycrystal — discretization margin, Berry phase | Ch 7 | [DOI](https://doi.org/10.5281/zenodo.18407920) |
| [supertopo3](https://github.com/grisuno/supertopo3) | Cyclotron orbits, ℏ_eff=0.012, topological structure | Ch 3 | — |
| [schrodinger](https://github.com/grisuno/schrodinger) | Schrödinger evolution as supercooled polycrystal | Ch 6 | — |
| [Willmore](https://github.com/grisuno/Willmore) | Willmore energy / RBC as functional glass | Ch 9 | — |
| [TopoGPT3](https://github.com/grisuno/TopoGPT3) | Spectral universality in transformers | Ch 10 | [DOI](https://doi.org/10.5281/zenodo.20388757) |
| [TopoGPT2](https://github.com/grisuno/TopoGPT2) | Complex-valued GPT with topological regularization | Ch 10 | — |
| [liber-monitor](https://github.com/grisuno/liber-monitor) | Real-time δ/κ/T_eff monitoring during training | Tooling | — |
| [Neurothermo](https://github.com/grisuno/Neurothermo) | Production thermodynamic diagnostics for NN training | Tooling | — |
| [QC](https://github.com/grisuno/QC) | Q²C quantum simulator — classical simulation of quantum evolution | Extension | — |
| [HPU-Core](https://github.com/grisuno/HPU-Core) | Hypercomplex Processing Unit protocol | Extension | [DOI](https://doi.org/10.5281/zenodo.18407920) |
| [toposwarm](https://github.com/grisuno/toposwarm) | LazyOwn AI — topological swarm intelligence | Extension | — |

**Key finding:** κ=1 (condition number of gradient covariance) is an order parameter for grokking. Same (δ, κ, T_eff) vocabulary across Strassen, Hamiltonian, Schrödinger, Dirac, and Willmore systems.

---

## 🛡️ Security — LazyOwn C2 Framework

| Project | Role | Stars \| Clones |
|---|---|---|
| [LazyOwn](https://github.com/grisuno/LazyOwn) | Framework hub — install, modules, operations | 213 ⭐ \| 518 |
| [BlackObsidianC2](https://github.com/grisuno/BlackObsidianC2) | C2 server core | 9 ⭐ |
| [BlackBasaltBeacon](https://github.com/grisuno/blacksandbeacon) | Linux beacon (C) | 12 ⭐ |
| [BlackSerpentine](https://github.com/grisuno/BlackSerpentine) | Python nano-implant | 4 ⭐ |
| [BlackZincBeacon](https://github.com/grisuno/BlackZincBeacon) | ARM/Android beacon | 1 ⭐ |
| [ShadowLink](https://github.com/grisuno/ShadowLink) | Fileless delivery via DNS TXT | 7 ⭐ |
| [cgoblin](https://github.com/grisuno/cgoblin) | Go cross-platform loader | 4 ⭐ |
| [keylogger](https://github.com/grisuno/keylogger) | Linux evdev keylogger | 2 ⭐ \| 88 |
| [amsi](https://github.com/grisuno/amsi) | AMSI bypass techniques | 8 ⭐ |
| [CVE-2022-22077](https://github.com/grisuno/CVE-2022-22077) | RTCore64 LPE exploit | 5 ⭐ \| 24 |

**Full ecosystem:** 20+ repos covering C2, beacons (Windows/Linux/ARM), delivery, persistence, evasion, and exploits. See [BlackObsidianC2](https://github.com/grisuno/BlackObsidianC2) for architecture diagram.

---

## 🌐 Privacy & Post-Quantum Infrastructure

| Project | Description | Clones (14d) |
|---|---|---|
| [FreeDom](https://github.com/grisuno/FreeDom) | Post-quantum web browser — C-hardened sandbox, Kyber768/Dilithium3 | **1,453** |
| [QuantumVault](https://github.com/grisuno/QuantumVault) | Post-quantum encrypted vault | 74 |
| [gopher2](https://github.com/grisuno/gopher2) | Alternative protocol — Gopher reborn | 17 |

FreeDom is my most cloned project (40% of all traffic). Security-first browser with post-quantum TLS, custom rendering engine, and memory-safe C sandbox.

---

## 🔍 OSINT & Fraud Detection

| Project | Description | Stars \| Clones |
|---|---|---|
| [estorides](https://github.com/grisuno/estorides) | OSINT framework — 15+ modules, modular architecture | 63 ⭐ \| 202 |
| [ElOjoDeRicci](https://github.com/grisuno/ElOjoDeRicci) | RESMA v1 — GNN with E8 lattice + Ricci flow for fraud detection | 1 ⭐ |
| [lie-detector](https://github.com/grisuno/lie-detector) | RESMA v2 — honest science on fraud detection limits | 2 ⭐ |
| [SWAN-Phoenix-Rising](https://github.com/grisuno/Swan-Phoenix-Rising) | Sparse autoencoder for anomaly detection | 2 ⭐ |

---

## 🐧 Embedded & Kernel

| Project | Description |
|---|---|
| [VSL-DSP](https://github.com/grisuno/VSL-DSP) | Linux kernel driver for DSP hardware |
| [malic](https://github.com/grisuno/malic) | Reverse engineering of Mali GPU driver (mali.ko) |
| [project-nomad](https://github.com/grisuno/project-nomad) | Offline-first server architecture |

---

## 📌 Pinned Repos

> The 6 repos below are pinned on my profile. The tables above are the full map.

`FreeDom` · `LazyOwn` · `estorides` · `strass_strassen` · `TopoGPT3` · `QuantumVault`

---

## 🌐 Socials

[![Discord](https://p.kagi.com/proxy/Discord-%237289DA.svg?c=EgGQfWtq44GRXgvj3b8hBRxPS1jY7cJLKReIaXGSipSEXWiA0nwn3mMKJQMfwLCDpfsoXeb1aLNIcCJ8ZfI-eEF6KEKxxTLg-GKdZ8KRyv_0DIpZjNYkoefQS7ZhNXzi)](https://discord.gg/V3usU8yH)
[![LinkedIn](https://p.kagi.com/proxy/LinkedIn-%230077B5.svg?c=EgGQfWtq44GRXgvj3b8hBddhUvfjMEIFuf2ZlAVxxy4JxsWASG9VussW-ehoIpVjUK1PFnkoN7ef4bejYzdfdspp9yZpDkYiiU0GYfjU6pr87D1nWChO82xmQ0h4hQjJuqrXLfvl-flNkRMcIXhMcA%3D%3D)](https://linkedin.com/in/lazyown)
[![Medium](https://p.kagi.com/proxy/Medium-12100E?c=EgGQfWtq44GRXgvj3b8hBbnxOVIxBPlvGZPtKpVR6T74AfAJnlbh7g3vl3oXD7p2u23dJPstlIg49rI39Ky7yfDuVykZk6BlTsHZzGNHghXOZZLvmPzcNCg9-g5oYsvM)](https://medium.com/@lazyown.redteam)
[![X](https://p.kagi.com/proxy/X-black.svg?c=EgGQfWtq44GRXgvj3b8hBST2chX5CQ51O5c4766soe7YeuuvGO-r9AET1GXfjQAb6UpWliJPKSOc5V38FZZ2ILkH-7a5yjegL3zVivz9Dbo%3D)](https://x.com/lazyown)
[![YouTube](https://p.kagi.com/proxy/YouTube-%23FF0000.svg?c=EgGQfWtq44GRXgvj3b8hBdiE45V644_9MktayniWv9JhnxosLqo3cXhYhU1sZj9X0o6gmv1e_qUwI_gXSAdrwoKlHhtV9fnQoeZCOnAL406oahaDrxuyeyVKU7Ya2sJa)](https://youtube.com/@UCh56TRcWhk6EH38eGiXtISA)

---

## 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=grisuno&theme=dark&include_all_commits=true&count_private=true)
![](https://nirzak-streak-stats.vercel.app/?user=grisuno&theme=dark)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=grisuno&theme=dark&layout=compact)

![](https://github-profile-trophy.vercel.app/?username=grisuno&theme=radical&no-bg=true&margin-w=4)

---

## 💰 Support

[![Patreon](https://p.kagi.com/proxy/Patreon-F96854?c=EgGQfWtq44GRXgvj3b8hBZmP_9qAblqRuZWDeHGED1s6447DozHxBaNwzGkMb1U_zLn97OCeCAImFX2HsE_ApbpN6qxfiNSgSVy8JAR8BBFWucNxMV3Z5eJJMTiyvu_ViOWcz18cuc9lErG6Hr222g%3D%3D)](https://patreon.com/LazyOwn)
[![Ko-fi](https://p.kagi.com/proxy/Ko--fi-F16061?c=EgGQfWtq44GRXgvj3b8hBUoW0AyNuU0a2A749HVXLFQWF_VbBXsB1lUJTyYpT8fmAG0J591A7phlE2s60gLQrbU5iIAfm-N3vRoRSko8CfBsvgJ-vPSjwg6iZ_rp_QnOK3kLsaeKT6d-vbPLJzmaCw%3D%3D)](https://ko-fi.com/grisuno)

[![ko-fi](https://p.kagi.com/proxy/githubbutton_sm.svg?c=P0HkpZ1Gg4BzpTe5S5Aw1zoqMMrPTgp202FiVvO-JB-YlphNB__CctFEXo2g59q5Gs4WFOI74-cwwHTnr98_bA%3D%3D)](https://ko-fi.com/Y8Y2Z73AV)

---

⚔️ [HackTheBox](https://app.hackthebox.com/teams/overview/6429) · 🇨🇱 Chile

clone the repo:
```bash
git clone https://github.com/grisuno/LazyOwn.git
cd LazyOwn
chmod +x install.sh
./install.sh
./fast_run_as_r00t.sh
```
# 💫 About Me: 
- I am a security researcher who secures algorithms against decoherence
- The biggest threat isn’t adversarial attacks, it’s the $10B compute budget that trains models in the wrong phase space.
  
✒️ Writing LazyOwn & Black Basalt Beacon<br>🛡️ Deveop LazyOwnBT<br>☣️ Testing Malware 🧫<br>🔎 I+D OFSEC<br>🐧 Kernel Driver Developer <br>🧠 Bio Inspired model trainer <br>⚛ Quantum Researcher<br>🌈⃤ Physics inspired model trainer.


## 🌐 Socials:
[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.gg/V3usU8yH) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/lazyown) [![Medium](https://img.shields.io/badge/Medium-12100E?logo=medium&logoColor=white)](https://medium.com/@lazyown.redteam) [![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/lazyown) [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=YouTube&logoColor=white)](https://youtube.com/@UCh56TRcWhk6EH38eGiXtISA) 

# 💻 Tech Stack:
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Lua](https://img.shields.io/badge/lua-%232C2D72.svg?style=for-the-badge&logo=lua&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white) ![Perl](https://img.shields.io/badge/perl-%2339457E.svg?style=for-the-badge&logo=perl&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white) ![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white) ![Apache Groovy](https://img.shields.io/badge/Apache%20Groovy-4298B8.svg?style=for-the-badge&logo=Apache+Groovy&logoColor=white) ![AssemblyScript](https://img.shields.io/badge/assembly%20script-%23000000.svg?style=for-the-badge&logo=assemblyscript&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![Ruby](https://img.shields.io/badge/ruby-%23CC342D.svg?style=for-the-badge&logo=ruby&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white) ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-FDEE21?style=for-the-badge&logo=apachespark&logoColor=black) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Phoenix Framework](https://img.shields.io/badge/phoenixframework-%23FD4F00.svg?style=for-the-badge&logo=phoenixframework&logoColor=black) ![Elixir](https://img.shields.io/badge/elixir-%234B275F.svg?style=for-the-badge&logo=elixir&logoColor=white) ![Erlang](https://img.shields.io/badge/Erlang-white.svg?style=for-the-badge&logo=erlang&logoColor=a90533) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white) ![WordPress](https://img.shields.io/badge/WordPress-%23117AC9.svg?style=for-the-badge&logo=WordPress&logoColor=white) ![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white) ![Gunicorn](https://img.shields.io/badge/gunicorn-%298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white) ![AmazonDynamoDB](https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?style=for-the-badge&logo=Amazon%20DynamoDB&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white) ![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![Adobe Audition](https://img.shields.io/badge/Adobe%20Audition-9999FF.svg?style=for-the-badge&logo=Adobe%20Audition&logoColor=white) ![Gimp](https://img.shields.io/badge/Gimp-657D8B?style=for-the-badge&logo=gimp&logoColor=FFFFFF) ![Sketch](https://img.shields.io/badge/Sketch-FFB387?style=for-the-badge&logo=sketch&logoColor=black) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![TravisCI](https://img.shields.io/badge/travis%20ci-%232B2F33.svg?style=for-the-badge&logo=travis&logoColor=white) ![Bitbucket](https://img.shields.io/badge/bitbucket-%230047B3.svg?style=for-the-badge&logo=bitbucket&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![Gitea](https://img.shields.io/badge/Gitea-34495E?style=for-the-badge&logo=gitea&logoColor=5D9425) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white) ![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![Splunk](https://img.shields.io/badge/splunk-%23000000.svg?style=for-the-badge&logo=splunk&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi) ![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white) ![TOR](https://img.shields.io/badge/tor-%237E4798.svg?style=for-the-badge&logo=tor-project&logoColor=white) ![Trello](https://img.shields.io/badge/Trello-%23026AA7.svg?style=for-the-badge&logo=Trello&logoColor=white) ![XFCE](https://img.shields.io/badge/XFCE-%232284F2.svg?style=for-the-badge&logo=xfce&logoColor=white) ![OpenGL](https://img.shields.io/badge/OpenGL-white?logo=OpenGL&style=for-the-badge)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=grisuno&theme=dark&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=grisuno&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=grisuno&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=grisuno&theme=radical&no-frame=false&no-bg=true&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=grisuno&limit=5&theme=dark&combine_all_yearly_contributions=true)

---
[![](https://visitcount.itsvg.in/api?id=grisuno&icon=0&color=0)](https://visitcount.itsvg.in)

  ## 💰 You can help me by Donating
  [![Patreon](https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white)](https://patreon.com/LazyOwn) [![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/grisuno) 

  
<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->

more info comming soon :)


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![image](https://github.com/user-attachments/assets/1b5049b8-3aad-40d1-89eb-642941ff13a1)
 [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Y8Y2Z73AV)




