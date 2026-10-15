# 🌳 Tree Removal Calculator

A free, open-source calculator that estimates the cost of removing a tree in the USA.
Enter the tree's height in feet, click **Calculate**, and get an estimated price range in USD.

**Live demo:** _coming soon_

## How it works

The estimate is based on rough US national averages by tree height:

| Height        | Size            | Estimated price   |
|---------------|-----------------|-------------------|
| Up to 30 ft   | Small tree      | $200 – $500       |
| 31–60 ft      | Medium tree     | $500 – $1,000     |
| 61–80 ft      | Large tree      | $800 – $1,500     |
| Over 80 ft    | Very large tree | $1,500 – $2,500   |

Actual prices vary with location, trunk diameter, tree condition, nearby structures and stump grinding.

## Run locally

It's a single static file — just open `index.html` in your browser.

## Customize prices

Edit the `tiers` array in the `<script>` at the bottom of `index.html`.

## Deploy

Works on any static host. On [Vercel](https://vercel.com), import the repo — no build settings needed.

## License

[MIT](LICENSE)
