# Problem Statement

## Who is affected?
- People who watch news-style videos on TikTok and may share them.
- Fact-checkers and moderators who must check videos by hand.
- The public, who are exposed to false health and political claims.

## What exactly is going wrong?
A short video combines speech, images, captions and music in 30 to 60 seconds and usually shows no source. Viewers cannot easily judge whether the claim is true. Fact-checkers can only review a small share of videos, and a false clip can spread long before it is checked.

## Why does it matter?
False health and political videos can change what people believe and do, for example about vaccines or elections. Late corrections rarely reach everyone who saw the original clip.

## Evidence
In September 2022, NewsGuard reviewed 540 TikTok search results on news topics (health, elections, the war in Ukraine) and found false or misleading claims in 105 of them, which is 19.4% (ABC7 New York, 2022). Researchers also describe fake news on short-video platforms as hard to detect, because a video carries several types of information at once (Qi et al., 2023).

## Problem statement (3 to 5 sentences)
People who get news from TikTok find it hard to tell whether a news video is true, because a 30-second clip mixes speech, images and on-screen text and usually shows no source. Fact-checkers review videos by hand, which is slow compared with how fast a clip can spread, so false claims often reach many viewers before anyone checks them. In a 2022 audit, NewsGuard found false or misleading claims in 105 of 540 TikTok search results (19.4%) on topics such as vaccines and elections. This matters because misleading health and political videos can change what people believe and do.

## Users and stakeholders
| Group | Role |
|-------|------|
| TikTok viewers | Main users. Want a quick check before they trust or share a video. |
| Fact-checkers and moderators | Main users. Want to find the videos most worth checking first. |
| Supervisor / examiners | Review the project. |
| Video creators | Affected stakeholders. May be wrongly flagged if the model is wrong. |

## Scope
**In scope**
- MP4 video files uploaded by the user (up to 3 minutes).
- Spoken English in the video (Malay as a possible extension).
- A Fake / Real prediction with a confidence score.
- Showing the transcript so the user can see what the prediction was based on.

**Out of scope**
- Downloading or scraping videos from TikTok at scale.
- Live streams, photo posts and videos without speech or visible text.
- Detecting edited or AI-generated footage (deepfakes). This project checks the claim, not the pixels.
- A final legal or editorial ruling on truth. The output is a warning, not a verdict.
- A mobile app or a TikTok plug-in.

## References
- ABC7 New York. (2022, September 20). *Nearly 20% of TikTok search results yield videos with misinformation, report says.* https://abc7ny.com/post/tiktok-misinformation-search-result-newsguard/12241564/
- Qi, P., Bu, Y., Cao, J., Ji, W., Shui, R., Xiao, J., Wang, D., & Chua, T.-S. (2023). FakeSV: A multimodal benchmark with rich social context for fake news detection on short video platforms. *Proceedings of the AAAI Conference on Artificial Intelligence, 37*(12), 14444-14452. https://doi.org/10.1609/aaai.v37i12.26689