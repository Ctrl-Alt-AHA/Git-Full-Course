# Part 02 platform notes

Verification date: 2026-10-16. Research only; no account was contacted and nothing was uploaded. Target platforms: YouTube Shorts, TikTok, Instagram Reels, X, Patreon. Facebook is excluded.

The user's stricter common deliverable is <60 seconds, 1080x1920 9:16, 30 fps H.264/yuv420p MP4, AAC 48 kHz stereo, faststart, embedded captions and no watermark. Reuse this master where compatible. The X web derivative is justified below; no other derivative is currently needed. Actual account upload success is untested. Keep subtitle sidecars in English SRT and VTT, but never promise every uploader accepts them. Burned-in captions already exist: native captions may duplicate them.

## Verified official guidance

### YouTube Shorts

[Upload Shorts](https://support.google.com/youtube/answer/12779649?hl=en): square or vertical videos up to three minutes qualify in the documented upload flow. This batch remains strictly below one minute by user requirement. Supply a title and description; a sparse #Git/#Shorts choice is editorial, not a reach promise.

[Custom thumbnails](https://support.google.com/youtube/answer/72431?hl=en): current documentation explicitly permits custom Shorts thumbnails through desktop YouTube Studio for verified accounts, recommending 9:16. Do not repeat older blanket advice that Shorts cannot upload custom artwork. The requested 1080x1920 JPEG exceeds its documented minimum height; the page recommends a higher resolution, which is a recommendation rather than this batch's requirement. Supply the vertical cover plus an existing-frame timestamp as fallback. Account verification/feature availability remains unverified.

[AI disclosure](https://support.google.com/youtube/answer/14328491?hl=en): realistic AI-generated/altered material can require disclosure. The fetched current page names an AI use setting; older localized guidance may call it Altered content. Record the synthetic narrator transparently. Whether the generic synthetic narration triggers a particular upload classification must be assessed in the actual current flow. The music here is generated procedurally by a local NumPy script, not an AI music model; do not mislabel it as AI-generated music. No real-person impersonation or realistic event footage is present.

### TikTok

[Cover selection](https://support.tiktok.com/en/using-tiktok/creating-videos/editing-posting-and-deleting?lang=en): select a cover by dragging to an existing frame before posting. Supply the exact candidate-frame timestamp. External JPEG artwork is a reusable asset, not a guaranteed custom-cover upload option.

[AI-generated content](https://support.tiktok.com/en/using-tiktok/creating-videos/ai-generated-content): realistic AI-generated audio is subject to labeling requirements. The synthetic human-sounding narrator merits using the applicable AI-generated-content disclosure. No account setting was changed. [Accessibility](https://support.tiktok.com/en/using-tiktok/creating-videos/accessibility) is the official reference for native captions; sidecar upload support is not established here.

Camera-tools duration guidance could not be fetched: it redirected to an inaccessible TikTok FAQ. Do not assert a numeric maximum or file-size limit from an unverified third-party page. The planned subminute MP4 is the production target; actual account/import compatibility remains untested.

### X

[Sharing video](https://help.x.com/en/using-x/x-videos): ordinary accounts may upload up to 140 seconds and 512 MB. Compare actual package bytes against this limit. Do not assume Premium. The English live-page parser exposes resolution/aspect-ratio FAQ headings without answers. A follow-up search retrieval of the [official Spanish FAQ](https://help.x.com/es/using-x/x-videos) on2026-10-16 exposes its web limits: portrait1200x1900, aspect ratio1:2.39–2.39:1, up to40fps and25Mbps. This is official indexed guidance; the live-page parser still omits those answers and actual account upload is untested. Do not substitute Media Studio or advertising limits for ordinary web upload.

The1080x1920 master exceeds that documented web portrait height. Supply a720x1280 exact9:16 X compatibility derivative, scaling the whole composition without cropping or retiming and copying the AAC stream. Verify its H.264/yuv420p30fps, duration<60s, file size, faststart, full decode and scene/seam image readability; confirm demuxed AAC matches the master. This derivative is justified specifically by X web compatibility, not a claim that every mobile/account flow rejects the master. Every candidate and derivative remains unaccepted until listening review passes. The user's post limit is<=280 characters including spaces and hashtags; verify literal length locally. Custom cover and sidecar-caption controls remain unverified. Provide an existing cover frame and embedded captions.

### Patreon

[Video overview](https://support.patreon.com/hc/en-us/articles/6598555214477-Patreon-Video-overview): native video is eligibility-dependent, currently supports 720p/1080p, offers frame/custom thumbnails, and accepts custom SRT/VTT captions. Check account eligibility and quota at upload; do not invent tiers or audiences.

[Image sizing](https://support.patreon.com/hc/en-us/articles/360038982432-How-do-I-size-images-for-Patreon-posts): 1280x720 at 16:9 is recommended for a video thumbnail. Use the recomposed landscape cover.

[Posting](https://support.patreon.com/hc/en-us/articles/115004048046-Posting-to-your-Patreon): title is required; settings and audience controls depend on surface. [Video file attachment](https://support.patreon.com/hc/en-gb/articles/360017431292-Posting-videos): MP4 is supported as a download attachment with a 5GB maximum, but this does not provide a video player. Do not silently substitute attachment-only delivery for native video. Supply a fuller explanatory post and discussion question, leaving audience, membership and notification settings unresolved.

## Official verification gaps

Instagram's [Reel size page](https://help.instagram.com/1038071743007909/) returned an internal fetch error. [Meta content-publishing documentation](https://developers.facebook.com/docs/instagram-platform/content-publishing/) returned HTTP 429. No logged-in request, upload, or bypass was attempted. Therefore this run has not independently verified current Instagram media ceilings, cover upload/cropping, caption fields or AI-label controls. Use the requested vertical master and cover as editorial preparation; keep these platform details explicitly pending current official/account verification. Do not cite a third-party spec as an official requirement. No derivative is required solely because a documentation request failed.

Editorial cover guidance for all platforms: keep a short headline and main diagram centrally legible, test the supplied artwork at small sizes, and inspect cropping in the actual upload preview. Exact UI overlays and profile crops can vary. Titles, sparse hashtags and discussion questions are editorial recommendations, not requirements or performance guarantees.

## Review status

These notes describe documentation checks, not successful uploads. Audible listening is still an unresolved acceptance gate in this session; it does not prevent preparation of technically verified review candidates and complete publishing drafts. Do not mark a candidate approved until all required reviews have actually occurred.
