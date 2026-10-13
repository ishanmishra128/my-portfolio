# Ishan Mishra Portfolio

A responsive portfolio built with Astro. The visual system uses a pale seafoam background, deep teal accents, muted mint panels, warm borders, and clear section breaks.

## Requirements
- Node.js 20.19+ or 22.12+
- npm

## Run locally
From this folder, run:

```bash
npm install
npm run dev
```

Open the local URL Astro prints in the terminal, usually `http://localhost:4321`. Stop the server with `Ctrl+C`.

## Before publishing
1. Replace `YOUR-DOMAIN-HERE` in `astro.config.mjs` with your Cloudflare domain.
2. Replace `YOUR_EMAIL` in `src/pages/index.astro` and `src/components/SiteFooter.astro`.
3. Replace `YOUR_GITHUB` and `YOUR_LINKEDIN` in `src/components/SiteFooter.astro`.
4. Update repository links in `src/data/projects.js`. They are deliberately not shown as working source links until you replace the placeholders.
5. Add your resume as `public/resume.pdf`, or change/remove the Resume link in `src/components/SiteHeader.astro`.
6. Check every metric against your project files. The project pages currently label reported results and call out where evaluation details should be added.
7. Add project screenshots, a pipeline diagram, a dashboard screenshot, and model evaluation visuals where the pages have evidence placeholders.
8. Airflow is labelled as in progress because the CivicPulse DAG is not yet confirmed to run end to end. Update this label once the workflow and tests succeed.

## Build and preview
```bash
npm run build
npm run preview
```

## Deploy to Cloudflare Pages
1. Create a GitHub repository for this project and push the folder contents.
2. In Cloudflare, open **Workers & Pages** and create a Pages project connected to the repository.
3. Set build command to `npm run build` and build output directory to `dist`.
4. Add your custom domain under the project's **Custom domains** settings and follow Cloudflare's DNS instructions.
5. Set the real canonical domain in `astro.config.mjs`, commit, and redeploy.

## Skills listed
Python, SQL, R, HTML, CSS, JavaScript, Figma, PostgreSQL, dbt, ETL/ELT, data modeling, Linux, Apache Airflow (learning), AWS S3, AWS Glue, Amazon Redshift, SageMaker, Snowflake, Google Cloud, BigQuery, Firebase, GitHub Actions, Pandas, scikit-learn, PyTorch, CNNs, Tableau, Tableau Cloud, and model evaluation.
