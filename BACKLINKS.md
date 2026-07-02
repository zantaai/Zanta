# Zanta AI Backlink Ledger

This file is the working ledger for public Zanta AI mentions that may be added to the main README after they are live and useful for discovery.

## Update Workflow

1. Confirm the public page is reachable.
2. Check whether the page is a real public profile, review page, article, or directory listing.
3. Add stable, reader-friendly anchor text to `README.md`.
4. Keep pending or broken pages in this ledger until they return a usable public URL.
5. Commit locally, then push with a GitHub account that has write access to `zantaai/Zanta`.

Useful local commands:

```bash
git -C /Users/andong/workspace/mksaas/zanta-github-readme pull --ff-only
git -C /Users/andong/workspace/mksaas/zanta-github-readme status
git -C /Users/andong/workspace/mksaas/zanta-github-readme add README.md BACKLINKS.md
git -C /Users/andong/workspace/mksaas/zanta-github-readme commit -m "Record Zanta AI backlink updates"
git -C /Users/andong/workspace/mksaas/zanta-github-readme push origin main
```

## Confirmed Public Pages

| Page | URL | Status checked |
| --- | --- | --- |
| Zanta AI profile on about.me | https://about.me/zanta | 200 on 2026-06-29 |
| Zanta AI on Linktree | https://linktr.ee/trytrycc | 200 on 2026-06-29 |
| Zanta AI Bio Sites profile | https://bio.site/zantaai | 200 on 2026-06-29 |
| Zanta AI reviews on ProvenExpert | https://www.provenexpert.com/en-us/zanta/ | 200 on 2026-06-29 |
| Zanta AI on SaaSHub | https://www.saashub.com/zanta-ai | 200 on 2026-06-29 |
| Teletype article: How to Build a Fast AI Image Workflow with Zanta AI and Nano Banana | https://teletype.in/@zantaai/Vr1I0pOIbFH | 200 on 2026-07-02; Zanta anchors visible in HTML |
| Velog article: Designing a Browser-Based AI Media Workflow | https://velog.io/@zantaai/Designing-a-Browser-Based-AI-Media-Workflow | 200 on 2026-07-02; 8 Zanta anchors visible in HTML |
| Medium article: A Practical AI Image Workflow for Product Visuals and Short Videos | https://medium.com/@trytrydotcc/a-practical-ai-image-workflow-for-product-visuals-and-short-videos-7b15c25fffdc | Browser-verified live on 2026-07-03; command-line check returned Cloudflare 403; 6 Zanta anchors visible in Chrome |

## Protected Or Browser-Verified Pages

These pages may block command-line checks but can still be valid public pages in a browser.

| Page | URL | Current note |
| --- | --- | --- |
| Zanta AI company profile on Crunchbase | https://www.crunchbase.com/organization/zanta-ai | `curl` returned 403 on 2026-06-29; keep in README only if browser-visible. |
| Zanta AI reviews on Trustpilot | https://www.trustpilot.com/review/zanta.ai | `curl` returned 403 on 2026-06-29; browser-visible review page was previously recorded. |
| Zanta AI reviews on G2 | https://www.g2.com/products/zanta-ai/reviews | `curl` returned 403 on 2026-06-29; G2 profile was approved in browser flow. |

## Pending Recheck

| Page | URL | Status | Next action |
| --- | --- | --- | --- |
| Hashnode article: How to Build a Fast AI Image Workflow with Zanta AI and Nano Banana | https://zanta.hashnode.dev/how-to-build-a-fast-ai-image-workflow-with-zanta-ai-and-nano-banana | Editor says Published, but public page returned 404 on 2026-06-29. | Reopen the Hashnode edit page, click View post, and add to README only after public URL returns 200. |
| Mssg.me Zanta page | https://zanta.mssg.me/ | Returned 404 on 2026-06-29. | Recheck the page builder publish state before adding to README. |

## Hashnode Article Details

Edit URL: https://hashnode.com/edit/cmqz24au800000ahq74lmamo2

The editor currently contains these Zanta AI anchors:

- Zanta AI: https://zanta.ai/
- AI image generator: https://zanta.ai/ai-image
- Nano Banana AI image generator: https://zanta.ai/image/nano-banana
- background remover: https://zanta.ai/ai-tools/background-remover
- image upscaler: https://zanta.ai/ai-tools/image-upscaler
- image to prompt tool: https://zanta.ai/ai-tools/image-to-prompt
- AI video generator: https://zanta.ai/ai-video

Do not treat this Hashnode article as a live backlink until the public URL is no longer a 404.

## Teletype Article Details

Public URL: https://teletype.in/@zantaai/Vr1I0pOIbFH

The public Teletype page returned `200` on 2026-07-02. The page source includes the article title, canonical URL, `article:published_time=2026-07-02T10:25:43.916Z`, and `allow_indexing: true`.

Verified Zanta AI anchors:

- browser-based AI image and video studio: https://zanta.ai/
- AI image generator: https://zanta.ai/ai-image
- Nano Banana AI image generator: https://zanta.ai/image/nano-banana
- AI video generator: https://zanta.ai/ai-video
- background remover: https://zanta.ai/ai-tools/background-remover
- image upscaler: https://zanta.ai/ai-tools/image-upscaler
- image to prompt tool: https://zanta.ai/ai-tools/image-to-prompt

The current article does not include the GPT Image 2 page. Add that later only if it fits the article naturally.

## Velog Article Details

Public URL: https://velog.io/@zantaai/Designing-a-Browser-Based-AI-Media-Workflow

The public Velog page returned `200` on 2026-07-02. The page source includes the article title, canonical URL, and all target Zanta AI anchors.

Verified Zanta AI anchors:

- Zanta AI: https://zanta.ai/
- AI image generator: https://zanta.ai/ai-image
- Nano Banana AI image generator: https://zanta.ai/image/nano-banana
- GPT Image 2 AI image generator: https://zanta.ai/image/gpt-image-2
- AI video generator: https://zanta.ai/ai-video
- background remover: https://zanta.ai/ai-tools/background-remover
- image upscaler: https://zanta.ai/ai-tools/image-upscaler
- image to prompt tool: https://zanta.ai/ai-tools/image-to-prompt

The Zanta anchors are visible in the command-line HTML response and do not declare `rel`.

## Medium Article Details

Public URL: https://medium.com/@trytrydotcc/a-practical-ai-image-workflow-for-product-visuals-and-short-videos-7b15c25fffdc

Published from Medium draft `https://medium.com/p/7b15c25fffdc/edit` on 2026-07-03. Chrome showed the live article title, author `trytrycc`, publish time `Just now`, and the success message `Your story has been published and sent!`.

Command-line `curl -I -L` returned Cloudflare 403 on 2026-07-03, so this page should be treated as browser-verified rather than command-line-verified.

Verified Zanta AI anchors in Chrome:

- Zanta AI: https://zanta.ai/ (`rel="noopener ugc nofollow"`)
- AI image generator: https://zanta.ai/ai-image (`rel="noopener ugc nofollow"`)
- AI video generator: https://zanta.ai/ai-video (`rel="noopener ugc nofollow"`)
- background remover: https://zanta.ai/ai-tools/background-remover (`rel="noopener ugc nofollow"`)
- image upscaler: https://zanta.ai/ai-tools/image-upscaler (`rel="noopener ugc nofollow"`)
- image to prompt tool: https://zanta.ai/ai-tools/image-to-prompt (`rel="noopener ugc nofollow"`)
