Signature
======

Templates for signatures in various format, media and applications.

### HTML

The [HTML template](./templates/signature.html) contains information as a [h-card (using microformat-2)](http://microformats.org/wiki/h-card) with embed `<style>` element :

* hover on links add an `→` (arrow) to indicate that it will open in new tab ;
* social icon will rotate `22.5°` right on hover.

Result **as an image** below (code available in : [HTML template](./templates/signature.html)

![HTML signatures](./screenshots/html-rich.png)

## How to use it ?

1. Fork mine ;
2. Fill your info refering to the [H-card microformat specs](http://microformats.org/wiki/h-card) ;
3. Open the `signature.html` using **Chrome/Chromium** ;
    * `Firefox 28.0a1`/`Opera 12.16 build 1860` do **not** copy the `<style>` and `<link>` elements. Henceforth missing typography and layout ;
4. Copy from the HTML to your [Gmail settings](https://support.google.com/mail/answer/8395?hl=en&ctx=mail).

Enjoy :)

## Image or text-only

* The `master` branch is the one using –external– images ;
* the `text-only` image aim to provide an image-free signature, so it should not passively track people reading your email.

### Why not Base64 images ?

I went this way. But using [base64](https://en.wikipedia.org/wiki/base64) images as CSS background is no good as _Gmail_ complains about the length of the signature and refuse to save it. So I went back to external images.
