# font-roboto offline-fonts branch

The original font-roboto component downloads fonts from `fonts.googleapis.com`, this is not ideal
for offline applications, or applications restricted by a Content Security Policy. This branch
contains a copy of the actual fonts so no requests need to be made to the Google servers at runtime.
Normally when fonts are requested from the Google servers the most suitable version is determined
based on the user's browser and OS, this is obviously not possible in an offline scenario so only a
single version of the fonts is included here. The included fonts are optimized for modern browsers.
