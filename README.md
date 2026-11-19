# Monarch Studio

A static, single-page studio and portfolio site. All HTML, CSS, JavaScript, and poster images are contained in `index.html`. The eight web-optimized MP4 films live in `media/`; they are separate files so visitors do not have to download every video to open the page. There is no build step or runtime dependency.

## Preview locally

From the repository root, run:

```sh
python3 -m http.server 8000
```

Open <http://localhost:8000/>. The page also works when opened directly as a local file. Videos use native controls and only load when played; links beside the films open their individual originals on Google Drive.

## Customize

Edit `index.html` to change the copy, colors, sections, and links. When replacing a video, update its file in `media/`, its `<source>`, and its poster. The contact section intentionally says “Contact details coming soon” until a real contact method is supplied. The YouTube workflow ends with delivery to Google Drive; the client uploads the finished video to YouTube.
