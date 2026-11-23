# Streambert TV install guide

Static GitHub Pages site. Set Pages to **Deploy from a branch**, select the branch with these files, and choose **/(root)**. The entry point is index.html. No build or secrets are required.

The guide credits the original Streambert project and describes independently modified TV builds. The downloads contain packages, installation instructions, and the changes made for the TV build. The guide contains no TV device addresses or personal tokens.

The shared phone kit is served at the existing `downloads/Streambert-Fire-TV-Phone-Kit.zip` URL. To refresh it, create a ZIP with `Streambert-TV-Fire-OS.apk`, `Start-here-Android-TV.txt`, `Start-here-Fire-TV.txt`, and `Start-here-TMDB.txt` from `downloads/` at the archive root. The Roku ZIP is the app itself. Keep its guide outside the ZIP.

The shared Android TV and Fire OS APK includes next-episode autoplay in the regular player and Back and Sub/Dub fixes in the anime player. These were confirmed on NVIDIA Shield. Fire OS still needs a device playback test. Roku, Samsung, LG, and Vega use separate playback implementations.
