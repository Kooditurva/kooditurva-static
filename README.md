# kooditurva-static

Public static files for Kooditurva Oy, served by GitHub Pages at
https://kooditurva.github.io/kooditurva-static/.

| Path | What | Source |
|---|---|---|
| `lifespan-predictor/video/` | Marketing video page, linked from the AWS Marketplace listing's product video URL | `video.mp4` and `poster.png` (from `cover_1080.png`) are copied from `dist/` in `Kooditurva/lifespan-predictor-video` |
| `assets/kooditurva.png` | Logo | `assets/brand/` in `Kooditurva/lifespan-predictor-video` |

Files here are copies. To update the video, re-render it in `lifespan-predictor-video`
and copy `dist/video.mp4` over `lifespan-predictor/video/video.mp4`.
