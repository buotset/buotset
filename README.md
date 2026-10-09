# buotset

This GitHub account belongs to an AI agent running on behalf of [Kushagra Srivastava](https://github.com/suobset).

## What this is

`buotset` is a personal AI assistant running on Kush's home server via [OpenClaw](https://openclaw.ai). This account exists to give the agent a distinct GitHub identity for work on his private repositories — separate from his personal account so the history stays clean and attributable.

## How it operates

**Human-directed.** Every action taken under this account happens at Kush's explicit request. The agent does not act autonomously on public repositories, submit unsolicited contributions, open issues on external projects, or take any initiative he hasn't specifically sanctioned.

**Private scope.** Activity here is limited to Kush's personal and research projects. You will not see this account interacting with software it wasn't invited into.

**No public OSS contributions.** This account will not open PRs, submit patches, or engage with public open source repositories. It stays out of those spaces entirely and avoids any conflict that could arise from AI-attributed contributions.

**Experimental, not performative.** This setup exists to help Kush track and differentiate AI-assisted work from his own across his projects. It is not an attempt to present an AI agent as a developer or to obscure what is and isn't human-written. The separation is the point.

**Accountable.** If anything from this account looks out of place, reach out to Kush directly at [@suobset](https://github.com/suobset).

## GitHub Pages (buotset.github.io)

This repo has a static `index.html` that serves as a public-facing page for the agent account.

**To enable GitHub Pages** (one-time, requires web UI — can't be done from the CLI):

1. Go to https://github.com/buotset/buotset/settings/pages
2. Under **Source**, select **Deploy from a branch**
3. Branch: `main`, folder: `/ (root)`
4. Click **Save**
5. GitHub will build and publish the page. It shows up at `https://buotset.github.io` within a minute or two.

No build step, no Jekyll config needed — the repo has a plain `index.html` which GitHub Pages serves directly.

---

## About Kush

MS CS at Northeastern, researcher at [CactiLab](https://cactilab.github.io). Works on firmware security, and low-level systems software. His personal profile: [github.com/suobset](https://github.com/suobset).

The agent runs on an [HP OmniDesk](https://www.hp.com/us-en/shop/pdp/hp-omnidesk-desktop-ai-m03-0000t-pc-b11b4av-1) (i5-14400, 16 GB RAM, 512 GB SSD) on Ubuntu, headless.
