# Deploy to Firebase Hosting

1. Install the CLI (needs Node.js):  npm install -g firebase-tools
2. Log in:                           firebase login
3. In this folder, link your project: firebase init hosting
   - choose "Use an existing project" (or create one)
   - public directory: public
   - single-page app: No
   - do NOT overwrite public/index.html
4. Put your CV at public/Hussein_Fakih_CV.pdf (the Download CV button points to it)
5. Deploy:                           firebase deploy --only hosting

Your site will be live at https://<project-id>.web.app
