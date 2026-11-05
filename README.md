# Freelance Client Portal

An early-stage, open-source prototype for freelancers to organize clients and deliverables in one calm workspace.

## Current features
- Responsive dashboard with client and task counts
- Add clients and tasks
- Change task status (To do, In progress, Done)
- Browser-local persistence using `localStorage`
- Demo client records included for exploration

**Important:** This is a local prototype, not a production-ready multi-user portal. There is no authentication, server, or cloud database. Do not store real client secrets or sensitive information in this version.

## Run locally

Requires Node.js 18+.

```bash
npm install
npm run dev
```

Open the local address printed by Vite.

## Production build

```bash
npm run build
```

Deploy the generated `dist/` directory on a static host such as Vercel or GitHub Pages (with appropriate base-path configuration).

## Roadmap
- [ ] Client edit/delete and accessible confirmations
- [ ] Task filtering, sorting and due-date reminders
- [ ] Export/import of workspace data
- [ ] Per-client theme customization
- [ ] Optional secure authentication and role-based access
- [ ] Database-backed collaboration and audit logs
- [ ] Client-owned cloud file integrations
- [ ] Tests and accessibility review

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md). Feedback, reproducible bug reports and focused pull requests are welcome.

## License
MIT. See [LICENSE](LICENSE).
