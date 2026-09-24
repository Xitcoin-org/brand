# Xitcoin brand assets

<p>
<img src="assets/png/square/xitcoin-square-200.png" width="96" alt="Xitcoin app icon">&nbsp;
<img src="assets/png/round/xitcoin-round-200.png" width="96" alt="Xitcoin round avatar">&nbsp;
<img src="assets/png/symbol-color/xitcoin-symbol-color-200.png" width="96" alt="Xitcoin symbol">
</p>

Official logo files for **Xitcoin** (XTC) — *Trade · Connect* — [xitcoin.org](https://xitcoin.org).
Xitcoin is a brand of [Kcalb Ltd](https://kcalb-ltd.com), part of the KcalbApp ecosystem.

## Choose an asset

| You need | Use |
|---|---|
| App icon, profile picture, favicon | [`assets/png/square/`](assets/png/square/) — 32, 200, 500, 1024, 3000 px |
| Round avatar, wallet or token list | [`assets/png/round/`](assets/png/round/) — 32, 200, 500, 1024, 3000 px |
| Symbol on a dark or colored background | [`assets/png/symbol-white/`](assets/png/symbol-white/) |
| Symbol on a white or light background | [`assets/png/symbol-color/`](assets/png/symbol-color/) |
| Print, large formats, any other size | [`assets/svg/`](assets/svg/) — vector masters |

Every PNG is rendered from the SVG masters. Use the SVG whenever the platform accepts it, otherwise the smallest PNG that is at least as large as the display size on a high-density screen.

Direct links, for integrations: `https://raw.githubusercontent.com/xitcoin-org/brand/main/assets/png/round/xitcoin-round-500.png`. For production, pin a commit hash instead of `main` and check the file against [asset-manifest.json](asset-manifest.json).

## Official colors

| Color | Hex | Use |
|---|---|---|
| Xitcoin | `#F58804` | background of the icon, symbol on light backgrounds |
| Shadow | `#673902` | drop shadow under the symbol only |
| White | `#FFFFFF` | symbol on the brand color or on dark backgrounds |

The icon is a flat brand color with a white symbol and a soft drop shadow toward the lower right. The mark itself never uses gradients.

## Usage rules

- Use the files as provided. Do not redraw, recolor, stretch, rotate, crop or outline the symbol, and do not add effects.
- Keep the symbol centered in its square or circle, and keep clear space around the icon.
- On a white background, use the square or round icon, or the colored symbol. On a dark background, use the icon or the white symbol.
- Do not place the artwork next to another mark in a way that suggests partnership or endorsement.
- Refer to the brand as **Xitcoin**, with this exact spelling.

## Integrity

`asset-manifest.json` lists every file with its size and SHA-256 hash. The *Asset integrity* check runs `scripts/verify-assets.py` on every change and fails if any file is added, removed or altered without updating the manifest.

## The Kcalb Ltd brand family

| Brand | Assets | Website |
|---|---|---|
| Xitcoin | [`xitcoin-org/brand`](https://github.com/xitcoin-org/brand) | [xitcoin.org](https://xitcoin.org) |
| KcalbApp | [`KcalbApp/kcalbapp-brand`](https://github.com/KcalbApp/kcalbapp-brand) | [kcalb-ltd.com](https://kcalb-ltd.com) |
| InoAi | [`KcalbApp/inoai-brand`](https://github.com/KcalbApp/inoai-brand) | [inoai.org](https://inoai.org) |
| Kcanther | [`KcalbApp/kcanther-brand`](https://github.com/KcalbApp/kcanther-brand) | [kcanther.org](https://kcanther.org) |
| InoSwap | [`KcalbApp/inoswap-brand`](https://github.com/KcalbApp/inoswap-brand) | [inoswap.org](https://inoswap.org) |
| StakeHolDrop | [`KcalbApp/stakeholdrop-brand`](https://github.com/KcalbApp/stakeholdrop-brand) | [stakeholdrop.com](https://stakeholdrop.com) |
| Crypto-Only | [`KcalbApp/crypto-only-brand`](https://github.com/KcalbApp/crypto-only-brand) | [crypto-only.org](https://crypto-only.org) |

## Token integration

Use **Xitcoin** for the project name and **XTC** for the asset symbol. A logo is not proof of asset identity: always verify the network and the complete contract address or native denomination through the [Xitcoin Guide](https://xitcoin.gitbook.io/guide/). Use alternative text such as “Xitcoin symbol”. Wallets and token lists should use the round icon.

Report security concerns through the Guide's responsible-disclosure process.

## License and contact

The artwork is published under [CC0 1.0 Universal](LICENSE) so that wallets, explorers and token lists can use it freely. The usage rules above describe official presentation; they do not restrict the CC0 dedication or imply endorsement.
Questions and requests: **contact@xitcoin.org**, or open an [issue](https://github.com/xitcoin-org/brand/issues).
