SERIF MK FAVICON PACKAGE
=======================
Contents:
  images/favicon.svg
  images/favicon.ico (16, 32, 48, 64, 128, 256)
  images/favicon-16x16.png
  images/favicon-32x32.png
  images/apple-touch-icon-180x180.png
  images/android-chrome-192x192.png
  images/android-chrome-512x512.png
  images/manifest.json
  _includes/head/custom.html

INSTALLATION ON WINDOWS
-----------------------
1. Extract this ZIP to your existing local Git clone:
     C:\Users\s8907032\Documents\MariusKroeper.github.io-clone
   Merge/overwrite matching files when prompted.
   Keep the existing .git directory in the clone.

2. Open PowerShell and enter:
     cd "C:\Users\s8907032\Documents\MariusKroeper.github.io-clone"
     git status
     git add images/ _includes/head/custom.html
     git commit -m "Replace favicon set with serif MK monogram"
     git push origin master

3. Check GitHub Actions for successful deployment.
4. Your old bookmark may still retain a cached icon. Remove and re-add it
   after opening the updated site if necessary.

NOTE: The package includes the replacement custom.html built from the version
you supplied in this conversation. If you've changed that file subsequently,
merge just the icon/link lines rather than overwriting newer modifications.
