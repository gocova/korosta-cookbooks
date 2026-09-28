# Korosta Cookbooks

Community cookbooks for [Korosta](https://covatools.com/korosta), a browser extension that helps job seekers cut through the noise by fading out job posts they have already seen or that come from companies they chose to skip.

This repo is **free and open**. Nothing here is sold, and anyone can download the cookbooks.

## What's a cookbook?

A **recipe** is a set of CSS selectors, each linked to a key, plus the list of sites where it can be applied. The selectors tell Korosta where job cards, company names, and links live on a given career page or job board.

A **cookbook** is a file that groups related recipes. Cookbooks are exported from Korosta and are data only: no code, no styles, no network requests.

## How to use a cookbook

1. Download a cookbook file from the `cookbooks/` folder.
2. In Korosta, import the file.
3. Open a supported site and click **Apply**.

Korosta never fetches cookbooks on its own, and nothing is applied automatically. You import, you click, and everything runs locally in your browser.

## Contributing

New cookbooks are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) first. In short:

- Cookbooks are exported from Korosta, which requires Korosta Pro. Submit the file as exported.
- An automated check validates every submission.
- Review the site's Terms of Service and note the result in your pull request.
- Sites with aggressive terms are not accepted.
- No shared blocklists naming specific companies.

## License

Released under **CC0 1.0** (public domain). See [LICENSE](LICENSE).

## Disclaimer

Cookbooks are community-contributed and provided as is. This project is not affiliated with, endorsed by, or sponsored by any of the sites or companies listed. Websites change, so a recipe may stop working at any time. If you operate a listed site and want a Cookbook removed, open an issue
or email [support@covatools.com](mailto:support@covatools.com). Please include the site URL and Cookbook name so we can review your request.
