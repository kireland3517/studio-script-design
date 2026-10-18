# Studio Script Design

Marketing site for Studio Script Design: healthcare operations consulting and compliance resources for peer support organizations. It sells two kits (MEDICAID-READY and the Admissions & Referral Coordinator Toolkit) and publishes a blog on Medicaid billing, 42 CFR Part 2 consent, and peer specialist credentialing.

**Who it's for:** peer support organizations and the program directors, billing staff, and referral coordinators who run them.

**Stack:** Astro 6 (static output), MDX for blog posts, Tailwind CSS 4. Requires Node 22.12 or newer.

## Run it

```bash
npm install
npm run dev       # dev server at localhost:4321
```

```bash
npm run build     # static site to ./dist/
npm run preview   # serve the build locally
```

## Pages

Home, About, MEDICAID-READY, Admissions Pipeline Fix, and a blog (`src/content/blog/*.mdx`).

## Related repos

Not the same project as [studio-script-design-agent](https://github.com/kireland3517/studio-script-design-agent), the Python design-consultant agent.
