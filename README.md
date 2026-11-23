# Tesseract Demo

This repo contains a demo of the OCR library [Tesseract](https://github.com/naptha/tesseract.js).

## Running The Demo

1. launch a local webserver. You can use PHP, Python, or any other webserver.

**Example**

```
$ python3 -m http.server 9999
```

2. Open a web browser and navigate to the URL hosted by your webserver.

3. Once the app loads, use the image loader in the app to load an image for Tesseract to perform OCR on. The page lists the Tesseract example image, but you can also test with your own images by adding them into the `examples` directory and then using the local url (ex. `127.0.0.1:9999/examples/eng_bw.png`).

## Demo GIF

![GIF of the demo](https://media.giphy.com/media/2n4hc3eaAgn9kntrao/giphy.gif "Demo GIF")
