<a href="https://4626.fun">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.png">
    <img alt="akita: onchain tools for creators, built with a team of ai agents. now building 4626.fun, creator vaults on Base with a lottery built in." src="assets/banner-light.png" width="100%">
  </picture>
</a>

<p align="center">
  <a href="https://4626.fun"><img alt="4626.fun" src="https://img.shields.io/badge/4626.fun-2F7BFF?style=for-the-badge&logoColor=white"></a>
  <a href="https://docs.4626.fun"><img alt="docs" src="https://img.shields.io/badge/docs-2B2F30?style=for-the-badge"></a>
  <a href="https://x.com/wenakita"><img alt="X @wenakita" src="https://img.shields.io/badge/@wenakita-000000?style=for-the-badge&logo=x&logoColor=white"></a>
  <a href="https://linkedin.com/in/wenakita"><img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>

hi, i'm akita 🐕 i build onchain stuff for creators. ai agents do most of the typing; i decide what gets built and what's allowed to ship.

## now: 4626

<p>
  <a href="https://4626.fun"><img alt="4626.fun landing page: Creator Vaults. Owned Together." src="assets/4626-site.png" width="49%"></a>
  <a href="https://docs.4626.fun"><img alt="4626 docs: Creator vaults on Base" src="assets/4626-docs.png" width="49%"></a>
</p>

**[4626](https://4626.fun)** gives every creator their own [ERC-4626](https://eips.ethereum.org/EIPS/eip-4626) vault on Base. a creator puts their coin in, fans buy shares, and every buy pays a 6.9% fee. most of that fee goes into a lottery pot, and every buy is a ticket. fun matters.

it's in private beta. the [simulator](https://4626.fun) and [docs](https://docs.4626.fun) are public.

<details>
<summary><b>how i got here</b></summary>
<br>

i spent a while on **omnidragon**, a swap-to-win lottery across chains. then i noticed people didn't want to just play a lottery. they wanted to build their own brand with their own coin, the way zora works. so i shelved it and built 4626 around that. the lottery came along for the ride.

</details>

## how i build

- **start silly, finish serious.** repo names are jokes. the proofs aren't.
- **one job per agent.** ai agents write most of the code. each one gets a single job and a clear lane.
- **nothing merges on vibes.** a change ships when tests, formal verification and review back it up, plus a yes from me on that exact change. one formal-verification pass proved 44 of 45 properties.
- **automate the checking.** right now i'm the last gate. i'm working on automating that part too.
- **build privately, publish proof.** what goes public is something you can check: rebuildable audit snapshots, a hackathon entry, docs.

## poke around

| project | what it is |
|:--|:--|
| [**4626fun/monorepo**](https://github.com/4626fun/monorepo) | the public side of 4626: contracts, frontend, indexer and docs. |
| [**creator-vaults-audit**](https://github.com/4626fun/creator-vaults-audit) | a pinned source snapshot with tests anyone can rerun, made for independent security review. |
| [**convergence-chainlink-hackathon**](https://github.com/4626fun/convergence-chainlink-hackathon) | my Chainlink hackathon entry: Chainlink CRE workflows that check 4626 payout wiring, with a 2-minute judge quickstart. |
| [**4626-Brand-Kit**](https://github.com/wenakita/4626-Brand-Kit) | logos, colors and social images for 4626 (from before the new flame logo). |

---

<p align="center"><sub>building in los angeles · say hi on <a href="https://x.com/wenakita">x</a></sub></p>
