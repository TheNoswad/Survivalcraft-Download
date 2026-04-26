# Survivalcraft Download

An unofficial download page for [Survivalcraft](https://kaalus.wordpress.com), available at **[survivalcraft.download](https://survivalcraft.download)**.

Displays locale-aware store badges for iOS, Android, Amazon, and Windows. Served over Cloudflare Pages with an animated panorama background ported from the game itself.

## Features

- **Locale-aware store badges** — automatically selects the correct App Store, Google Play, and Amazon Appstore badge based on the visitor's browser language
- **Animated panorama background** — Animated tiling panorama background ported from the game's `PanoramaWidget`
- **Responsive layout** — 2×2 badge grid on desktop, single column on mobile

## Stores

| Platform | Link |
|----------|------|
| iOS (App Store) | https://apps.apple.com/us/app/survivalcraft-2/id1185580782 |
| Android (Google Play) | https://play.google.com/store/apps/details?id=com.candyrufusgames.survivalcraft2 |
| Amazon Appstore | https://www.amazon.com/dp/B01N6GTF7M |
| Windows (Microsoft Store) | https://apps.microsoft.com/detail/9phc48p58nb2 |

## Development

No build step required. Opening `index.html` directly in a browser will **not** work, instead use any static file server:

```bash
python3 -m http.server
```

## Deployment

Hosted on [Cloudflare Pages](https://pages.cloudflare.com). Deployments trigger automatically on push to `main`.

To deploy your own fork:

1. Push to GitHub
2. Cloudflare Dashboard → Pages → Connect to Git → select repo
3. Leave build command blank (static site)
4. Set custom domain if desired

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for:

- Missing or incorrect store badges
- Locale support improvements
- Visual or accessibility fixes
- More links, potentially to modded versions or communities. Or links to Bugs and Ruthless Conquest?
- Bugs

## License

This project is licensed under the **GNU General Public License v3.0** — see [LICENSE](LICENSE) for details. Any forks or modifications must be released under the same license.

The files in the `badges/` and `assets/` directories, and the Survivalcraft logo and favicons are **not covered** by the above license. They are property of their respective owners:

- **Survivalcraft logo, name, and related assets** © CandyRufusGames — used for fan/informational purposes only, not affiliated with or endorsed by CandyRufusGames — https://kaalus.wordpress.com
- **Apple App Store badges** © Apple Inc. — https://developer.apple.com/app-store/marketing/guidelines/
- **Google Play badges** © Google LLC — https://partnermarketinghub.withgoogle.com/brands/google-play/
- **Amazon Appstore badges** © Amazon.com, Inc. — https://developer.amazon.com/support/legal/tuabg
- **Microsoft Store badge** © Microsoft Corporation — https://apps.microsoft.com/badge

## Disclaimer

This is an unofficial download page and is not affiliated with, endorsed by, or associated with CandyRufusGames or the developers of Survivalcraft. All trademarks, store badges, and app names are the property of their respective owners.
