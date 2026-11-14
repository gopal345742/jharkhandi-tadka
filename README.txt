# Jharkhandi Tadka website — Version 2

## Website features
- Responsive landing page based on the Jharkhandi Tadka brand poster
- Menu categories and prices from the supplied menu poster
- Add-to-cart website order form with customer name, address and notes
- Direct WhatsApp ordering option
- Website order form sends a formatted order message to WhatsApp
- Contact, order timing, advance booking and delivery details

## Run locally
Keep `index.html` and `poster.jpg` in the same folder, then open `index.html` in a browser.

## Free publishing using GitHub Pages
1. Sign in to GitHub and create a **public** repository named `jharkhandi-tadka`.
2. Upload both `index.html` and `poster.jpg` to the repository root.
3. Open repository **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. Wait for GitHub Pages to publish the site. The URL will be shown in the Pages section.

Alternative: use Netlify's manual deploy by uploading the folder containing both files.

## Important limitations of this no-cost first version
- No admin login or database yet.
- No online payment gateway; UPI payment is arranged manually after WhatsApp confirmation.
- No automatic order tracking.
- Website form does not save orders on a server; it opens WhatsApp with the order details.

## Check before launch
Confirm the menu/prices, WhatsApp number, delivery area, opening hours, advance booking and payment rules. The supplied poster says orders 10 AM–8 PM, book at least one day ahead, next-day delivery across Obra, advance UPI required and no cash on delivery.
