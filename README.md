# Power BI Portfolio

A static portfolio showcasing selected Power BI dashboards in this repository. It uses data-free, illustrative dashboard previews and does not require a build tool or third-party service.

## Publish with GitHub Pages

1. Push this repository to GitHub and merge the portfolio changes into `main`.
2. In the repository, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.
3. The workflow at `.github/workflows/pages.yml` publishes the site on pushes to `main`. Its URL will be `https://<owner>.github.io/<repository>/`.

The workflow publishes only the site HTML and CSS. Source screenshots are intentionally omitted because they contain report-level figures, and one also contains customer-level records.

## Updating the portfolio

Edit `index.html` to change the project descriptions or add verified contact links. The site currently describes retail sales, banking, e-commerce sales, supply chain, and financial dashboard projects verified from the repository artifacts. Keep customer-level records and other private or sensitive report details out of the public site.
