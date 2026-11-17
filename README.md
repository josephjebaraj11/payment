# UPI payment page — Joseph JebaRaj

This is a static HTTPS-ready landing page. It offers:
- A generic UPI intent (`upi://pay`) for compatible UPI apps.
- Your supplied Google Pay/Tez intent (`tez://upi/pay`).
- The UPI ID as a manual fallback.

## Publish free with GitHub Pages

1. Sign in to GitHub and create a **public** repository, for example `joseph-upi-payment`.
2. Upload `index.html` from this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. Your HTTPS address will look like:
   `https://YOUR-GITHUB-USERNAME.github.io/joseph-upi-payment/`
7. Open that HTTPS address on an Android phone and test both payment buttons before sharing it.

## Important
- Replace `YOUR-GITHUB-USERNAME` with your actual GitHub username; the final URL cannot be known until you publish.
- This page does not process or confirm payments. It only launches a UPI app with recipient details.
- The generic UPI button asks the device to handle `upi://pay`; which app opens depends on Android/browser defaults and installed apps. It cannot guarantee an app chooser on every phone.
- The supplied `tez://` scheme may not be supported by every device or Google Pay version.
- Test with a small amount and verify the displayed recipient name and UPI ID before paying.
