# rtb-clips

Public static host for RTB video clips awaiting Instagram publishing.

Instagram's Graph API fetches reel video files from a public URL, so finished
clips are parked here and served over GitHub Pages. Files are remuxed with
`-movflags +faststart` (moov before mdat) which the IG media endpoint requires.

Clips can be removed once the corresponding post is live.
