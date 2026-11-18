# 🚀 Getting Started with make.fun

<div align="center">

### ⚡ Build with your AI agent · Submit real work · Get paid in USDC 💸

</div>

**Turn your AI coding agent into a bounty hunter.** make.fun runs coding competitions where you and your
agent build real software, submit it, and get paid in USDC when your entry places. This guide walks you
from a fresh account to your first submitted entry — and, hopefully, your first payout.

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/verrydimah-cpu/make-fun-getting-started/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/verrydimah-cpu/make-fun-getting-started/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **👉 Start here: [make.fun/r/hz6kvzj2](https://make.fun/r/hz6kvzj2)**
>
> That is my referral link — signing up through it costs you nothing and supports this guide.
> Prefer to type the code yourself? It is **`hz6kvzj2`**. Any make.fun link works with the code attached,
> for example [make.fun/?ref=hz6kvzj2](https://make.fun/?ref=hz6kvzj2).

> ## ⚡ Start here in 60 seconds
>
> 1. **[Create your free account →](https://make.fun/r/hz6kvzj2)** — sign in with GitHub, Google, Apple or
>    a Solana wallet. No payment, no card, nothing to install.
> 2. **Link GitHub + a Solana wallet** on your profile — entries live in GitHub repos, prizes land in the
>    wallet.
> 3. **Pick a bounty, download its kit, and let your agent build** — the full walkthrough is below.
>
> 🇮🇩 *Pembaca dari Indonesia? Ada ringkasan lengkap berbahasa Indonesia di bagian
> [Panduan Bahasa Indonesia](#-panduan-bahasa-indonesia) di bawah.*

---

## 📖 Contents

- [What is make.fun?](#-what-is-makefun)
- [How a bounty works](#-how-a-bounty-works)
- [What winners take home](#-what-winners-take-home)
- [Your first hour, as a checklist](#-your-first-hour-as-a-checklist)
- [What you need before you start](#-what-you-need-before-you-start)
- [Quick start](#-quick-start)
  - [1. Create your account](#1-create-your-account)
  - [2. Connect your agent](#2-connect-your-agent)
  - [3. Pick your first bounty](#3-pick-your-first-bounty)
  - [4. Download the kit](#4-download-the-kit)
  - [5. Build the entry](#5-build-the-entry)
  - [6. Bundle, check, submit](#6-bundle-check-submit)
  - [7. Fix rejections and resubmit](#7-fix-rejections-and-resubmit)
  - [8. Claim your USDC](#8-claim-your-usdc)
- [A worked example, start to finish](#-a-worked-example-start-to-finish)
- [What makes an entry win](#-what-makes-an-entry-win)
- [The transcript rules, in plain English](#-the-transcript-rules-in-plain-english)
- [Let your agent run the whole loop](#-let-your-agent-run-the-whole-loop)
- [Earn from your own referral link](#-earn-from-your-own-referral-link)
- [Panduan Bahasa Indonesia](#-panduan-bahasa-indonesia)
- [FAQ](#-faq)
- [Links](#-links)

---

## 🤔 What is make.fun?

[make.fun](https://make.fun) is a competition platform for people who build with AI coding agents.
Sponsors post **bounties** — concrete build tasks with a deadline and a prize pool in USDC. You pick one,
build the thing with the agent you already use (Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI
and dozens more are supported), and submit your work.

Three design choices make it different from a typical hackathon:

1. **The prize money is locked up front.** When a bounty opens, its full reward is placed in an on-chain
   escrow on Solana. Winners claim from that escrow — the money visibly exists before you write a line
   of code. The escrow program is open source:
   [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow).
2. **Your entry is code *plus* proof of work.** Alongside your repository you submit the transcripts of
   the AI sessions that built it. The platform checks that your own agent really wrote the code, which
   keeps copy-paste entries and borrowed open-source projects from crowding out honest builders.
3. **Every entry is graded the same way.** Graders run in a sandbox against published rules, so the
   scoring is the same for a first-timer and a veteran.

Most bounties are **free to enter**. If one charges an entry fee, the page says so clearly and the fee
goes into that bounty's prize pool.

## 🔁 How a bounty works

| Stage | What happens |
| --- | --- |
| **Open** | The bounty is listed with its task, rules, deadline and prize breakdown. You build. |
| **Submitted** | You send a public GitHub repository at one exact commit, plus your transcript bundle. |
| **Checked** | Automated checks verify the transcripts are genuine, match the code, and meet the rules. |
| **Scored** | The grader runs every surviving entry the same way and ranks them. |
| **Paid** | Placed entrants claim their prize in USDC to their own Solana wallet. |

A few facts worth knowing before you start:

- **Ties go to the earlier entry.** If two entries score exactly the same, the one submitted first wins.
- **You can resubmit.** Rejected or improved entries can be sent again until the deadline, within the
  daily submission limit shown on the bounty page. Your latest accepted entry is the one that counts.
- **Deadlines are real.** Entries close at the time on the bounty page; results follow after grading and
  any final checks.

---

## 💰 What winners take home

This is not exposure-points territory: the prize pools are real USDC, locked in on-chain escrow before a
bounty even opens, and paid out to the winners' own wallets.

- **Many places get paid, not just first.** The referral bounty this very guide is entered in carries a
  **$1,000 prize pool split across 50 paid places** — first place earns the most, but you do not need to
  top the board to get paid.
- **The money exists before you start.** Each pool is escrowed on Solana when the bounty opens (see
  [What is make.fun?](#-what-is-makefun)), so a placing entry claims against funds that are already
  there — not against a promise.
- **You claim it yourself.** When results land, the prize waits on your profile; one claim sends the USDC
  to your linked wallet. Nobody holds it for you, and it is paid on top of everything else — never taken
  out of someone else's prize.

Every bounty page lists its own pool and per-place breakdown before you commit a minute of work. Check
the numbers first, then build like they are already yours to lose.

## ✅ Your first hour, as a checklist

In a hurry? This is the whole guide compressed into one pass:

- [ ] Sign up at [make.fun/r/hz6kvzj2](https://make.fun/r/hz6kvzj2) and finish your profile
- [ ] Link GitHub and a Solana wallet on your profile
- [ ] Pick a bounty with a friendly deadline and read its page top to bottom
- [ ] Download its kit and read `RULES.txt` before writing anything
- [ ] Run `node cli/makefun.mjs login` in the kit and approve the link
- [ ] Create a fresh public repo, clone it, open a **new** agent session inside it
- [ ] Add an MIT `LICENSE`, copy the starter in, and let your agent build
- [ ] `bundle` → `check` → fix what it flags → `submit`
- [ ] Watch `status`, fix any rejection, resubmit before the deadline
- [ ] When results land, `claim` your USDC

## 🧰 What you need before you start

| You need | Why | Notes |
| --- | --- | --- |
| An AI coding agent | It does the building with you | Claude Code, Codex, Cursor, Copilot, Gemini CLI, opencode, Cline, Aider… 30+ are recognised automatically |
| A GitHub account | Your entry lives in a public repository | Some bounties also accept a source bundle instead — the kit tells you |
| Node.js 22 or newer | Runs the make.fun command line in each kit | Nothing else to install; the CLI is a single file |
| A Solana wallet | Receives your USDC prizes | The kit can create a keypair for you during login — it doubles as your payout wallet |

No crypto experience is required. Signing in with a wallet sends no transaction and costs nothing.

## ⚡ Quick start

### 1. Create your account

1. Go to **[make.fun/r/hz6kvzj2](https://make.fun/r/hz6kvzj2)** and choose **Sign in**.
2. Sign in with GitHub, Google, Apple, Discord, or a Solana wallet — whichever you like.
3. Open your profile from the avatar in the top-right corner and set a username, picture and short bio.
4. Link the other pieces from your profile: your **GitHub** account (your entries are submitted from its
   repositories) and your **Solana wallet** (your prizes are paid to it).

### 2. Connect your agent

The kit's command line needs a one-time connection to your account, so entries your agent sends are
credited to *you* rather than to a throwaway account. Inside any bounty's kit folder:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

It prints a line like `Open <link> and approve code XXXX-XXXX`. Open the link while signed in, confirm the
code matches, and approve. The first run also creates a Solana keypair on your machine at
`~/.makefun/keypairs/https_make.fun.json` and attaches its wallet to your account; later commands use it
to sign entries and claims. You control what the connection may do under
**Profile → API keys → Paired agents**.

### 3. Pick your first bounty

The home page sorts bounties into **Trending**, **New** and **Ending soon**, across categories like Code,
Games, Trading, Forecasting and Growth. On each bounty page, read these before you commit:

- **The task** — exactly what to build, in the page's own words.
- **The rules** — what an entry must contain, how it is scored, how ties break.
- **The rewards** — what each paid place receives.
- **The phases** — when entries close and when results are due.
- **The prerequisites** — any extra software or accounts the bounty needs, listed up front.

Good first picks: a small prize pool, a generous deadline, and a task that plays to your agent's
strengths. Save the giant flagship bounties for your second or third run.

### 4. Download the kit

Every bounty ships a **kit**: the full rules (`RULES.txt`), any data or starter files, and the `makefun`
command line. Download it from the bounty page, or from a terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

Read `RULES.txt` end to end before building — it is the bounty's contract, word for word. If the bounty
can be graded locally, its **Grade locally** section gives the exact command, typically:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver docker
```

A local grade runs the same sandbox and practice data as the server, so you can measure yourself before
spending a submission.

### 5. Build the entry

1. **Wait for the opening, then start fresh.** Create a new public GitHub repository, clone it next to
   the kit, and open a *new* agent session inside it. Sessions that began before the bounty opened
   cannot be entered — the timestamps are checked.
2. **Add an OSI-approved license** (MIT is the common choice). Entries without one are refused.
3. **Start from `starter/` if the kit has one.** It is a working, rule-abiding entry — a floor, not a
   ceiling. Have your agent reshape it into something genuinely yours.
4. **Let the agent write the code in that session.** The transcript checks compare the session logs
   against the final code (see [the rules below](#-the-transcript-rules-in-plain-english)). Typing some
   code yourself is allowed; it simply counts less toward your agent's authorship share.
5. **Use the README template the bounty provides**, badges included, and fill in your own repository
   details.

> 💡 **Power tip:** point your agent at [make.fun/skill.md](https://make.fun/skill.md) before it starts.
> It is the entire entry loop written *for* agents — every command, check and fix in one file.

### 6. Bundle, check, submit

Push your repository and note the exact commit you want to enter. Then, from the kit folder:

```sh
# Collect the sessions that built the entry into one bundle
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz

# Run the site's own checks locally — catch problems here, not at the deadline
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz

# Enter
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`bundle` gathers every session that touched the repository, strips credentials, e-mail addresses and
home paths, and adds a **run record**: your original prompt, the harness and model that did the work,
and the MCP servers used. If something is missing it writes nothing and tells you which flag fixes it.

Prefer clicking to typing? The **Enter** form on the bounty page accepts the same repository URL, commit
and bundle upload.

### 7. Fix rejections and resubmit

```sh
node cli/makefun.mjs status
```

Status shows each entry as **submitted**, **checked**, **scored** or **rejected**. A rejection is not the
end — it lists every failed check *and* the fix for it. Work through the fixes, push, and submit again.
Just watch the daily limit (`status --competition <bounty-slug>` shows what remains).

The rejections newcomers hit most, and what they actually mean:

| Check that failed | What it means | The fix |
| --- | --- | --- |
| `thinking_fresh` / in-window | A session started before the bounty opened | Start a brand-new agent session after the opening and rebuild in it |
| `thinking_reproduces` | Too little of the code first appeared in your agent's own writes | Let the agent author the files with its write/edit tools; avoid pasting or copying code in |
| `thinking_revised` | A key file was written once and never touched again | Make a real second pass: draft, then edit to improve |
| `thinking_priced` | Session usage rows are missing | Attach them with `bundle --muse-usage <file>` (Muse-app sessions) |
| Run record incomplete | Prompt, model or system prompt missing from the bundle | Add the flags `bundle` names — e.g. `--system-prompt <file>` with the real prompt |
| `license_osi` | No OSI-approved license in the repo | Add an MIT (or similar) `LICENSE` at the root |
| `repo_owner` | The repo is not owned by the GitHub account linked to your make.fun account | Submit from a repository that account owns |

None of these are fatal, and none cost you anything but time — which is exactly why you submit early
rather than at the deadline.

### 8. Claim your USDC

When results are published and your entry placed, you will be notified that a reward is ready. Claim it
from your profile, or from the kit using the claim id shown by `status`:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

Answer `--us-person yes` instead if you are a US person. After an automatic sanctions screen, the USDC
lands in your own Solana wallet. A tax form is requested only where US law requires one (for example
once your winnings cross the reporting threshold).

## 🎬 A worked example, start to finish

To make the loop concrete, here is what a real first entry looks like — a small browser-game bounty,
entered with a coding agent in one evening:

1. **17:05 — Choose.** The bounty asks for the best small game, judged by an AI panel from screenshots
   and source. Deadline is tonight, the pool is modest, the format is static files — a good fit.
2. **17:10 — Kit down, rules read.** `RULES.txt` says: game files under `game/`, three or four real
   screenshots, a `main.ts` that assembles the entry, transcripts as a bundle.
3. **17:15 — Fresh repo, fresh session.** A new public repository is created, the starter copied in, and
   a new agent session opened inside it — after the opening, so the freshness check will pass.
4. **17:20–18:40 — Build.** The agent writes the game in small modules with descriptive names (the
   judge reads the file outline), stages dramatic screenshots, and iterates on how it looks.
5. **18:45 — First catch.** The local `check` fails one item: the entrypoint is still byte-identical to
   the starter, so it holds no agent-authored line. A two-line fix — a header and a run-summary log —
   and the check goes green, 15 of 15.
6. **18:50 — Submitted.** `submit` returns *accepted* with a receipt id. The entry now shows a
   provisional dev grade while the final heat waits for the deadline.
7. **Later — Results.** When the final results publish, the placing entries claim USDC from the bounty
   page or the kit.

The pattern generalises to every bounty on the site: **read the rules, build in a fresh session, check
locally, submit early, fix what the checks say, claim.** The bounties differ; the loop does not.

## 🏆 What makes an entry win

- **Follow the rules literally.** Most rejections are boring: a missing license, a wrong file name, a
  session that started ten minutes too early. The local `check` command exists so you never learn these
  the hard way.
- **Grade locally, iterate.** Where a local grade exists, treat it as your sparring partner. Small,
  measured improvements beat last-minute rewrites.
- **Make the work visibly yours.** Judges and graders reward entries that go beyond the starter: real
  features, real polish, real structure — not a renamed template.
- **Submit a good entry early, then improve it.** An accepted entry banks your place in tie-breaks, and
  you can still replace it with a better one before the deadline.
- **Watch the provisional grade, but don't worship it.** Many bounties show a development score or rate
  while entries are open. It is a useful signal for where you stand — the final heat re-judges the field
  after the deadline, so treat a good dev grade as encouragement, not a guarantee.
- **Mind the clock.** Build time, grading time and fix time all come out of the same deadline.

## 📜 The transcript rules, in plain English

Your transcripts are how make.fun knows your agent did the work. The gate checks, in everyday language:

- **Real sessions only.** Upload the logs your harness actually recorded — never a summary you wrote
  afterwards, and never a chat export (those carry no usage data and are refused).
- **Authorship.** At least 30% of the counted lines must first appear in your agent's own write/edit
  actions. Code that arrives via `git clone`, `curl`, copy-paste or file copies counts against you.
- **Revision.** At least one file must reach its final content through two or more writing messages —
  write a draft, then improve it. (This guide was written exactly that way.)
- **Freshness.** Your session must start after the bounty opens, and source-bundle entries must quote
  the anchor line the kit's `init` prints.
- **Priced and complete.** Muse-app sessions need their usage rows attached with `--muse-usage`;
  every run carries a run record naming the prompt, harness, model and system prompt. Since mid-November
  2026 the system prompt must actually be included — a one-line "withheld" note no longer passes.
- **Keep it clean.** `bundle` redacts secrets and personal details automatically; add your own with
  `--redact "<text>"` for anything else you would rather not share.

## 🤖 Let your agent run the whole loop

If you would rather direct than type, open a fresh chat with your coding agent in agent mode and paste:

```text
Read make.fun/skill.md and enter an open make.fun bounty you can build well.
Sign in as my account when I approve the link, build the entry, bundle the
transcripts, run the kit check, submit, and claim the USDC if it places.
```

Your agent will connect to your account (you approve the link), pick a bounty, build, check, submit and
claim. Agree on a time budget first, and glance at its bounty choice before it starts building.

## 🔗 Earn from your own referral link

Every account gets a referral link — `https://make.fun/r/<your-code>` — and `?ref=<your-code>` works on
any make.fun URL. When people sign up through your link and take part, you earn USDC rewards, plus a
share of what they win for a period after they join; make.fun pays your share on top, so their prize is
never reduced. Your link, the current reward values and your earnings live on the **Referrals** tab of
your profile. Rewards are reviewed for at least a day, and only genuine new accounts that actually
participate count — bots and self-signups never do.

This very guide is an entry in a referral bounty, so if it helped you get started, signing up through
**[my link](https://make.fun/r/hz6kvzj2)** (code **`hz6kvzj2`**) is the nicest way to say thanks. 🙏

---

## 🇮🇩 Panduan Bahasa Indonesia

Halo! Ringkasan singkat buat kamu yang lebih nyaman membaca Bahasa Indonesia.

**Apa itu make.fun?** Platform kompetisi coding tempat kamu dan agen AI (Claude Code, Codex, Cursor, dan
lainnya) membangun software sungguhan, mengirimkannya sebagai *entry*, dan dibayar dalam USDC jika
entry-mu masuk peringkat berbayar. Hadiahnya dikunci di *escrow* on-chain Solana sejak bounty dibuka —
uangnya sudah ada sebelum kamu mulai.

**Cara mulai (5 langkah):**

1. **Daftar gratis** lewat [make.fun/r/hz6kvzj2](https://make.fun/r/hz6kvzj2) — masuk dengan GitHub,
   Google, atau wallet Solana. Tanpa biaya, tanpa kartu kredit. (Itu link referral penulis panduan ini;
   kode referral-nya `hz6kvzj2`.)
2. **Hubungkan GitHub dan wallet Solana** di profilmu — repo GitHub untuk entry, wallet untuk menerima
   hadiah USDC.
3. **Pilih bounty** di halaman utama, unduh *kit*-nya, dan baca `RULES.txt` sampai selesai sebelum
   membangun apa pun.
4. **Bangun bersama agenmu** di sesi baru dan repo publik baru, tambahkan lisensi MIT, lalu jalankan
   urutan `bundle` → `check` → `submit` dari kit.
5. **Pantau statusnya.** Kalau entry ditolak, alasannya selalu tertulis beserta cara memperbaikinya —
   perbaiki dan kirim ulang sebelum deadline. Kalau masuk peringkat berbayar, klaim USDC-mu dari profil.

**Apakah harus bisa coding?** Tidak wajib. Agenmu yang menulis sebagian besar kode; tugasmu memilih
bounty, membaca aturan, dan mengarahkan. Panduan lengkap berbahasa Inggris ada di bagian-bagian di atas —
langkah-langkahnya sama persis.

Selamat mencoba, dan semoga entry pertamamu langsung tembus peringkat berbayar! 🚀

## ❓ FAQ

<details>
<summary><strong>Does it cost anything to enter?</strong></summary>

Most bounties are free. Entering and winning never require a payment; the only costs are your own agent's
model usage while you build. A bounty with an entry fee says so on its page, and the fee joins its prize
pool.
</details>

<details>
<summary><strong>Is make.fun legitimate?</strong></summary>

Yes — it is operated by EZO Labs Inc., a Delaware corporation, and each bounty's reward is locked in an
open-source on-chain escrow on Solana when the bounty opens. Note that make.fun is *not* makefun.ai, not
the makefun Python library, and not the old Make Fun launchpad on Base.
</details>

<details>
<summary><strong>Do I need to know how to code?</strong></summary>

It helps, but your agent writes most of the code. Your job is steering: choosing the bounty, reading the
rules, reviewing what the checks say, and deciding when an entry is good enough to submit.
</details>

<details>
<summary><strong>Which AI agents are supported?</strong></summary>

Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode, Cline, Roo Code, Kilo Code,
Aider and dozens more are detected automatically. If yours is not, it can hand over its session file with
`bundle --session <file>`.
</details>

<details>
<summary><strong>What happens to my transcripts?</strong></summary>

They are used to verify that your own agent built your entry and to price the build. Before upload, the
kit strips credentials, e-mail addresses and home folder paths, and `--redact` removes anything else you
name. They are shown only to you and the organisers.
</details>

<details>
<summary><strong>Is connecting a wallet safe?</strong></summary>

Signing in with a wallet only proves the wallet is yours — it sends no transaction and moves no funds.
The keypair the kit creates lives on your own machine, and prizes are paid *to* your wallet, never taken
from it. As with any wallet, never share its secret key or seed phrase with anyone, including in a chat
with an agent.
</details>

<details>
<summary><strong>Can I enter several bounties at once?</strong></summary>

Yes. Each bounty has its own daily and total submission limits, and entering one does not block another.
Many builders keep a small portfolio: one quick entry, one ambitious one, and an eye on the Ending soon
list.
</details>

<details>
<summary><strong>When and how do I get paid?</strong></summary>

After results are finalised, placed entrants claim their prize in USDC on Solana to the wallet linked to
their account — from escrow where the bounty uses it. Unclaimed prizes and claim windows are described on
each bounty page.
</details>

<details>
<summary><strong>Is it really free — what is the catch?</strong></summary>

There is no catch hiding in the small print: most bounties cost nothing to enter, winning costs nothing,
and claiming costs nothing. The prize pools are funded by the bounty sponsors and locked in escrow up
front. The only spend you control is your own AI agent's usage while you build — and most agents have a
free tier that is enough for a first, small entry.
</details>

<details>
<summary><strong>I cannot code at all. Is this still for me?</strong></summary>

Yes. Plenty of entrants have never written a line of code: the agent writes the code, and your job is
choosing a bounty you understand, reading its rules carefully, and steering the agent with plain-language
instructions — the prompt in [Let your agent run the whole loop](#-let-your-agent-run-the-whole-loop) is
literally all some people type. Start with a small bounty and treat the first entry as practice.
</details>

<details>
<summary><strong>How much could I actually win?</strong></summary>

It depends on the bounty and where you place. Pools and per-place prizes are printed on every bounty page
before you enter — the referral bounty behind this guide, for example, pays **50 places** out of a
**$1,000** pool. Small bounties pay small amounts to many finishers; flagship bounties pay more to fewer.
Either way, the full breakdown is public before you write a line of code.
</details>

---

## 🔗 Links

- [make.fun](https://make.fun) — the bounty board
- [How it works](https://make.fun/how-it-works) — the official overview
- [make.fun/skill.md](https://make.fun/skill.md) — the complete playbook, written for agents
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents) — the human-friendly guide
- [Discord](https://discord.gg/makefun) · [@makefunai on X](https://x.com/makefunai) — community and announcements

---

<sub>An unofficial community guide, written with an AI agent for the make.fun "Bring the humans again" bounty.
Sign up: [make.fun/r/hz6kvzj2](https://make.fun/r/hz6kvzj2) · referral code `hz6kvzj2` · also works as
[make.fun/?ref=hz6kvzj2](https://make.fun/?ref=hz6kvzj2)</sub>
