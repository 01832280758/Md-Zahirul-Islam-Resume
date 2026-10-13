[README.md](https://github.com/user-attachments/files/33407580/README.md)
# Md. Zahirul Islam | Portfolio

Personal portfolio and CV site. Plain HTML, CSS and a little JavaScript. No build step.

## Files

```
index.html                    the whole site
assets/photo.jpg              your portrait
assets/Zahirul_Islam_CV.pdf   the CV people download
README.md                     this file
```

## 1. Add your YouTube channel (one line)

Open `index.html` and scroll to the bottom. Find this block:

```js
var SITE = {
  youtube:   "https://www.youtube.com/@YOUR-CHANNEL",
  ytVideoId: "",
  whatsapp:  "8801832280758",
  ...
};
```

- Replace `https://www.youtube.com/@YOUR-CHANNEL` with your real channel link. Every YouTube button on the page updates by itself.
- Optional: paste one video ID into `ytVideoId` (the letters after `v=` in a YouTube link) and that video plays right on the page.
- `whatsapp` is country code plus number, digits only. It is set to +880 1832-280758. Change it if your WhatsApp number is different.
- `linkedin` is already set to your profile.

## 2. Publish on GitHub Pages

1. On github.com click **New repository**. Name it **YOUR-USERNAME.github.io** (your exact GitHub username). Public.
2. Click **uploading an existing file**. Drag in `index.html`, `README.md` and the `assets` folder. **Commit changes**.
3. **Settings > Pages**. Build and deployment: **Deploy from a branch**, branch **main**, folder **/ (root)**. **Save**.
4. After a minute or two your site is live at `https://YOUR-USERNAME.github.io`.

## 3. After publishing

- In `index.html`, find the `og:image` line near the top and put your full photo URL, for example `https://YOUR-USERNAME.github.io/assets/photo.jpg`. This is the picture shown when the link is shared on LinkedIn or WhatsApp.
- Replace `assets/photo.jpg` with a larger portrait (800 x 1000 px or more), same file name, for a sharper hero image.
- Replace `assets/Zahirul_Islam_CV.pdf` whenever you update your CV, same file name.
- Your phone number and email are public on this page. The CV PDF on the site leaves out your date of birth and referee details on purpose.
