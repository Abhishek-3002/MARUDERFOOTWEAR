# MARUDER FOOTWEAR

A responsive React + Vite storefront. Orders are prepared and sent to WhatsApp; no online payment gateway is connected.

## Run locally
1. Install Node.js (LTS).
2. Open this folder in VS Code.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL shown in the terminal.

## Deploy to Vercel
1. Upload this project to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Framework preset: Vite. Build command: `npm run build`. Output directory: `dist`.
4. Deploy.

## Important setup
Open `src/config.js` and replace `WHATSAPP_NUMBER` with your business WhatsApp number in international format, digits only (India: 91 followed by the 10-digit number). Example format: `919876543210`.

Products are sample demo data in `src/products.js`. Replace names, prices, descriptions, sizes, categories and image URLs with your actual catalogue before launch.

## Admin note
This starter is a storefront, not a secure multi-user admin backend. Product edits in `src/products.js` require a code change and redeploy. Do not put private admin passwords or payment secrets in frontend code. A real secure product dashboard/database can be added in a later phase.
