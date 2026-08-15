<p align="center">
  <strong>TopDaily Dev</strong> — OSS CLI tooling for README badges, repo health, and safe releases.
</p>

<p align="center">
  <a href="https://github.com/topdaily-dev/badgekit"><img src="https://img.shields.io/badge/badgekit-README_badges-0ea5e9?style=for-the-badge" alt="badgekit"></a>
  <a href="https://github.com/topdaily-dev/repomark"><img src="https://img.shields.io/badge/repomark-repo_health-22c55e?style=for-the-badge" alt="repomark"></a>
  <a href="https://github.com/topdaily-dev/shipkit"><img src="https://img.shields.io/badge/shipkit-releases-8b5cf6?style=for-the-badge" alt="shipkit"></a>
</p>

---

## Toolchain

Three small CLIs that compose — no SaaS, no lock-in.

| Tool | Purpose |
|------|---------|
| [**badgekit**](https://github.com/topdaily-dev/badgekit) | Generate and validate shields.io README badge rows |
| [**repomark**](https://github.com/topdaily-dev/repomark) | Score OSS repo hygiene; scaffold missing policy files |
| [**shipkit**](https://github.com/topdaily-dev/shipkit) | Preflight, changelog, GitHub release, npm publish |

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

Bootstrap a new repo with team workflows + this stack:

```bash
npx @korykaai/collab-kit init . --oss-toolchain
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
</p>

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
