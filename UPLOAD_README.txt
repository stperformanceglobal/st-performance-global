ST PERFORMANCE GLOBAL - GITHUB READY BUILD

WHY YOU ARE SEEING 404s
Only index.html reached the repository. The other eight pages are not
there, so every internal link has nowhere to go. Upload ALL the files
in this folder together and the 404s stop.

GitHub's web uploader also flattens folders unless you drag a whole
folder. This build has no folders at all, so that cannot break anything.

HOW TO UPLOAD
1. Your repository on github.com, Add file, Upload files
2. Select EVERY file in this folder and drag them in together
3. Commit changes
4. Settings, Pages, Deploy from a branch, main, / (root), Save

BEFORE YOU MOVE DNS, READ THIS
Your domain currently points at Squarespace, which is why the shop,
subscription and contact pages still work. All six commerce links in
this build use that domain. The moment DNS points at GitHub Pages they
will break.

Fix: get your Squarespace built-in domain from Settings, Domains,
Built-in Domain. It looks like something.squarespace.com. Then in each
HTML file, inside the script block near the bottom, replace
www.stperformanceglobal.com with that built-in domain in these six
values only:
  subscribeSelfStarter, subscribeProfessional, subscribeEnterprise,
  productPressureWorkbook, productRiskCascadeEbook, squarespaceForm
Leave booking, articles, emails and social links alone.

Or send me the built-in domain and I will produce a finished build.
