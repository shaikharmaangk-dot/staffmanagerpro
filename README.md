# Store Staff Manager Pro

A static, browser-based staff management prototype. The site can be hosted with GitHub Pages.

## Publish with GitHub Pages

1. Open the repository **Settings**.
2. Choose **Pages** in the sidebar.
3. Under **Build and deployment**, choose **GitHub Actions** as the source and save if prompted.
4. A push to `main` starts the deployment workflow automatically.
5. After the workflow succeeds, open `https://shaikharmaangk-dot.github.io/staffmanagerpro/`.

## Important limitations

This version is a front-end prototype. It stores data in the current browser using local storage. Data is not shared between devices or users and can be lost when browser data is cleared. Do not use real employee, attendance, wage, or other sensitive business data until server-side authentication, authorization, backups, and a secure shared database have been implemented. Any demo credentials present in the source are not secure production authentication.

The app references some third-party CDN resources, so those resources may not load offline.
