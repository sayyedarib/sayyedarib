<h1>Hey, I'm Aarib 👋</h1>

**Software engineer at [telecrm](https://telecrm.in).** I'd rather read the config than guess at it.

I work across the whole stack of a CRM that 2,300+ businesses lean on every day: Angular up front, Node.js and PostgreSQL behind it, AWS underneath, and a mobile app that used to take 23 seconds to open on a budget phone. It takes 12 now. You're welcome, low-end Android users.

```console
$ whoami
aarib — builds it, runs it, and finds out why it broke.

$ cat values.txt
→ Root cause over closed ticket.
→ If I can't measure it, I don't claim it.
→ Agents write the first draft. I read every diff.
→ Leave docs for the next person. I was the next person once, in an undocumented codebase.

$ uptime
 1.5+ years in production, 0 years of pretending I know the answer before reading the logs.
```

<img src="https://komarev.com/ghpvc/?username=sayyedarib&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />

---

### 🧾 Things I've shipped (receipts attached)

| What | Before → After | The short story |
|---|---|---|
| Mobile startup on low-end devices | **23 s → 12 s** | Bundle went from 23 MB to 10 MB. Turns out a phone doesn't need a desktop diagramming library. |
| Role-based access control | **5 modules** redesigned | Everyone used to rebuild the same dashboard for themselves. Now a role gets it once, and everyone in that role has it. |
| Model Context Protocol server | **6 read/write tools** | So LLM apps can work the CRM without asking me. |
| Regression tests | **300+**, gating every release | The robots say "no" before customers get the chance to. |
| Bulk update limit | **10,000 → 50,000** leads | One job doing everything became a master handing batches to workers. |
| Mobile release time | **3-day store review → minutes** | Over-the-air updates. The app stores still get their turn, just less often. |
| Dev database bill | **$500 → $200/month** | Instances that never crossed 20% CPU got politely downsized. |
| Analytics dashboards | **200+** for 40+ clients | One funnel view helped marketing lift campaign reply rates by 20%. |

Also on the list: two-factor auth, crash reporting with Firebase Crashlytics, and first-line support every fourth sprint, where I learned that "it's not working" is a complete bug report if you ask the right three questions.

---

### 🏗️ Side quests

- **[Khan Group of Hostels & PG](https://github.com/sayyedarib/hostel-booking-frontend)**: I built the booking platform for the hostel I was living in. **250+ bookings, ₹2.63L+ in revenue.** The payment gateway allowed one linked account and the owner needed another, so "verification pending" slips were born, and everyone got paid.
- **[Botcraft](https://github.com/sayyedarib/botcraft-frontend)**: A no-code AI assistant builder. Upload a knowledge base, tune the retrieval pipeline live, and embed it with one `<script>` tag. The part I'd defend in a code review: server state and client state never share a room.
- **[Project Alpha](https://github.com/sayyedarib/Alpha)**: Play computer games with your body through webcam pose detection. Gaming that technically counts as exercise. Built at Vercera Hackathon 2024.

---

### 🌱 Open source

- **5 pull requests merged into [Zulip](https://github.com/zulip/zulip/pulls?q=is%3Apr+author%3Asayyedarib+is%3Amerged)**, including a bot check that stops people claiming PRs they aren't assigned to. Yes, I automated saying "no" politely.
- Fixed zulipbot's CI: [zulipbot#231](https://github.com/zulip/zulipbot/pull/231).
- Hacktoberfest contributions across 8+ organizations, including Layer5/Meshery and Ockam. Plus one small Rust fix that I'm unreasonably proud of.

I came for the programs and stayed for the people. Maintainers who took the time to point out my careless mistakes, politely, are why I review newcomers' PRs the same way.

---

### 🔧 Daily drivers

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)

**Workspace:** Neovim · Claude Code (with my own skills and hooks) · kiro-cli · herdr · hunk · Bash on Ubuntu, daily for two years, ever since setting up open-source repos on Windows wore me down.

---

### 📬 Say hi

**Ask me about:** slow PostgreSQL queries, getting your first open-source PR merged, or why your laptop should shut itself down at 10 pm (mine does, with a systemd timer).

[![Portfolio](https://img.shields.io/badge/Portfolio-aarib.me-0e75b6?style=flat)](https://aarib.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/aarib)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=white)](https://leetcode.com/u/Aarib)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:sayyedaribhussain4321@gmail.com)

<sub>P.S. My portfolio has a working terminal. Go ahead, try <code>rm -rf /</code>. There's an undo.</sub>
