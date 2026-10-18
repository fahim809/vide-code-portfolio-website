# Fahim — Personal Portfolio

An editable React + Vite portfolio for Fahmidul Islam. All work currently shown is explicitly presented as **self-initiated concept work**.

## Run locally

```bash
pnpm install
pnpm dev
```

Build for production with `pnpm run build`.

## Maintain the portfolio

- **Bio, positioning, contact email, social links, skills, services, projects, and experiments:** edit `src/portfolioData.js`.
- **Add a project:** copy a project object in `projects`. The gallery, filters, and case-study overlay update automatically.
- **Add image or mockup assets:** put optimized files in `src/assets/projects/`, add a path to the relevant project, and render it in `ProjectArt` or the case-study gallery in `src/App.jsx`.
- **Visual design and responsive layouts:** edit `src/styles.css`.
- **Components and animation behaviour:** edit `src/App.jsx`.

Before publishing, add your real email to `profile.email`, add only real social URLs to `profile.socials`, and replace concept work with real work as it becomes available.
