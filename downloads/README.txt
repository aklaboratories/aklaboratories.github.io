Download files go here.

The site's download buttons point to:
  downloads/Prism.zip   -> Prism app (zip the ad-hoc-signed build/Prism.app)
  downloads/Halo.dmg    -> Halo disk image (dist/Halo.dmg)

Drop those two files into this folder with exactly those names and every
"Download" button on the page works with no code changes.

To regenerate the builds:
  Prism:  ./build.sh   then  zip -r downloads/Prism.zip build/Prism.app
  Halo:   scripts/package-app.sh   then copy dist/Halo.dmg -> downloads/Halo.dmg
