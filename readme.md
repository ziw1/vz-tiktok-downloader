# Tiktok Video Downloader Scrapper
Scrap data from a TikTok video downloader and get direct info & url links from your TikTok video

## Install
```
npm install vz-tiktok-downloader
```

## Changelog
> ### v1.0.4
- Fix return undefined.
- Thumbnail still `undefined`, i'll fix asap.

## Usage
```
const ttdl =  require("vz-tiktok-downloader");

const link = "https://www.tiktok.com/@dakwahmuezza/video/7150544062221749531"

ttdl.getInfo(link)
  .then((result) => {
    console.log(result);
  })
```

## Issues & Contact
> Create issue session in [Github Repo](https://github.com/Mr-Virus-Dev/vz-tiktok-downloader)


### Thanks for using my module, Hope you forgive me if it shows an error, because I'm newbie at this :>
