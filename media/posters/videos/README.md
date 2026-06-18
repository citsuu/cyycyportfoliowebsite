# Video Replacement Folder

Drop your exported videos here, then connect them in `data/projects.ts`.

Recommended export settings:

- Format: `.mp4` or `.webm`
- Ratio: `16:9`
- Resolution: `1920x1080` or `1280x720`
- Codec: H.264 for `.mp4`
- Keep filenames lowercase with hyphens.

Example:

```ts
{
  title: "Static - Short Film Concept",
  poster: "/media/project-wide-01.png",
  thumbnail: "/media/project-wide-01.png",
  media: "/media/project-wide-01.png",
  mediaKind: "image",
  video: "/media/videos/static-short-film.mp4"
}
```

When `video` is present, the project modal automatically becomes a real video player with native controls.
