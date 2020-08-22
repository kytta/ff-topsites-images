# ff-topsites-images
Slick images for use as Firefox Top Sites' custom thumbnails

## Why

Firefox' Top Sites feature is great and simple, yet there is a problem — the websites have either ugly or no thumbnails. However, one can add a custom image either by uploading it or by using a link. This repo is a collection of handmade thumbnail images for popular sites.

## How

There is currently no list of websites, but you can easily try to find one by inserting the _reversed_ website URL into this template: `https://raw.githubusercontent.com/NickKaramoff/ff-topsites-images/master/dist/<reversed-url>.png`

For example:
  - https://raw.githubusercontent.com/NickKaramoff/ff-topsites-images/master/dist/com.github.png is the thumbnail for github.com
  - https://raw.githubusercontent.com/NickKaramoff/ff-topsites-images/master/dist/com.google.keep.png is the thumbnail for keep.google.com

### Why reversed URLs

This helps order the icons alphabetically. This way subdomains are closer to the main domains, e. g. `google.com` is next to `keep.google.com` rather than being in different ends of a list

## Can I contribute?

Sure! If you want to add an image, [add a request for it](https://github.com/NickKaramoff/ff-topsites-images/issues/new?assignees=NickKaramoff&labels=new+icon&template=icon-request.md&title=Add+%5BWEBSITE_ADDRESS%5D) or implement it yourself and [open a PR][new-pr]. Please note that this is first of all a side project to make my browser pretty, so I may reject your PR or request changes if I dislike the way you did the icon.

The guidelines for thumbnails are as follows:
  - **Format:** PNG
  - **Size:** 192x192
  - **Content:** centered, fits into 152x152 square, preferably 140x140  
    You can use [Material Design Product Icon Guidelines](https://material.io/design/iconography/product-icons.html#grid-and-keyline-shapes) for reference
  - **Compression:** [Squoosh](https://squoosh.app/)
    - **Resize:** Lanczos3 100% to 192x192, Linear RGB
    - **Compress:** OxiPNG with Effort 2

----

All trademark rights reserved by their respective owners. If you own right to an image published in this repo and would like it to be taken down, [file an issue](https://github.com/NickKaramoff/ff-topsites-images/issues/new?assignees=NickKaramoff&labels=takedown&template=takedown-request.md&title=Take+down+%5BWEBSITE_ADDRESS%5D) or [email me](copyright@karamoff.dev).

[new-pr]: https://github.com/NickKaramoff/ff-topsites-images/compare
