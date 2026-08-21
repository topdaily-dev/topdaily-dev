<p align="center">
  <strong>TopDaily Dev</strong> — OSS CLI tooling for README badges, repo health, and safe releases.
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@topdaily-dev/badgekit"><img src="https://img.shields.io/npm/v/@topdaily-dev/badgekit.svg?style=flat-square" alt="badgekit npm"></a>
  <a href="https://www.npmjs.com/package/@topdaily-dev/repomark"><img src="https://img.shields.io/npm/v/@topdaily-dev/repomark.svg?style=flat-square" alt="repomark npm"></a>
  <a href="https://www.npmjs.com/package/@topdaily-dev/shipkit"><img src="https://img.shields.io/npm/v/@topdaily-dev/shipkit.svg?style=flat-square" alt="shipkit npm"></a>
</p>

<p align="center">
  <a href="https://github.com/topdaily-dev/badgekit"><img src="https://img.shields.io/badge/badgekit-README_badges-0ea5e9?style=for-the-badge" alt="badgekit"></a>
  <a href="https://github.com/topdaily-dev/repomark"><img src="https://img.shields.io/badge/repomark-repo_health-22c55e?style=for-the-badge" alt="repomark"></a>
  <a href="https://github.com/topdaily-dev/shipkit"><img src="https://img.shields.io/badge/shipkit-releases-8b5cf6?style=for-the-badge" alt="shipkit"></a>
</p>

---

## Toolchain

Three small CLIs that compose — no SaaS, no lock-in.

| Tool | npm | Purpose |
|------|-----|---------|
| [**badgekit**](https://github.com/topdaily-dev/badgekit) | `@topdaily-dev/badgekit` | Generate and validate shields.io README badge rows |
| [**repomark**](https://github.com/topdaily-dev/repomark) | `@topdaily-dev/repomark` | Score OSS repo hygiene; scaffold missing policy files |
| [**shipkit**](https://github.com/topdaily-dev/shipkit) | `@topdaily-dev/shipkit` | Preflight, changelog, GitHub release, npm publish |
| [**repomark-action**](https://github.com/topdaily-dev/repomark-action) | — | GitHub Action wrapper for repomark CI |

```bash
# Badges
npx @topdaily-dev/badgekit row ci npm license --owner topdaily-dev --repo badgekit --npm @topdaily-dev/badgekit
npx @topdaily-dev/badgekit validate .

# Repo health
npx @topdaily-dev/repomark check .
npx @topdaily-dev/repomark fix .

# Release
npx @topdaily-dev/shipkit preflight
npx @topdaily-dev/shipkit ship --patch --yes
```

Bootstrap a new repo with team workflows + this stack ([collab-kit](https://github.com/kory-kaai/collab-kit)):

```bash
npx @korykaai/collab-kit init . --oss-toolchain
collab-kit enable-hooks .
```

---

## Featured repos

<p align="center">
  <a href="https://github.com/topdaily-dev/badgekit">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=topdaily-dev&repo=badgekit&theme=tokyonight&hide_border=true&border_radius=12" alt="badgekit" />
  </a>
  <a href="https://github.com/topdaily-dev/repomark">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=topdaily-dev&repo=repomark&theme=tokyonight&hide_border=true&border_radius=12" alt="repomark" />
  </a>
  <a href="https://github.com/topdaily-dev/shipkit">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=topdaily-dev&repo=shipkit&theme=tokyonight&hide_border=true&border_radius=12" alt="shipkit" />
  </a>
</p>

---

## Pair with collab-kit

Maintained with **[kory-kaai/collab-kit](https://github.com/kory-kaai/collab-kit)** — human co-authors only, no agent attribution.

---

## Stack

TypeScript · Node.js · React · Next.js · PostgreSQL · Docker · GitHub Actions · npm

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,nodejs,react,nextjs,postgres,docker,github,vercel&perline=8" alt="Skills" />
</p>

---

<p align="center">
  <i>Building maintainable OSS — shipped in public.</i>
</p>
