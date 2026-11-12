# Awesome AI Video Models

**The open price index for AI video generation APIs.** Every model, every provider that hosts it, every resolution — priced per second, compared side by side.

[**🔎 Live price index**](https://videorouter.sh/pricing-index?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=top) · [**🚀 Get a free API key**](https://videorouter.sh/signup?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=top) · [**📘 Docs**](https://videorouter.sh/docs/quickstart?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=top) · [**🎬 Browse all models**](https://videorouter.sh/models?out=video&utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=top)

> 141 video models · 36 API providers · 777 price points · updated **2026-11-11**

The same video model is often sold by many API providers at very different prices — the same checkpoint can cost 3–5× more on one host than another. This repo tracks those differences in open, machine-readable data so you can pick a provider with numbers, not guesses.

## Biggest price gaps right now

Cheapest provider vs. the Fal list price for the same model and resolution (when Fal doesn't list that tier, vs. the priciest provider). *Via VideoRouter* includes the 2.5% platform fee, so the saving is net. † Higgsfield's own list price for the same model and resolution, shown for reference (not available through VideoRouter, never counted as the cheapest host).

| Model | Tier | Cheapest provider | List $/s | Via VideoRouter $/s | Baseline $/s | Higgsfield $/s † | Saving |
|---|---|---|---:|---:|---:|---:|---:|
| [seedance-2.5](models/bytedance__seedance-2.5.md) | 720p | SoCheap-Overseas | $0.137 | $0.1404 | $0.473 (Fal) | $0.2647 | **70.3%** |
| [seedance-2.0](models/bytedance__seedance-2.0.md) | 720p | SoCheap-Overseas | $0.0896 | $0.0918 | $0.3034 (Fal) | $0.1735 | **69.7%** |
| [wan-3.0](models/alibaba__wan-3.0.md) | 480p | Replicate | $0.025 | $0.0256 | $0.05 (Fal) | $0.0375 | **48.8%** |
| [gemini-omni-flash](models/google__gemini-omni-flash.md) | any | Google | $0.1 | $0.1025 | $0.13 (Fal) | – | **21.2%** |
| [minimax/h3](models/minimax__h3.md) | 1080p | Atlas Cloud | $0.08 | $0.082 | $0.16 (WaveSpeedAI) | – | **48.8%** |
| [happyhorse-1.1](models/alibaba__happyhorse-1.1.md) | 1080p | Pika | $0.126 | $0.1291 | $0.213 (OpenRouter) | – | **39.4%** |
| [grok-imagine-video](models/xai__grok-imagine-video.md) | 720p | WaveSpeedAI | $0.05 | $0.0512 | $0.7 (xAI) | – | **92.7%** |
| [grok-imagine-video-1.5](models/xai__grok-imagine-video-1.5.md) | 480p | OpenRouter | $0.08 | $0.082 | $0.8 (xAI) | – | **89.8%** |
| [seedance-2.0-mini](models/bytedance__seedance-2.0-mini.md) | 480p | Atlas Cloud | $0.0112 | $0.0115 | $0.0721 (Fal) | – | **84%** |
| [seedance-2.0-fast](models/bytedance__seedance-2.0-fast.md) | 1080p | Atlas Cloud | $0.1306 | $0.1339 | $0.5 (WaveSpeedAI) | – | **73.2%** |
| [luma-ray-3.2](models/luma__luma-ray-3.2.md) | 540p | Luma | $0.03 | $0.0307 | $0.1 (SandBase) | – | **69.2%** |
| [ltx-2.3-pro](models/lightricks__ltx-2.3-pro.md) | 2160p | MachGen | $0.1 | $0.1025 | $0.32 (SandBase) | – | **68%** |
| [pixverse-v6-max](models/pixverse__pixverse-v6-max.md) | 360p | Atlas Cloud | $0.024 | $0.0246 | $0.06 (Replicate) | – | **59%** |
| [vidu-q3](models/shengshu__vidu-q3.md) | 540p | Runware | $0.0293 | $0.03 | $0.07 (SandBase) | – | **57.2%** |
| [kling-v3](models/kuaishou__kling-v3.md) | 720p | SandBase | $0.0588 | $0.0603 | $0.14 (OpenRouter) | $0.0714 | **57%** |

> **Prices change every week.** This repo is a snapshot — the always-current, sortable version is the [VideoRouter Price Index](https://videorouter.sh/pricing-index?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=gaps) ([JSON](https://videorouter.sh/pricing-index.json?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=gaps) · [CSV](https://videorouter.sh/pricing-index.csv?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=gaps)). ⭐ **Star this repo** to follow updates.

## All models

| Model | Creator | Providers | Tiers | Cheapest (any tier) |
|---|---|---:|---|---:|
| [happy-horse](models/alibaba__happy-horse.md) | Alibaba | 1 | 720p, 1080p | $0.14/s |
| [happyhorse-1.0](models/alibaba__happyhorse-1.0.md) | Alibaba | 3 | 720p, 1080p | $0.098/s |
| [happyhorse-1.0-i2v](models/alibaba__happyhorse-1.0-i2v.md) | Alibaba | 1 | 720p, 1080p | $0.14/s |
| [happyhorse-1.0-r2v](models/alibaba__happyhorse-1.0-r2v.md) | Alibaba | 1 | 720p, 1080p | $0.14/s |
| [happyhorse-1.0-t2v](models/alibaba__happyhorse-1.0-t2v.md) | Alibaba | 1 | 720p, 1080p | $0.14/s |
| [happyhorse-1.1](models/alibaba__happyhorse-1.1.md) | Alibaba | 5 | 480p, 720p, 1080p | $0.07/s |
| [happyhorse-1.1-i2v](models/alibaba__happyhorse-1.1-i2v.md) | Alibaba | 1 | 720p, 1080p | $0.14/s |
| [happyhorse-1.1-r2v](models/alibaba__happyhorse-1.1-r2v.md) | Alibaba | 1 | 720p, 1080p | $0.14/s |
| [happyhorse-1.1-t2v](models/alibaba__happyhorse-1.1-t2v.md) | Alibaba | 1 | 720p, 1080p | $0.14/s |
| [wan-2.2-a14b](models/alibaba__wan-2.2-a14b.md) | Alibaba | 1 | 480p, 720p | $0.018/s |
| [wan-2.2-animate-mix](models/alibaba__wan-2.2-animate-mix.md) | Alibaba | 1 | pro, std | $0.126/s |
| [wan-2.2-animate-move](models/alibaba__wan-2.2-animate-move.md) | Alibaba | 1 | pro, std | $0.084/s |
| [wan-2.5-extend](models/alibaba__wan-2.5-extend.md) | Alibaba | 1 | 480p, 720p, 1080p | $0.0525/s |
| [wan-2.7-i2v](models/alibaba__wan-2.7-i2v.md) | Alibaba | 1 | any | $0.02/s |
| [wan-2.7-image](models/alibaba__wan-2.7-image.md) | Alibaba | 1 | 720p, 1080p | $0.1/s |
| [wan-2.7-pro](models/alibaba__wan-2.7-pro.md) | Alibaba | 1 | 1080p, 2k, 2160p | $0.14/s |
| [wan-2.7-r2v](models/alibaba__wan-2.7-r2v.md) | Alibaba | 1 | any | $0.02/s |
| [wan-2.7-t2v](models/alibaba__wan-2.7-t2v.md) | Alibaba | 1 | any | $0.02/s |
| [wan-25-preview](models/alibaba__wan-25-preview.md) | Alibaba | 1 | 480p, 720p, 1080p | $0.05/s |
| [wan-3.0](models/alibaba__wan-3.0.md) | Alibaba | 12 | 480p … 4k-esr | $0.025/s |
| [wan-3.0-prime](models/alibaba__wan-3.0-prime.md) | Alibaba | 8 | 480p … 4k-esr | $0.0408/s |
| [Wan2.2-I2V-A14B](models/Wan-AI__Wan2.2-I2V-A14B.md) | Alibaba | 1 | any | $0.0573/s |
| [Wan2.2-T2V-A14B](models/Wan-AI__Wan2.2-T2V-A14B.md) | Alibaba | 1 | any | $0.0573/s |
| [video-upscaler](models/atlas-cloud__video-upscaler.md) | Atlas Cloud | 1 | – | varies by input clip |
| [flux-3](models/black-forest-labs__flux-3.md) | Black Forest Labs | 6 | 720p, 1080p | $0.17/s |
| [flux-3-edit-video](models/black-forest-labs__flux-3-edit-video.md) | Black Forest Labs | 4 | any | $0.03/s |
| [flux-3-extend](models/black-forest-labs__flux-3-extend.md) | Black Forest Labs | 4 | 720p, 1080p | $0.41/s |
| [flux-video-upscale](models/black-forest-labs__flux-video-upscale.md) | Black Forest Labs | 3 | – | varies by input clip |
| [flux-video-upscale-creative](models/black-forest-labs__flux-video-upscale-creative.md) | Black Forest Labs | 1 | – | varies by input clip |
| [higgs-avatar](models/boson__higgs-avatar.md) | Boson AI | 1 | 480x640, 640x480, 640x640 | $0.0012/s |
| [byteplus-video-upscaler](models/bytedance__byteplus-video-upscaler.md) | ByteDance | 3 | – | varies by input clip |
| [omnihuman-v2](models/bytedance__omnihuman-v2.md) | ByteDance | 2 | any | $0.0896/s |
| [seedance-1.0-pro-quality](models/bytedance__doubao-seedance-1-0-pro-quality.md) | ByteDance | 1 | 480p, 720p, 1080p | $0.0226/s |
| [seedance-1.5-pro](models/bytedance__seedance-1-5-pro.md) | ByteDance | 2 | 480p, 720p, 1080p | $0.0115/s |
| [seedance-2.0](models/bytedance__seedance-2.0.md) | ByteDance | 11 | 480p … 2160p | $0.0592/s |
| [seedance-2.0-fast](models/bytedance__seedance-2.0-fast.md) | ByteDance | 9 | 480p … any | $0.027/s |
| [seedance-2.0-mini](models/bytedance__seedance-2.0-mini.md) | ByteDance | 8 | 480p … 2160p | $0.0112/s |
| [seedance-2.5](models/bytedance__seedance-2.5.md) | ByteDance | 12 | 480p … 4k-esr | $0.0862/s |
| [seedance-2.5-talking-avatar](models/bytedance__seedance-2.5-talking-avatar.md) | ByteDance | 1 | 480p, 720p | $0.22/s |
| [seedvr2-upscale-video](models/bytedance__seedvr2-upscale-video.md) | ByteDance | 1 | – | varies by input clip |
| [crystal-video-upscale](models/clarity-ai__crystal-video-upscale.md) | Clarity AI | 1 | – | varies by input clip |
| [boreal](models/creatify__boreal.md) | Creatify | 1 | 720p, 1080p, 2k | $0.01/s |
| [hyperswap-video-faceswap](models/segmind__hyperswap-video-faceswap.md) | FaceFusion Labs | 1 | any | $0.0067/s |
| [flux-3-max](models/fal__flux-3-max.md) | Fal | 1 | 720p, 1080p | $0.17/s |
| [gemini-omni-1.1-flash](models/google__gemini-omni-1.1-flash.md) | Google | 3 | 360p … any | $0.03/s |
| [gemini-omni-1.2-flash](models/google__gemini-omni-1.2-flash.md) | Google | 4 | 360p, 720p, 1080p, 2160p | $0.023/s |
| [gemini-omni-flash](models/google__gemini-omni-flash.md) | Google | 4 | any | $0.1/s |
| [veo-3](models/google__veo-3.md) | Google | 1 | any | $0.2/s |
| [veo-3-fast](models/google__veo-3-fast.md) | Google | 1 | any | $0.1/s |
| [veo-3.1](models/google__veo-3.1.md) | Google | 7 | 720p, 1080p, 2160p, any | $0.2/s |
| [veo-3.1-extend](models/google__veo-3.1-extend.md) | Google | 1 | 720p, 1080p | $0.4/s |
| [veo-3.1-fast](models/google__veo-3.1-fast.md) | Google | 7 | 720p, 1080p, 2160p, any | $0.08/s |
| [veo-3.1-fast-extend](models/google__veo-3.1-fast-extend.md) | Google | 1 | 720p, 1080p | $0.15/s |
| [veo-3.1-lite](models/google__veo-3.1-lite.md) | Google | 4 | 720p, 1080p | $0.03/s |
| [HeyGen Avatar IV](models/heygen__avatar-iv.md) | HeyGen | 1 | 720p, 1080p, 2160p | $0.05/s |
| [heygen-avatar4-image-to-video](models/heygen__heygen-avatar4-image-to-video.md) | HeyGen | 1 | any | $0.1/s |
| [heygen-v3-lipsync-precision](models/heygen__heygen-v3-lipsync-precision.md) | HeyGen | 1 | any | $0.1/s |
| [heygen-v3-lipsync-speed](models/heygen__heygen-v3-lipsync-speed.md) | HeyGen | 1 | any | $0.05/s |
| [heygen-video-1](models/heygen__heygen-video-1.md) | HeyGen | 4 | 480p, 768p, 1080p, 2k | $0.02/s |
| [kling-ai-avatar-v2-pro](models/kuaishou__kling-ai-avatar-v2-pro.md) | Kuaishou | 2 | any | $0.112/s |
| [kling-ai-avatar-v2-standard](models/kuaishou__kling-ai-avatar-v2-standard.md) | Kuaishou | 2 | any | $0.056/s |
| [kling-motion-control](models/kuaishou__kling-motion-control.md) | Kuaishou | 2 | pro, std | $0.1071/s |
| [kling-o3](models/kuaishou__kling-o3.md) | Kuaishou | 3 | 720p, 1080p, 2160p, any | $0.0588/s |
| [kling-v2.6](models/kuaishou__kling-v2.6.md) | Kuaishou | 2 | 1080p, any, pro, std | $0.042/s |
| [kling-v2.6-motion-control](models/kuaishou__kling-v2.6-motion-control.md) | Kuaishou | 1 | pro, std | $0.0595/s |
| [kling-v3](models/kuaishou__kling-v3.md) | Kuaishou | 8 | 720p, 1080p, 2160p, any | $0.0588/s |
| [kling-v3-omni-video](models/kuaishou__kling-v3-omni-video.md) | Kuaishou | 1 | 2160p, pro, standard | $0.168/s |
| [kling-v3-turbo](models/kuaishou__kling-v3-turbo.md) | Kuaishou | 3 | 720p, 1080p, any | $0.09/s |
| [kling-v3-video](models/kuaishou__kling-v3-video.md) | Kuaishou | 1 | 2160p, pro, standard | $0.168/s |
| [kling-v4.0](models/kuaishou__kling-v4.0.md) | Kuaishou | 8 | 720p … 4k-esr | $0.1335/s |
| [kling-v4.0-edit](models/kuaishou__kling-v4.0-edit.md) | Kuaishou | 5 | 720p, 1080p | $0.1598/s |
| [kling-v4.0-extend](models/kuaishou__kling-v4.0-extend.md) | Kuaishou | 1 | 720p, 1080p | $0.157/s |
| [kling-v4.0-flash](models/kuaishou__kling-v4.0-flash.md) | Kuaishou | 4 | 720p | $0.0857/s |
| [kling-v4.0-flash-edit](models/kuaishou__kling-v4.0-flash-edit.md) | Kuaishou | 3 | 720p | $0.1143/s |
| [kling-video-o1](models/kuaishou__kling-video-o1.md) | Kuaishou | 1 | any | $0.112/s |
| [ltx-2-fast](models/lightricks__ltx-2-fast.md) | Lightricks | 1 | any | $0.04/s |
| [ltx-2-pro](models/lightricks__ltx-2-pro.md) | Lightricks | 1 | any | $0.06/s |
| [ltx-2.3](models/lightricks__ltx-2.3.md) | Lightricks | 1 | 480p, 720p, 1080p | $0.02/s |
| [ltx-2.3-fast](models/lightricks__ltx-2.3-fast.md) | Lightricks | 1 | 1080p, 1440p, 2160p | $0.06/s |
| [ltx-2.3-pro](models/lightricks__ltx-2.3-pro.md) | Lightricks | 2 | 1080p, 1440p, 2160p | $0.03/s |
| [ltx-2.5](models/lightricks__ltx-2.5.md) | Lightricks | 1 | 720p, 1080p, 2k, 2160p | $0.1/s |
| [ltx-2.5-fast](models/lightricks__ltx-2.5-fast.md) | Lightricks | 2 | 720p, 1080p, 1440p, 2160p | $0.09/s |
| [ltx-2.5-pro](models/lightricks__ltx-2.5-pro.md) | Lightricks | 2 | 720p, 1080p | $0.12/s |
| [luma-ray-3.2](models/luma__luma-ray-3.2.md) | Luma | 2 | 540p, 720p, 1080p | $0.03/s |
| [infinitetalk](models/meigen-ai__infinitetalk.md) | MeiGen-AI | 1 | 480p, 720p | $0.03/s |
| [infinitetalk-fast](models/meigen-ai__infinitetalk-fast.md) | MeiGen-AI | 1 | any | $0.015/s |
| [longcat-avatar-1.5](models/meituan__longcat-avatar-1.5.md) | Meituan | 1 | 480p, 720p | $0.04/s |
| [h3-max](models/minimax__h3-max.md) | MiniMax | 4 | 480p … 4k-sr | $0.04/s |
| [h3-max-camera-controls](models/minimax__h3-max-camera-controls.md) | MiniMax | 1 | 480p, 768p, 1080p | $0.05/s |
| [h3-max-lipsync](models/minimax__h3-max-lipsync.md) | MiniMax | 1 | 480p, 768p, 1080p, 2k | $0.05/s |
| [hailuo-2.3](models/minimax__hailuo-2.3.md) | MiniMax | 1 | any | $0.0817/s |
| [hailuo-2.3-standard](models/minimax__hailuo-2.3-standard.md) | MiniMax | 1 | any | $0.0467/s |
| [hailuo-3](models/minimax__hailuo-3.md) | MiniMax | 1 | any | $0.13/s |
| [hailuo-3-max](models/minimax__hailuo-3-max.md) | MiniMax | 1 | 480p, 768p | $0.05/s |
| [minimax/h3](models/minimax__h3.md) | MiniMax | 13 | 480p … 4k-esr | $0.038/s |
| [minimax/h3-fast](models/minimax__h3-fast.md) | MiniMax | 1 | any | $0.0437/s |
| [minimax/h3-max-turbo](models/minimax__h3-max-turbo.md) | MiniMax | 2 | 480p, 768p, 1080p | $0.025/s |
| [minimax/h3-turbo](models/minimax__minimax-h3-turbo.md) | MiniMax | 1 | 480p, 768p | $0.02/s |
| [minimax/hailuo-2.3-pro](models/minimax__hailuo-2.3-pro.md) | MiniMax | 1 | any | $0.0817/s |
| [pika-2.5](models/pika__pika-2.5.md) | Pika | 1 | 720p, 1080p | $0.04/s |
| [pika-h3-flex](models/pika__pika-h3-flex.md) | Pika | 1 | 480p … 2160p | $0.01/s |
| [pikadditions](models/pika__pikadditions.md) | Pika | 1 | any | $0.006/s |
| [Pixverse-6-T2V](models/Pixverse__Pixverse-6-T2V.md) | PixVerse | 1 | any | $0.045/s |
| [pixverse-c1](models/pixverse__pixverse-c1.md) | PixVerse | 1 | 360p, 540p, 720p, 1080p | $0.0246/s |
| [pixverse-v6](models/pixverse__pixverse-v6.md) | PixVerse | 3 | 360p, 540p, 720p, 1080p | $0.0204/s |
| [pixverse-v6-extend](models/pixverse__pixverse-v6-extend.md) | PixVerse | 1 | 360p, 540p, 720p, 1080p | $0.025/s |
| [pixverse-v6-max](models/pixverse__pixverse-v6-max.md) | PixVerse | 3 | 360p, 540p, 720p, 1080p | $0.024/s |
| [pruna-p-video-2-pro-avatar](models/pruna-ai__pruna-p-video-2-pro-avatar.md) | Pruna AI | 1 | 480p, 768p | $0.02/s |
| [p-video](models/prunaai__p-video.md) | PrunaAI | 2 | 720p, 1080p, any | $0.02/s |
| [p-video-2](models/prunaai__p-video-2.md) | PrunaAI | 1 | 720p, 1080p | $0.025/s |
| [p-video-2-draft](models/prunaai__p-video-2-draft.md) | PrunaAI | 1 | 720p, 1080p | $0.015/s |
| [p-video-2-pro](models/prunaai__p-video-2-pro.md) | PrunaAI | 5 | 480p … 2160p | $0.02/s |
| [p-video-2-pro-cost](models/prunaai__p-video-2-pro-cost.md) | PrunaAI | 5 | 480p … 2160p | $0.01/s |
| [p-video-2-pro-quality](models/prunaai__p-video-2-pro-quality.md) | PrunaAI | 5 | 480p … 2160p | $0.04/s |
| [p-video-draft](models/prunaai__p-video-draft.md) | PrunaAI | 1 | 720p, 1080p | $0.005/s |
| [aleph-2](models/runway__aleph-2.md) | Runway | 1 | any | $0.28/s |
| [gen-4.5](models/runway__gen-4.5.md) | Runway | 2 | any | $0.12/s |
| [s1-avatar-offline](models/vidu__s1-avatar-offline.md) | Shengshu | 1 | any | $0.005/s |
| [vidu-q3](models/shengshu__vidu-q3.md) | Shengshu | 3 | 360p, 540p, 720p, 1080p | $0.0293/s |
| [vidu-q3-pro](models/shengshu__vidu-q3-pro.md) | Shengshu | 2 | 540p, 720p, 1080p | $0.05/s |
| [vidu-q3-pro-fast](models/shengshu__vidu-q3-pro-fast.md) | Shengshu | 1 | 720p, 1080p | $0.118/s |
| [vidu-q3-turbo](models/shengshu__vidu-q3-turbo.md) | Shengshu | 3 | 360p, 540p, 720p, 1080p | $0.02/s |
| [skyreels-v3-talking-avatar](models/skywork-ai__skyreels-v3-talking-avatar.md) | Skywork AI | 1 | 480p, 720p | $0.03/s |
| [skyreels-v4](models/skywork-ai__skyreels-v4.md) | Skywork AI | 1 | 480p, 720p, 1080p | $0.11/s |
| [sync-lipsync](models/sync-labs__sync-lipsync.md) | Sync Labs | 1 | any | $0.0117/s |
| [sync-lipsync-react-1](models/sync-labs__sync-lipsync-react-1.md) | Sync Labs | 1 | any | $0.1667/s |
| [sync-lipsync-v2](models/sync-labs__sync-lipsync-v2.md) | Sync Labs | 1 | any | $0.05/s |
| [sync-lipsync-v2-pro](models/sync-labs__sync-lipsync-v2-pro.md) | Sync Labs | 1 | any | $0.0833/s |
| [sync-lipsync-v3](models/sync-labs__sync-lipsync-v3.md) | Sync Labs | 1 | any | $0.1333/s |
| [sync-lipsync-v3-image](models/sync-labs__sync-lipsync-v3-image.md) | Sync Labs | 1 | any | $0.1333/s |
| [tencent-video-upscaler](models/tencent__tencent-video-upscaler.md) | Tencent | 1 | – | varies by input clip |
| [topaz-upscale-video-creative](models/topaz-labs__topaz-upscale-video-creative.md) | Topaz Labs | 1 | – | varies by input clip |
| [topaz-upscale-video-generative](models/topaz-labs__topaz-upscale-video-generative.md) | Topaz Labs | 1 | – | varies by input clip |
| [topaz-upscale-video-precision](models/topaz-labs__topaz-upscale-video-precision.md) | Topaz Labs | 1 | – | varies by input clip |
| [veed-fabric-1.0](models/veed__veed-fabric-1.0.md) | VEED | 1 | 480p, 720p | $0.07/s |
| [veed-lipsync-v2](models/veed__veed-lipsync-v2.md) | VEED | 1 | any | $0.07/s |
| [grok-imagine-video](models/xai__grok-imagine-video.md) | xAI | 5 | 480p, 720p, 1080p | $0.05/s |
| [grok-imagine-video-1.5](models/xai__grok-imagine-video-1.5.md) | xAI | 5 | 480p, 720p, 1080p, any | $0.08/s |
| [grok-imagine-video-1.5-lite](models/xai__grok-imagine-video-1.5-lite.md) | xAI | 1 | 480p, 720p, 1080p | $0.02/s |
| [grok-imagine-video-edit](models/xai__grok-imagine-video-edit.md) | xAI | 1 | any | $0.08/s |
| [grok-imagine-video-extend](models/xai__grok-imagine-video-extend.md) | xAI | 1 | any | $0.08/s |

## Compare every host, model by model

Expand a model to see **every** provider's price for **every** resolution (USD per second, list price before platform fee; cheapest per resolution in bold).

<details><summary><b>Alibaba happy-horse</b> — 1 host, from $0.14/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Fal | $0.14 | $0.18 |

[Details](models/alibaba__happy-horse.md) · [**Call happy-horse via VideoRouter →**](https://videorouter.sh/video/alibaba/happy-horse?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba happyhorse-1.0</b> — 3 hosts, from $0.098/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Pika | **$0.098** | **$0.168** |
| MachGen | $0.1122 | $0.2244 |
| OpenRouter | $0.1647 | $0.2824 |

[Details](models/alibaba__happyhorse-1.0.md) · [**Call happyhorse-1.0 via VideoRouter →**](https://videorouter.sh/video/alibaba/happyhorse-1.0?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba happyhorse-1.0-i2v</b> — 1 host, from $0.14/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Together AI | $0.14 | $0.24 |

[Details](models/alibaba__happyhorse-1.0-i2v.md) · [**Call happyhorse-1.0-i2v via VideoRouter →**](https://videorouter.sh/video/alibaba/happyhorse-1.0-i2v?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba happyhorse-1.0-r2v</b> — 1 host, from $0.14/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Together AI | $0.14 | $0.24 |

[Details](models/alibaba__happyhorse-1.0-r2v.md) · [**Call happyhorse-1.0-r2v via VideoRouter →**](https://videorouter.sh/video/alibaba/happyhorse-1.0-r2v?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba happyhorse-1.0-t2v</b> — 1 host, from $0.14/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Together AI | $0.14 | $0.24 |

[Details](models/alibaba__happyhorse-1.0-t2v.md) · [**Call happyhorse-1.0-t2v via VideoRouter →**](https://videorouter.sh/video/alibaba/happyhorse-1.0-t2v?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba happyhorse-1.1</b> — 5 hosts, from $0.07/s</summary>

| Provider | 480p | 720p | 1080p |
|---|---:|---:|---:|
| Alibaba | $0.07 | $0.14 | $0.18 |
| Pika | – | **$0.098** | **$0.126** |
| MachGen | – | $0.1122 | $0.1445 |
| Replicate | – | $0.14 | $0.18 |
| OpenRouter | – | $0.1647 | $0.213 |

[Details](models/alibaba__happyhorse-1.1.md) · [**Call happyhorse-1.1 via VideoRouter →**](https://videorouter.sh/video/alibaba/happyhorse-1.1?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba happyhorse-1.1-i2v</b> — 1 host, from $0.14/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Together AI | $0.14 | $0.18 |

[Details](models/alibaba__happyhorse-1.1-i2v.md) · [**Call happyhorse-1.1-i2v via VideoRouter →**](https://videorouter.sh/video/alibaba/happyhorse-1.1-i2v?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba happyhorse-1.1-r2v</b> — 1 host, from $0.14/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Together AI | $0.14 | $0.18 |

[Details](models/alibaba__happyhorse-1.1-r2v.md) · [**Call happyhorse-1.1-r2v via VideoRouter →**](https://videorouter.sh/video/alibaba/happyhorse-1.1-r2v?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba happyhorse-1.1-t2v</b> — 1 host, from $0.14/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Together AI | $0.14 | $0.18 |

[Details](models/alibaba__happyhorse-1.1-t2v.md) · [**Call happyhorse-1.1-t2v via VideoRouter →**](https://videorouter.sh/video/alibaba/happyhorse-1.1-t2v?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba wan-2.2-a14b</b> — 1 host, from $0.018/s</summary>

| Provider | 480p | 720p |
|---|---:|---:|
| MachGen | $0.018 | $0.036 |

[Details](models/alibaba__wan-2.2-a14b.md) · [**Call wan-2.2-a14b via VideoRouter →**](https://videorouter.sh/video/alibaba/wan-2.2-a14b?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba wan-2.2-animate-mix</b> — 1 host, from $0.126/s</summary>

| Provider | pro | std |
|---|---:|---:|
| Atlas Cloud | $0.182 | $0.126 |

[Details](models/alibaba__wan-2.2-animate-mix.md) · [**Call wan-2.2-animate-mix via VideoRouter →**](https://videorouter.sh/video/alibaba/wan-2.2-animate-mix?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba wan-2.2-animate-move</b> — 1 host, from $0.084/s</summary>

| Provider | pro | std |
|---|---:|---:|
| Atlas Cloud | $0.126 | $0.084 |

[Details](models/alibaba__wan-2.2-animate-move.md) · [**Call wan-2.2-animate-move via VideoRouter →**](https://videorouter.sh/video/alibaba/wan-2.2-animate-move?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba wan-2.5-extend</b> — 1 host, from $0.0525/s</summary>

| Provider | 480p | 720p | 1080p |
|---|---:|---:|---:|
| Atlas Cloud | $0.0525 | $0.105 | $0.1575 |

[Details](models/alibaba__wan-2.5-extend.md) · [**Call wan-2.5-extend via VideoRouter →**](https://videorouter.sh/video/alibaba/wan-2.5-extend?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba wan-2.7-i2v</b> — 1 host, from $0.02/s</summary>

| Provider | any |
|---|---:|
| Together AI | $0.02 |

[Details](models/alibaba__wan-2.7-i2v.md) · [**Call wan-2.7-i2v via VideoRouter →**](https://videorouter.sh/video/alibaba/wan-2.7-i2v?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba wan-2.7-image</b> — 1 host, from $0.1/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| WaveSpeedAI | $0.1 | $0.15 |

[Details](models/alibaba__wan-2.7-image.md) · [**Call wan-2.7-image via VideoRouter →**](https://videorouter.sh/video/alibaba/wan-2.7-image?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba wan-2.7-pro</b> — 1 host, from $0.14/s</summary>

| Provider | 1080p | 2k | 2160p |
|---|---:|---:|---:|
| WaveSpeedAI | $0.14 | $0.15 | $0.17 |

[Details](models/alibaba__wan-2.7-pro.md) · [**Call wan-2.7-pro via VideoRouter →**](https://videorouter.sh/video/alibaba/wan-2.7-pro?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba wan-2.7-r2v</b> — 1 host, from $0.02/s</summary>

| Provider | any |
|---|---:|
| Together AI | $0.02 |

[Details](models/alibaba__wan-2.7-r2v.md) · [**Call wan-2.7-r2v via VideoRouter →**](https://videorouter.sh/video/alibaba/wan-2.7-r2v?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba wan-2.7-t2v</b> — 1 host, from $0.02/s</summary>

| Provider | any |
|---|---:|
| Together AI | $0.02 |

[Details](models/alibaba__wan-2.7-t2v.md) · [**Call wan-2.7-t2v via VideoRouter →**](https://videorouter.sh/video/alibaba/wan-2.7-t2v?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba wan-25-preview</b> — 1 host, from $0.05/s</summary>

| Provider | 480p | 720p | 1080p |
|---|---:|---:|---:|
| Fal | $0.05 | $0.1 | $0.15 |

[Details](models/alibaba__wan-25-preview.md) · [**Call wan-25-preview via VideoRouter →**](https://videorouter.sh/video/alibaba/wan-25-preview?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba wan-3.0</b> — 12 hosts, from $0.025/s</summary>

| Provider | 480p | 720p | 720p-esr | 1080p | 1080p-esr | 1440p | 1440p-esr | 2160p | 4k-esr |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Fal | $0.05 | $0.1 | – | $0.2 | – | – | – | – | – |
| Higgsfield † | $0.0375 | $0.075 | – | $0.15 | – | – | – | – | – |
| Replicate | **$0.025** | **$0.05** | – | **$0.1** | – | – | – | – | – |
| SandBase | $0.03 | $0.06 | – | $0.12 | – | – | – | – | – |
| TOAPIS | $0.03 | $0.06 | – | $0.12 | – | – | – | – | – |
| Pika | $0.0325 | $0.065 | – | $0.13 | – | – | – | – | – |
| Atlas Cloud | $0.04 | $0.08 | $0.064 | $0.16 | $0.128 | $0.16 | $0.2752 | $0.16 | $0.5917 |
| MuleRouter | $0.04 | $0.08 | – | $0.16 | – | – | – | – | – |
| MachGen | $0.0416 | $0.0816 | – | $0.1623 | – | – | – | – | – |
| Alibaba | $0.05 | $0.1 | – | $0.2 | – | – | – | – | – |
| WaveSpeedAI | $0.05 | $0.1 | – | $0.2 | – | – | – | – | – |
| OpenRouter | $0.1062 | $0.2125 | – | $0.425 | – | – | – | – | – |
| DeepInfra | – | – | – | $0.2 | – | – | – | – | – |

† Higgsfield is not available through VideoRouter — reference list price only, never counted as the cheapest host.

[Details](models/alibaba__wan-3.0.md) · [**Call wan-3.0 via VideoRouter →**](https://videorouter.sh/video/alibaba/wan-3.0?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba wan-3.0-prime</b> — 8 hosts, from $0.0408/s</summary>

| Provider | 480p | 720p | 720p-esr | 1080p | 1080p-esr | 1440p | 1440p-esr | 2160p | 4k-esr |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Fal | $0.068 | $0.14 | – | $0.28 | – | – | – | – | – |
| Higgsfield † | $0.051 | $0.105 | – | $0.21 | – | – | – | – | – |
| SandBase | **$0.0408** | **$0.084** | – | **$0.168** | – | – | – | – | – |
| Pika | $0.051 | $0.105 | – | $0.21 | – | – | – | – | – |
| MuleRouter | $0.0578 | $0.119 | – | $0.238 | – | – | – | – | – |
| Atlas Cloud | $0.0612 | $0.126 | $0.1008 | $0.252 | $0.2016 | $0.252 | $0.4334 | $0.252 | $0.9319 |
| Alibaba | $0.068 | $0.14 | – | $0.28 | – | – | – | – | – |
| WaveSpeedAI | $0.075 | $0.15 | – | $0.3 | – | – | – | – | – |
| OpenRouter | $0.17 | $0.35 | – | $0.7 | – | – | – | – | – |

† Higgsfield is not available through VideoRouter — reference list price only, never counted as the cheapest host.

[Details](models/alibaba__wan-3.0-prime.md) · [**Call wan-3.0-prime via VideoRouter →**](https://videorouter.sh/video/alibaba/wan-3.0-prime?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba Wan2.2-I2V-A14B</b> — 1 host, from $0.0573/s</summary>

| Provider | any |
|---|---:|
| SiliconFlow | $0.0573 |

[Details](models/Wan-AI__Wan2.2-I2V-A14B.md) · [**Call Wan2.2-I2V-A14B via VideoRouter →**](https://videorouter.sh/video/Wan-AI/Wan2.2-I2V-A14B?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Alibaba Wan2.2-T2V-A14B</b> — 1 host, from $0.0573/s</summary>

| Provider | any |
|---|---:|
| SiliconFlow | $0.0573 |

[Details](models/Wan-AI__Wan2.2-T2V-A14B.md) · [**Call Wan2.2-T2V-A14B via VideoRouter →**](https://videorouter.sh/video/Wan-AI/Wan2.2-T2V-A14B?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Black Forest Labs flux-3</b> — 6 hosts, from $0.17/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Black Forest Labs | **$0.17** | **$0.29** |
| OpenRouter | **$0.17** | **$0.29** |
| Replicate | **$0.17** | **$0.29** |
| Together AI | **$0.17** | **$0.29** |
| WaveSpeedAI | **$0.17** | **$0.29** |
| Atlas Cloud | $0.187 | $0.319 |

[Details](models/black-forest-labs__flux-3.md) · [**Call flux-3 via VideoRouter →**](https://videorouter.sh/video/black-forest-labs/flux-3?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Black Forest Labs flux-3-edit-video</b> — 4 hosts, from $0.03/s</summary>

| Provider | any |
|---|---:|
| Fal | **$0.03** |
| Black Forest Labs | **$0.03** |
| WaveSpeedAI | **$0.03** |
| Atlas Cloud | $0.033 |

[Details](models/black-forest-labs__flux-3-edit-video.md) · [**Call flux-3-edit-video via VideoRouter →**](https://videorouter.sh/video/black-forest-labs/flux-3-edit-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Black Forest Labs flux-3-extend</b> — 4 hosts, from $0.41/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Fal | **$0.41** | **$0.53** |
| Black Forest Labs | **$0.41** | **$0.53** |
| WaveSpeedAI | **$0.41** | **$0.53** |
| Atlas Cloud | $0.451 | $0.583 |

[Details](models/black-forest-labs__flux-3-extend.md) · [**Call flux-3-extend via VideoRouter →**](https://videorouter.sh/video/black-forest-labs/flux-3-extend?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Boson AI higgs-avatar</b> — 1 host, from $0.0012/s</summary>

| Provider | 480x640 | 640x480 | 640x640 |
|---|---:|---:|---:|
| Boson AI | $0.0012 | $0.0012 | $0.0015 |

[Details](models/boson__higgs-avatar.md) · [**Call higgs-avatar via VideoRouter →**](https://videorouter.sh/video/boson/higgs-avatar?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>ByteDance omnihuman-v2</b> — 2 hosts, from $0.0896/s</summary>

| Provider | any |
|---|---:|
| Fal | $0.105 |
| Atlas Cloud | **$0.0896** |

[Details](models/bytedance__omnihuman-v2.md) · [**Call omnihuman-v2 via VideoRouter →**](https://videorouter.sh/video/bytedance/omnihuman-v2?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>ByteDance seedance-1.0-pro-quality</b> — 1 host, from $0.0226/s</summary>

| Provider | 480p | 720p | 1080p |
|---|---:|---:|---:|
| TOAPIS | $0.0226 | $0.0524 | $0.1137 |

[Details](models/bytedance__doubao-seedance-1-0-pro-quality.md) · [**Call seedance-1.0-pro-quality via VideoRouter →**](https://videorouter.sh/video/bytedance/doubao-seedance-1-0-pro-quality?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>ByteDance seedance-1.5-pro</b> — 2 hosts, from $0.0115/s</summary>

| Provider | 480p | 720p | 1080p |
|---|---:|---:|---:|
| OpenRouter | **$0.0115** | **$0.0259** | **$0.0583** |
| TOAPIS | $0.0124 | $0.027 | $0.0607 |

[Details](models/bytedance__seedance-1-5-pro.md) · [**Call seedance-1.5-pro via VideoRouter →**](https://videorouter.sh/video/bytedance/seedance-1-5-pro?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>ByteDance seedance-2.0</b> — 11 hosts, from $0.0592/s</summary>

| Provider | 480p | 720p | 720p-sr | 1080p | 1080p-sr | 1440p-sr | 2160p |
|---|---:|---:|---:|---:|---:|---:|---:|
| Fal | $0.1345 | $0.3034 | – | $0.682 | – | – | $1.5552 |
| Higgsfield † | $0.0804 | $0.1735 | – | $0.4293 | – | – | $0.8907 |
| SoCheap-Official | **$0.0592** | $0.1274 | – | $0.3201 | – | – | – |
| MachGen | $0.0598 | $0.1285 | – | $0.3181 | – | – | $0.661 |
| OpenSand | $0.0598 | $0.1285 | – | **$0.3181** | – | – | **$0.6065** |
| TOAPIS | $0.066 | $0.1419 | – | $0.3543 | – | – | $0.7684 |
| OpenRouter | $0.0673 | $0.1512 | – | $0.3742 | – | – | $0.7776 |
| Replicate | $0.08 | $0.18 | – | $0.45 | – | – | $1 |
| SoCheap-Overseas | – | **$0.0896** | – | – | – | – | – |
| Atlas Cloud | $0.09 | $0.1935 | $0.162 | $0.4355 | $0.3484 | $0.6193 | $1.241 |
| SandBase | $0.096 | $0.192 | – | $0.48 | – | – | $0.96 |
| WaveSpeedAI | $0.12 | $0.24 | – | $0.6 | – | – | $1.2 |

† Higgsfield is not available through VideoRouter — reference list price only, never counted as the cheapest host.

[Details](models/bytedance__seedance-2.0.md) · [**Call seedance-2.0 via VideoRouter →**](https://videorouter.sh/video/bytedance/seedance-2.0?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>ByteDance seedance-2.0-fast</b> — 9 hosts, from $0.027/s</summary>

| Provider | 480p | 720p | 720p-sr | 1080p | 1080p-sr | 1440p-sr | 2160p | any |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Fal | – | – | – | – | – | – | – | $0.2419 |
| Atlas Cloud | **$0.027** | **$0.0581** | $0.0486 | **$0.1306** | $0.1045 | $0.1858 | – | – |
| OpenRouter | $0.0404 | $0.0907 | – | – | – | – | – | – |
| TOAPIS | $0.0416 | $0.0895 | – | – | – | – | – | – |
| OpenSand | $0.0478 | $0.1028 | – | – | – | – | – | – |
| MachGen | $0.0478 | $0.1028 | – | – | – | – | – | – |
| Replicate | $0.07 | $0.15 | – | – | – | – | – | – |
| SandBase | $0.085 | $0.17 | – | – | – | – | – | – |
| WaveSpeedAI | $0.1 | $0.2 | – | $0.5 | – | – | $1 | – |

[Details](models/bytedance__seedance-2.0-fast.md) · [**Call seedance-2.0-fast via VideoRouter →**](https://videorouter.sh/video/bytedance/seedance-2.0-fast?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>ByteDance seedance-2.0-mini</b> — 8 hosts, from $0.0112/s</summary>

| Provider | 480p | 720p | 720p-sr | 1080p | 1080p-sr | 1440p-sr | 2160p |
|---|---:|---:|---:|---:|---:|---:|---:|
| Fal | $0.0721 | $0.1547 | – | – | – | – | – |
| Atlas Cloud | **$0.0112** | **$0.0242** | $0.0202 | – | $0.0435 | $0.0774 | – |
| TOAPIS | $0.019 | $0.0408 | – | – | – | – | – |
| MachGen | $0.0299 | $0.0643 | – | – | – | – | – |
| OpenSand | $0.0299 | $0.0643 | – | – | – | – | – |
| OpenRouter | $0.0336 | $0.0756 | – | – | – | – | – |
| SandBase | $0.054 | $0.108 | – | – | – | – | – |
| WaveSpeedAI | $0.06 | $0.12 | – | $0.3 | – | – | $0.6 |

[Details](models/bytedance__seedance-2.0-mini.md) · [**Call seedance-2.0-mini via VideoRouter →**](https://videorouter.sh/video/bytedance/seedance-2.0-mini?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>ByteDance seedance-2.5</b> — 12 hosts, from $0.0862/s</summary>

| Provider | 480p | 720p | 720p-esr | 720p-sr | 1080p | 1080p-esr | 1080p-esr & 60fps | 1080p-sr | 1440p-esr | 1440p-sr | 2160p | 4k-esr |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Fal | $0.2205 | $0.473 | – | – | $1.164 | – | – | – | – | – | – | – |
| Higgsfield † | $0.1177 | $0.2647 | – | – | $0.6518 | – | – | – | – | – | – | – |
| SoCheap-Official | **$0.0862** | $0.1934 | – | – | **$0.4783** | – | – | – | – | – | – | – |
| MachGen | $0.0874 | $0.1965 | – | – | $0.4833 | – | – | – | – | – | – | – |
| OpenSand | $0.0914 | $0.1965 | – | – | $0.4833 | – | – | – | – | – | $1.9333 | – |
| TOAPIS | $0.1004 | $0.2175 | – | – | $0.5391 | – | – | – | – | – | – | – |
| Replicate | $0.1028 | $0.2312 | – | – | – | – | – | – | – | – | – | – |
| OpenRouter | $0.1028 | $0.2311 | – | – | $0.52 | – | – | – | – | – | $2.0801 | – |
| SoCheap-Overseas | – | **$0.137** | – | – | – | – | – | – | – | – | – | – |
| Atlas Cloud | $0.1397 | $0.3005 | $0.2515 | $0.2193 | $0.5914 | $0.4507 | $0.4958 | $0.4056 | $0.7602 | $0.7 | – | $1.7006 |
| SandBase | $0.144 | $0.288 | – | – | $0.72 | – | – | – | – | – | – | – |
| WaveSpeedAI | $0.162 | $0.324 | – | – | $0.81 | – | – | – | – | – | **$1.62** | – |
| Fal-US | $0.2205 | $0.473 | – | – | – | – | – | – | – | – | – | – |

† Higgsfield is not available through VideoRouter — reference list price only, never counted as the cheapest host.

[Details](models/bytedance__seedance-2.5.md) · [**Call seedance-2.5 via VideoRouter →**](https://videorouter.sh/video/bytedance/seedance-2.5?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>ByteDance seedance-2.5-talking-avatar</b> — 1 host, from $0.22/s</summary>

| Provider | 480p | 720p |
|---|---:|---:|
| WaveSpeedAI | $0.22 | $0.44 |

[Details](models/bytedance__seedance-2.5-talking-avatar.md) · [**Call seedance-2.5-talking-avatar via VideoRouter →**](https://videorouter.sh/video/bytedance/seedance-2.5-talking-avatar?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Creatify boreal</b> — 1 host, from $0.01/s</summary>

| Provider | 720p | 1080p | 2k |
|---|---:|---:|---:|
| Fal | $0.01 | $0.03 | $0.12 |

[Details](models/creatify__boreal.md) · [**Call boreal via VideoRouter →**](https://videorouter.sh/video/creatify/boreal?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>FaceFusion Labs hyperswap-video-faceswap</b> — 1 host, from $0.0067/s</summary>

| Provider | any |
|---|---:|
| FaceFusion Labs | $0.0067 |

[Details](models/segmind__hyperswap-video-faceswap.md) · [**Call hyperswap-video-faceswap via VideoRouter →**](https://videorouter.sh/video/segmind/hyperswap-video-faceswap?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Fal flux-3-max</b> — 1 host, from $0.17/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Fal | $0.17 | $0.29 |

[Details](models/fal__flux-3-max.md) · [**Call flux-3-max via VideoRouter →**](https://videorouter.sh/video/fal/flux-3-max?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Google gemini-omni-1.1-flash</b> — 3 hosts, from $0.03/s</summary>

| Provider | 360p | 720p | 1080p | 2160p | any |
|---|---:|---:|---:|---:|---:|
| WaveSpeedAI | $0.03 | $0.1 | $0.15 | $0.3 | – |
| Atlas Cloud | – | **$0.099** | **$0.144** | **$0.279** | – |
| Google | – | – | – | – | $0.1 |

[Details](models/google__gemini-omni-1.1-flash.md) · [**Call gemini-omni-1.1-flash via VideoRouter →**](https://videorouter.sh/video/google/gemini-omni-1.1-flash?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Google gemini-omni-1.2-flash</b> — 4 hosts, from $0.023/s</summary>

| Provider | 360p | 720p | 1080p | 2160p |
|---|---:|---:|---:|---:|
| Fal | $0.0273 | $0.0819 | $0.1229 | $0.2457 |
| WaveSpeedAI | **$0.023** | $0.07 | $0.105 | $0.21 |
| Google | $0.0232 | $0.0695 | $0.1043 | $0.2085 |
| Atlas Cloud | – | **$0.0596** | **$0.0874** | **$0.1708** |

[Details](models/google__gemini-omni-1.2-flash.md) · [**Call gemini-omni-1.2-flash via VideoRouter →**](https://videorouter.sh/video/google/gemini-omni-1.2-flash?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Google gemini-omni-flash</b> — 4 hosts, from $0.1/s</summary>

| Provider | any |
|---|---:|
| Fal | $0.13 |
| Google | **$0.1** |
| Atlas Cloud | $0.125 |
| WaveSpeedAI | $0.13 |

[Details](models/google__gemini-omni-flash.md) · [**Call gemini-omni-flash via VideoRouter →**](https://videorouter.sh/video/google/gemini-omni-flash?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Google veo-3</b> — 1 host, from $0.2/s</summary>

| Provider | any |
|---|---:|
| Replicate | $0.2 |

[Details](models/google__veo-3.md) · [**Call veo-3 via VideoRouter →**](https://videorouter.sh/video/google/veo-3?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Google veo-3-fast</b> — 1 host, from $0.1/s</summary>

| Provider | any |
|---|---:|
| Replicate | $0.1 |

[Details](models/google__veo-3-fast.md) · [**Call veo-3-fast via VideoRouter →**](https://videorouter.sh/video/google/veo-3-fast?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Google veo-3.1</b> — 7 hosts, from $0.2/s</summary>

| Provider | 720p | 1080p | 2160p | any |
|---|---:|---:|---:|---:|
| OpenRouter | **$0.2** | **$0.2** | **$0.4** | – |
| Pika | – | – | – | **$0.2** |
| Replicate | – | – | – | **$0.2** |
| SandBase | **$0.2** | **$0.2** | **$0.4** | – |
| DeepInfra | – | – | – | $0.4 |
| WaveSpeedAI | $0.4 | $0.4 | **$0.4** | – |
| MachGen | $0.4003 | $0.4003 | $0.6001 | – |

[Details](models/google__veo-3.1.md) · [**Call veo-3.1 via VideoRouter →**](https://videorouter.sh/video/google/veo-3.1?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Google veo-3.1-extend</b> — 1 host, from $0.4/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Fal | $0.4 | $0.4 |

[Details](models/google__veo-3.1-extend.md) · [**Call veo-3.1-extend via VideoRouter →**](https://videorouter.sh/video/google/veo-3.1-extend?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Google veo-3.1-fast</b> — 7 hosts, from $0.08/s</summary>

| Provider | 720p | 1080p | 2160p | any |
|---|---:|---:|---:|---:|
| OpenRouter | **$0.08** | **$0.1** | $0.25 | – |
| Pika | **$0.08** | **$0.1** | – | – |
| SandBase | **$0.08** | **$0.1** | $0.25 | – |
| Replicate | – | – | – | **$0.1** |
| MachGen | $0.1003 | $0.1207 | $0.3 | – |
| DeepInfra | – | – | – | $0.15 |
| WaveSpeedAI | $0.15 | $0.15 | **$0.15** | – |

[Details](models/google__veo-3.1-fast.md) · [**Call veo-3.1-fast via VideoRouter →**](https://videorouter.sh/video/google/veo-3.1-fast?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Google veo-3.1-fast-extend</b> — 1 host, from $0.15/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Fal | $0.15 | $0.15 |

[Details](models/google__veo-3.1-fast-extend.md) · [**Call veo-3.1-fast-extend via VideoRouter →**](https://videorouter.sh/video/google/veo-3.1-fast-extend?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Google veo-3.1-lite</b> — 4 hosts, from $0.03/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| OpenRouter | **$0.03** | **$0.05** |
| Pika | **$0.03** | **$0.05** |
| SandBase | **$0.03** | **$0.05** |
| WaveSpeedAI | $0.05 | $0.08 |

[Details](models/google__veo-3.1-lite.md) · [**Call veo-3.1-lite via VideoRouter →**](https://videorouter.sh/video/google/veo-3.1-lite?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>HeyGen Avatar IV</b> — 1 host, from $0.05/s</summary>

| Provider | 720p | 1080p | 2160p |
|---|---:|---:|---:|
| HeyGen | $0.05 | $0.05 | $0.0667 |

[Details](models/heygen__avatar-iv.md) · [**Call HeyGen Avatar IV via VideoRouter →**](https://videorouter.sh/video/heygen/avatar-iv?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>heygen-avatar4-image-to-video</b> — 1 host, from $0.1/s</summary>

| Provider | any |
|---|---:|
| Fal | $0.1 |

[Details](models/heygen__heygen-avatar4-image-to-video.md) · [**Call heygen-avatar4-image-to-video via VideoRouter →**](https://videorouter.sh/video/heygen/heygen-avatar4-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>heygen-v3-lipsync-precision</b> — 1 host, from $0.1/s</summary>

| Provider | any |
|---|---:|
| Fal | $0.1 |

[Details](models/heygen__heygen-v3-lipsync-precision.md) · [**Call heygen-v3-lipsync-precision via VideoRouter →**](https://videorouter.sh/video/heygen/heygen-v3-lipsync-precision?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>heygen-v3-lipsync-speed</b> — 1 host, from $0.05/s</summary>

| Provider | any |
|---|---:|
| Fal | $0.05 |

[Details](models/heygen__heygen-v3-lipsync-speed.md) · [**Call heygen-v3-lipsync-speed via VideoRouter →**](https://videorouter.sh/video/heygen/heygen-v3-lipsync-speed?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>heygen-video-1</b> — 4 hosts, from $0.02/s</summary>

| Provider | 480p | 768p | 1080p | 2k |
|---|---:|---:|---:|---:|
| Fal | **$0.02** | **$0.02** | **$0.06** | **$0.06** |
| HeyGen | **$0.02** | $0.03 | $0.09 | $0.09 |
| OpenRouter | **$0.02** | $0.036 | $0.1 | $0.1 |
| WaveSpeedAI | **$0.02** | $0.036 | – | – |

[Details](models/heygen__heygen-video-1.md) · [**Call heygen-video-1 via VideoRouter →**](https://videorouter.sh/video/heygen/heygen-video-1?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-ai-avatar-v2-pro</b> — 2 hosts, from $0.112/s</summary>

| Provider | any |
|---|---:|
| Fal | $0.115 |
| WaveSpeedAI | **$0.112** |

[Details](models/kuaishou__kling-ai-avatar-v2-pro.md) · [**Call kling-ai-avatar-v2-pro via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-ai-avatar-v2-pro?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-ai-avatar-v2-standard</b> — 2 hosts, from $0.056/s</summary>

| Provider | any |
|---|---:|
| Fal | $0.0562 |
| WaveSpeedAI | **$0.056** |

[Details](models/kuaishou__kling-ai-avatar-v2-standard.md) · [**Call kling-ai-avatar-v2-standard via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-ai-avatar-v2-standard?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-motion-control</b> — 2 hosts, from $0.1071/s</summary>

| Provider | pro | std |
|---|---:|---:|
| Atlas Cloud | **$0.1428** | **$0.1071** |
| Novita | $0.21 | $0.1575 |

[Details](models/kuaishou__kling-motion-control.md) · [**Call kling-motion-control via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-motion-control?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-o3</b> — 3 hosts, from $0.0588/s</summary>

| Provider | 720p | 1080p | 2160p | any |
|---|---:|---:|---:|---:|
| SandBase | **$0.0588** | **$0.0784** | **$0.294** | – |
| MachGen | $0.068 | $0.0901 | $0.3366 | – |
| WaveSpeedAI | $0.084 | $0.112 | $0.42 | $0.084 |

[Details](models/kuaishou__kling-o3.md) · [**Call kling-o3 via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-o3?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-v2.6</b> — 2 hosts, from $0.042/s</summary>

| Provider | 1080p | any | pro | std |
|---|---:|---:|---:|---:|
| Higgsfield † | $0.0666 | – | – | – |
| WaveSpeedAI | – | $0.042 | $0.14 | **$0.042** |
| Kling | – | – | – | $0.062 |

† Higgsfield is not available through VideoRouter — reference list price only, never counted as the cheapest host.

[Details](models/kuaishou__kling-v2.6.md) · [**Call kling-v2.6 via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-v2.6?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-v2.6-motion-control</b> — 1 host, from $0.0595/s</summary>

| Provider | pro | std |
|---|---:|---:|
| Atlas Cloud | $0.0952 | $0.0595 |

[Details](models/kuaishou__kling-v2.6-motion-control.md) · [**Call kling-v2.6-motion-control via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-v2.6-motion-control?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-v3</b> — 8 hosts, from $0.0588/s</summary>

| Provider | 720p | 1080p | 2160p | any |
|---|---:|---:|---:|---:|
| Higgsfield † | $0.0714 | $0.0962 | – | – |
| SandBase | **$0.0588** | **$0.0784** | **$0.294** | – |
| TOAPIS | $0.06 | $0.08 | – | – |
| MachGen | $0.068 | $0.0901 | $0.3366 | – |
| Pika | $0.068 | $0.09 | – | – |
| kie.ai | $0.07 | $0.09 | $0.335 | – |
| Novita | $0.084 | $0.112 | $0.42 | – |
| WaveSpeedAI | $0.084 | $0.112 | $0.42 | $0.084 |
| OpenRouter | $0.14 | – | – | – |

† Higgsfield is not available through VideoRouter — reference list price only, never counted as the cheapest host.

[Details](models/kuaishou__kling-v3.md) · [**Call kling-v3 via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-v3?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-v3-omni-video</b> — 1 host, from $0.168/s</summary>

| Provider | 2160p | pro | standard |
|---|---:|---:|---:|
| Replicate | $0.42 | $0.224 | $0.168 |

[Details](models/kuaishou__kling-v3-omni-video.md) · [**Call kling-v3-omni-video via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-v3-omni-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-v3-turbo</b> — 3 hosts, from $0.09/s</summary>

| Provider | 720p | 1080p | any |
|---|---:|---:|---:|
| kie.ai | **$0.09** | $0.1125 | – |
| Pika | **$0.09** | **$0.112** | – |
| WaveSpeedAI | $0.112 | $0.14 | $0.112 |

[Details](models/kuaishou__kling-v3-turbo.md) · [**Call kling-v3-turbo via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-v3-turbo?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-v3-video</b> — 1 host, from $0.168/s</summary>

| Provider | 2160p | pro | standard |
|---|---:|---:|---:|
| Replicate | $0.42 | $0.224 | $0.168 |

[Details](models/kuaishou__kling-v3-video.md) · [**Call kling-v3-video via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-v3-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-v4.0</b> — 8 hosts, from $0.1335/s</summary>

| Provider | 720p | 1080p | 1080p-esr | 2k | 2160p | 4k-esr |
|---|---:|---:|---:|---:|---:|---:|
| Fal | $0.157 | $0.235 | – | – | – | – |
| Higgsfield † | $0.1257 | $0.1879 | – | – | – | – |
| MachGen | **$0.1335** | **$0.1998** | – | – | – | – |
| SandBase | **$0.1335** | **$0.1998** | – | – | – | – |
| Atlas Cloud | $0.1429 | $0.2139 | $0.182 | $0.2139 | $0.2139 | $0.364 |
| Replicate | $0.157 | $0.235 | – | – | – | – |
| Runware | $0.157 | $0.235 | – | – | – | – |
| TOAPIS | $0.157 | $0.235 | – | – | – | – |
| WaveSpeedAI | $0.157 | $0.235 | – | – | – | – |

† Higgsfield is not available through VideoRouter — reference list price only, never counted as the cheapest host.

[Details](models/kuaishou__kling-v4.0.md) · [**Call kling-v4.0 via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-v4.0?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-v4.0-edit</b> — 5 hosts, from $0.1598/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Fal | $0.188 | $0.282 |
| SandBase | **$0.1598** | **$0.2397** |
| Atlas Cloud | $0.1711 | $0.2566 |
| Runware | $0.188 | $0.282 |
| WaveSpeedAI | $0.188 | $0.282 |

[Details](models/kuaishou__kling-v4.0-edit.md) · [**Call kling-v4.0-edit via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-v4.0-edit?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-v4.0-extend</b> — 1 host, from $0.157/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| WaveSpeedAI | $0.157 | $0.235 |

[Details](models/kuaishou__kling-v4.0-extend.md) · [**Call kling-v4.0-extend via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-v4.0-extend?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-v4.0-flash</b> — 4 hosts, from $0.0857/s</summary>

| Provider | 720p |
|---|---:|
| Fal | $0.094 |
| Atlas Cloud | **$0.0857** |
| Runware | $0.094 |
| WaveSpeedAI | $0.094 |

[Details](models/kuaishou__kling-v4.0-flash.md) · [**Call kling-v4.0-flash via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-v4.0-flash?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-v4.0-flash-edit</b> — 3 hosts, from $0.1143/s</summary>

| Provider | 720p |
|---|---:|
| Atlas Cloud | **$0.1143** |
| Runware | $0.126 |
| WaveSpeedAI | $0.126 |

[Details](models/kuaishou__kling-v4.0-flash-edit.md) · [**Call kling-v4.0-flash-edit via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-v4.0-flash-edit?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Kuaishou kling-video-o1</b> — 1 host, from $0.112/s</summary>

| Provider | any |
|---|---:|
| OpenRouter | $0.112 |

[Details](models/kuaishou__kling-video-o1.md) · [**Call kling-video-o1 via VideoRouter →**](https://videorouter.sh/video/kuaishou/kling-video-o1?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Lightricks ltx-2-fast</b> — 1 host, from $0.04/s</summary>

| Provider | any |
|---|---:|
| WaveSpeedAI | $0.04 |

[Details](models/lightricks__ltx-2-fast.md) · [**Call ltx-2-fast via VideoRouter →**](https://videorouter.sh/video/lightricks/ltx-2-fast?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Lightricks ltx-2-pro</b> — 1 host, from $0.06/s</summary>

| Provider | any |
|---|---:|
| WaveSpeedAI | $0.06 |

[Details](models/lightricks__ltx-2-pro.md) · [**Call ltx-2-pro via VideoRouter →**](https://videorouter.sh/video/lightricks/ltx-2-pro?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Lightricks ltx-2.3</b> — 1 host, from $0.02/s</summary>

| Provider | 480p | 720p | 1080p |
|---|---:|---:|---:|
| WaveSpeedAI | $0.02 | $0.03 | $0.04 |

[Details](models/lightricks__ltx-2.3.md) · [**Call ltx-2.3 via VideoRouter →**](https://videorouter.sh/video/lightricks/ltx-2.3?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Lightricks ltx-2.3-fast</b> — 1 host, from $0.06/s</summary>

| Provider | 1080p | 1440p | 2160p |
|---|---:|---:|---:|
| SandBase | $0.06 | $0.12 | $0.24 |

[Details](models/lightricks__ltx-2.3-fast.md) · [**Call ltx-2.3-fast via VideoRouter →**](https://videorouter.sh/video/lightricks/ltx-2.3-fast?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Lightricks ltx-2.3-pro</b> — 2 hosts, from $0.03/s</summary>

| Provider | 1080p | 1440p | 2160p |
|---|---:|---:|---:|
| MachGen | **$0.03** | **$0.06** | **$0.1** |
| SandBase | $0.08 | $0.16 | $0.32 |

[Details](models/lightricks__ltx-2.3-pro.md) · [**Call ltx-2.3-pro via VideoRouter →**](https://videorouter.sh/video/lightricks/ltx-2.3-pro?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Lightricks ltx-2.5</b> — 1 host, from $0.1/s</summary>

| Provider | 720p | 1080p | 2k | 2160p |
|---|---:|---:|---:|---:|
| WaveSpeedAI | $0.1 | $0.14 | $0.21 | $0.33 |

[Details](models/lightricks__ltx-2.5.md) · [**Call ltx-2.5 via VideoRouter →**](https://videorouter.sh/video/lightricks/ltx-2.5?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Lightricks ltx-2.5-fast</b> — 2 hosts, from $0.09/s</summary>

| Provider | 720p | 1080p | 1440p | 2160p |
|---|---:|---:|---:|---:|
| Fal | **$0.09** | **$0.13** | **$0.19** | **$0.3** |
| Lightricks | **$0.09** | **$0.13** | **$0.19** | **$0.3** |

[Details](models/lightricks__ltx-2.5-fast.md) · [**Call ltx-2.5-fast via VideoRouter →**](https://videorouter.sh/video/lightricks/ltx-2.5-fast?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Lightricks ltx-2.5-pro</b> — 2 hosts, from $0.12/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Fal | **$0.12** | **$0.17** |
| Lightricks | **$0.12** | **$0.17** |

[Details](models/lightricks__ltx-2.5-pro.md) · [**Call ltx-2.5-pro via VideoRouter →**](https://videorouter.sh/video/lightricks/ltx-2.5-pro?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>luma-ray-3.2</b> — 2 hosts, from $0.03/s</summary>

| Provider | 540p | 720p | 1080p |
|---|---:|---:|---:|
| Luma | **$0.03** | **$0.06** | **$0.24** |
| SandBase | $0.1 | $0.2 | $0.4 |

[Details](models/luma__luma-ray-3.2.md) · [**Call luma-ray-3.2 via VideoRouter →**](https://videorouter.sh/video/luma/luma-ray-3.2?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>MeiGen-AI infinitetalk</b> — 1 host, from $0.03/s</summary>

| Provider | 480p | 720p |
|---|---:|---:|
| Atlas Cloud | $0.03 | $0.06 |

[Details](models/meigen-ai__infinitetalk.md) · [**Call infinitetalk via VideoRouter →**](https://videorouter.sh/video/meigen-ai/infinitetalk?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>MeiGen-AI infinitetalk-fast</b> — 1 host, from $0.015/s</summary>

| Provider | any |
|---|---:|
| WaveSpeedAI | $0.015 |

[Details](models/meigen-ai__infinitetalk-fast.md) · [**Call infinitetalk-fast via VideoRouter →**](https://videorouter.sh/video/meigen-ai/infinitetalk-fast?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Meituan longcat-avatar-1.5</b> — 1 host, from $0.04/s</summary>

| Provider | 480p | 720p |
|---|---:|---:|
| WaveSpeedAI | $0.04 | $0.08 |

[Details](models/meituan__longcat-avatar-1.5.md) · [**Call longcat-avatar-1.5 via VideoRouter →**](https://videorouter.sh/video/meituan/longcat-avatar-1.5?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>MiniMax h3-max</b> — 4 hosts, from $0.04/s</summary>

| Provider | 480p | 768p | 1440p | 1440p-sr | 2160p | 4k-sr |
|---|---:|---:|---:|---:|---:|---:|
| Fal | $0.05 | $0.08 | – | – | – | – |
| SandBase | **$0.04** | **$0.064** | – | – | – | – |
| Atlas Cloud | $0.0475 | $0.076 | $0.076 | $0.1425 | $0.076 | $0.1948 |
| TOAPIS | $0.05 | $0.08 | – | – | – | – |

[Details](models/minimax__h3-max.md) · [**Call h3-max via VideoRouter →**](https://videorouter.sh/video/minimax/h3-max?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>MiniMax h3-max-camera-controls</b> — 1 host, from $0.05/s</summary>

| Provider | 480p | 768p | 1080p |
|---|---:|---:|---:|
| Fal | $0.05 | $0.08 | $0.16 |

[Details](models/minimax__h3-max-camera-controls.md) · [**Call h3-max-camera-controls via VideoRouter →**](https://videorouter.sh/video/minimax/h3-max-camera-controls?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>MiniMax h3-max-lipsync</b> — 1 host, from $0.05/s</summary>

| Provider | 480p | 768p | 1080p | 2k |
|---|---:|---:|---:|---:|
| Fal | $0.05 | $0.08 | $0.16 | $0.32 |

[Details](models/minimax__h3-max-lipsync.md) · [**Call h3-max-lipsync via VideoRouter →**](https://videorouter.sh/video/minimax/h3-max-lipsync?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>MiniMax hailuo-2.3</b> — 1 host, from $0.0817/s</summary>

| Provider | any |
|---|---:|
| OpenRouter | $0.0817 |

[Details](models/minimax__hailuo-2.3.md) · [**Call hailuo-2.3 via VideoRouter →**](https://videorouter.sh/video/minimax/hailuo-2.3?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>MiniMax hailuo-2.3-standard</b> — 1 host, from $0.0467/s</summary>

| Provider | any |
|---|---:|
| WaveSpeedAI | $0.0467 |

[Details](models/minimax__hailuo-2.3-standard.md) · [**Call hailuo-2.3-standard via VideoRouter →**](https://videorouter.sh/video/minimax/hailuo-2.3-standard?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>MiniMax hailuo-3</b> — 1 host, from $0.13/s</summary>

| Provider | any |
|---|---:|
| OpenRouter | $0.13 |

[Details](models/minimax__hailuo-3.md) · [**Call hailuo-3 via VideoRouter →**](https://videorouter.sh/video/minimax/hailuo-3?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>MiniMax hailuo-3-max</b> — 1 host, from $0.05/s</summary>

| Provider | 480p | 768p |
|---|---:|---:|
| OpenRouter | $0.05 | $0.08 |

[Details](models/minimax__hailuo-3-max.md) · [**Call hailuo-3-max via VideoRouter →**](https://videorouter.sh/video/minimax/hailuo-3-max?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>minimax/h3</b> — 13 hosts, from $0.038/s</summary>

| Provider | 480p | 540p | 768p | 1080p | 1080p-esr | 1440p | 1440p-esr | 2k | 2160p | 4k-esr |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Fal | $0.05 | – | $0.06 | – | – | – | – | $0.13 | $0.16 | – |
| Higgsfield † | – | – | – | – | – | $0.13 | – | – | – | – |
| Atlas Cloud | **$0.038** | – | $0.08 | **$0.08** | $0.105 | **$0.08** | $0.115 | $0.13 | **$0.08** | $0.195 |
| kie.ai | – | – | **$0.04** | – | – | – | – | **$0.065** | – | – |
| WaveSpeedAI | $0.04 | $0.06 | $0.08 | $0.16 | – | – | – | – | – | – |
| MachGen | $0.044 | – | $0.05 | – | – | $0.125 | – | – | – | – |
| SandBase | – | – | $0.048 | – | – | – | – | $0.104 | – | – |
| OpenSand | – | – | $0.053 | – | – | – | – | $0.0862 | – | – |
| Novita | – | – | $0.069 | – | – | – | – | $0.1104 | – | – |
| MiniMax | – | – | $0.08 | – | – | – | – | $0.13 | – | – |
| Pika | – | – | $0.08 | – | – | – | – | $0.13 | – | – |
| Replicate | – | – | $0.08 | – | – | – | – | $0.13 | – | – |
| TOAPIS | – | – | $0.08 | – | – | – | – | $0.13 | – | – |
| WaveSpeedAI-resell | – | – | $0.1 | – | – | – | – | $0.14 | – | – |

† Higgsfield is not available through VideoRouter — reference list price only, never counted as the cheapest host.

[Details](models/minimax__h3.md) · [**Call minimax/h3 via VideoRouter →**](https://videorouter.sh/video/minimax/h3?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>minimax/h3-fast</b> — 1 host, from $0.0437/s</summary>

| Provider | any |
|---|---:|
| Atlas Cloud | $0.0437 |

[Details](models/minimax__h3-fast.md) · [**Call minimax/h3-fast via VideoRouter →**](https://videorouter.sh/video/minimax/h3-fast?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>minimax/h3-max-turbo</b> — 2 hosts, from $0.025/s</summary>

| Provider | 480p | 768p | 1080p |
|---|---:|---:|---:|
| Fal | **$0.025** | **$0.04** | $0.08 |
| TOAPIS | **$0.025** | **$0.04** | – |

[Details](models/minimax__h3-max-turbo.md) · [**Call minimax/h3-max-turbo via VideoRouter →**](https://videorouter.sh/video/minimax/h3-max-turbo?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>minimax/h3-turbo</b> — 1 host, from $0.02/s</summary>

| Provider | 480p | 768p |
|---|---:|---:|
| MachGen | $0.02 | $0.02 |

[Details](models/minimax__minimax-h3-turbo.md) · [**Call minimax/h3-turbo via VideoRouter →**](https://videorouter.sh/video/minimax/minimax-h3-turbo?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>minimax/hailuo-2.3-pro</b> — 1 host, from $0.0817/s</summary>

| Provider | any |
|---|---:|
| WaveSpeedAI | $0.0817 |

[Details](models/minimax__hailuo-2.3-pro.md) · [**Call minimax/hailuo-2.3-pro via VideoRouter →**](https://videorouter.sh/video/minimax/hailuo-2.3-pro?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>pika-2.5</b> — 1 host, from $0.04/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Pika | $0.04 | $0.09 |

[Details](models/pika__pika-2.5.md) · [**Call pika-2.5 via VideoRouter →**](https://videorouter.sh/video/pika/pika-2.5?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>pika-h3-flex</b> — 1 host, from $0.01/s</summary>

| Provider | 480p | 768p | 1080p | 2k | 2160p |
|---|---:|---:|---:|---:|---:|
| Pika | $0.01 | $0.02 | $0.035 | $0.04 | $0.08 |

[Details](models/pika__pika-h3-flex.md) · [**Call pika-h3-flex via VideoRouter →**](https://videorouter.sh/video/pika/pika-h3-flex?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>pikadditions</b> — 1 host, from $0.006/s</summary>

| Provider | any |
|---|---:|
| Pika | $0.006 |

[Details](models/pika__pikadditions.md) · [**Call pikadditions via VideoRouter →**](https://videorouter.sh/video/pika/pikadditions?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Pixverse-6-T2V</b> — 1 host, from $0.045/s</summary>

| Provider | any |
|---|---:|
| DeepInfra | $0.045 |

[Details](models/Pixverse__Pixverse-6-T2V.md) · [**Call Pixverse-6-T2V via VideoRouter →**](https://videorouter.sh/video/Pixverse/Pixverse-6-T2V?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>pixverse-c1</b> — 1 host, from $0.0246/s</summary>

| Provider | 360p | 540p | 720p | 1080p |
|---|---:|---:|---:|---:|
| MachGen | $0.0246 | $0.0323 | $0.0408 | $0.0765 |

[Details](models/pixverse__pixverse-c1.md) · [**Call pixverse-c1 via VideoRouter →**](https://videorouter.sh/video/pixverse/pixverse-c1?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>pixverse-v6</b> — 3 hosts, from $0.0204/s</summary>

| Provider | 360p | 540p | 720p | 1080p |
|---|---:|---:|---:|---:|
| MachGen | **$0.0204** | **$0.028** | **$0.0365** | **$0.0722** |
| SandBase | $0.025 | $0.035 | $0.045 | $0.09 |
| WaveSpeedAI | $0.025 | $0.035 | $0.045 | $0.09 |

[Details](models/pixverse__pixverse-v6.md) · [**Call pixverse-v6 via VideoRouter →**](https://videorouter.sh/video/pixverse/pixverse-v6?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>pixverse-v6-extend</b> — 1 host, from $0.025/s</summary>

| Provider | 360p | 540p | 720p | 1080p |
|---|---:|---:|---:|---:|
| Atlas Cloud | $0.025 | $0.035 | $0.045 | $0.09 |

[Details](models/pixverse__pixverse-v6-extend.md) · [**Call pixverse-v6-extend via VideoRouter →**](https://videorouter.sh/video/pixverse/pixverse-v6-extend?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>pixverse-v6-max</b> — 3 hosts, from $0.024/s</summary>

| Provider | 360p | 540p | 720p | 1080p |
|---|---:|---:|---:|---:|
| Atlas Cloud | **$0.024** | **$0.036** | **$0.044** | **$0.088** |
| WaveSpeedAI | $0.027 | $0.04 | $0.049 | $0.098 |
| Replicate | $0.06 | $0.09 | $0.11 | $0.22 |

[Details](models/pixverse__pixverse-v6-max.md) · [**Call pixverse-v6-max via VideoRouter →**](https://videorouter.sh/video/pixverse/pixverse-v6-max?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Pruna AI pruna-p-video-2-pro-avatar</b> — 1 host, from $0.02/s</summary>

| Provider | 480p | 768p |
|---|---:|---:|
| WaveSpeedAI | $0.02 | $0.04 |

[Details](models/pruna-ai__pruna-p-video-2-pro-avatar.md) · [**Call pruna-p-video-2-pro-avatar via VideoRouter →**](https://videorouter.sh/video/pruna-ai/pruna-p-video-2-pro-avatar?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>PrunaAI p-video</b> — 2 hosts, from $0.02/s</summary>

| Provider | 720p | 1080p | any |
|---|---:|---:|---:|
| DeepInfra | – | – | $0.02 |
| Pruna | $0.02 | $0.04 | – |

[Details](models/prunaai__p-video.md) · [**Call p-video via VideoRouter →**](https://videorouter.sh/video/prunaai/p-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>PrunaAI p-video-2</b> — 1 host, from $0.025/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Pruna | $0.025 | $0.05 |

[Details](models/prunaai__p-video-2.md) · [**Call p-video-2 via VideoRouter →**](https://videorouter.sh/video/prunaai/p-video-2?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>PrunaAI p-video-2-draft</b> — 1 host, from $0.015/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Pruna | $0.015 | $0.03 |

[Details](models/prunaai__p-video-2-draft.md) · [**Call p-video-2-draft via VideoRouter →**](https://videorouter.sh/video/prunaai/p-video-2-draft?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>PrunaAI p-video-2-pro</b> — 5 hosts, from $0.02/s</summary>

| Provider | 480p | 768p | 1080p | 2k | 2160p |
|---|---:|---:|---:|---:|---:|
| Pruna | **$0.02** | **$0.035** | **$0.055** | **$0.075** | **$0.115** |
| Replicate | **$0.02** | **$0.035** | **$0.055** | **$0.075** | **$0.115** |
| Runware | **$0.02** | **$0.035** | – | – | – |
| Segmind | **$0.02** | **$0.035** | – | – | – |
| WaveSpeedAI | **$0.02** | **$0.035** | – | – | – |

[Details](models/prunaai__p-video-2-pro.md) · [**Call p-video-2-pro via VideoRouter →**](https://videorouter.sh/video/prunaai/p-video-2-pro?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>PrunaAI p-video-2-pro-cost</b> — 5 hosts, from $0.01/s</summary>

| Provider | 480p | 768p | 1080p | 2k | 2160p |
|---|---:|---:|---:|---:|---:|
| Pruna | **$0.01** | **$0.025** | **$0.045** | **$0.065** | **$0.105** |
| Replicate | **$0.01** | **$0.025** | **$0.045** | **$0.065** | **$0.105** |
| Runware | **$0.01** | **$0.025** | – | – | – |
| Segmind | **$0.01** | **$0.025** | – | – | – |
| WaveSpeedAI | **$0.01** | **$0.025** | – | – | – |

[Details](models/prunaai__p-video-2-pro-cost.md) · [**Call p-video-2-pro-cost via VideoRouter →**](https://videorouter.sh/video/prunaai/p-video-2-pro-cost?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>PrunaAI p-video-2-pro-quality</b> — 5 hosts, from $0.04/s</summary>

| Provider | 480p | 768p | 1080p | 2k | 2160p |
|---|---:|---:|---:|---:|---:|
| Pruna | **$0.04** | **$0.075** | **$0.095** | **$0.115** | **$0.155** |
| Replicate | **$0.04** | **$0.075** | **$0.095** | **$0.115** | **$0.155** |
| Runware | **$0.04** | **$0.075** | – | – | – |
| Segmind | **$0.04** | **$0.075** | – | – | – |
| WaveSpeedAI | **$0.04** | **$0.075** | – | – | – |

[Details](models/prunaai__p-video-2-pro-quality.md) · [**Call p-video-2-pro-quality via VideoRouter →**](https://videorouter.sh/video/prunaai/p-video-2-pro-quality?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>PrunaAI p-video-draft</b> — 1 host, from $0.005/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| Pruna | $0.005 | $0.01 |

[Details](models/prunaai__p-video-draft.md) · [**Call p-video-draft via VideoRouter →**](https://videorouter.sh/video/prunaai/p-video-draft?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Runway aleph-2</b> — 1 host, from $0.28/s</summary>

| Provider | any |
|---|---:|
| Runway | $0.28 |

[Details](models/runway__aleph-2.md) · [**Call aleph-2 via VideoRouter →**](https://videorouter.sh/video/runway/aleph-2?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Runway gen-4.5</b> — 2 hosts, from $0.12/s</summary>

| Provider | any |
|---|---:|
| OpenRouter | **$0.12** |
| Replicate | **$0.12** |

[Details](models/runway__gen-4.5.md) · [**Call gen-4.5 via VideoRouter →**](https://videorouter.sh/video/runway/gen-4.5?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Shengshu s1-avatar-offline</b> — 1 host, from $0.005/s</summary>

| Provider | any |
|---|---:|
| Shengshu | $0.005 |

[Details](models/vidu__s1-avatar-offline.md) · [**Call s1-avatar-offline via VideoRouter →**](https://videorouter.sh/video/vidu/s1-avatar-offline?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Shengshu vidu-q3</b> — 3 hosts, from $0.0293/s</summary>

| Provider | 360p | 540p | 720p | 1080p |
|---|---:|---:|---:|---:|
| Runware | **$0.0325** | **$0.0293** | **$0.065** | **$0.078** |
| MachGen | – | $0.042 | $0.071 | $0.089 |
| SandBase | $0.07 | $0.07 | $0.154 | $0.16 |

[Details](models/shengshu__vidu-q3.md) · [**Call vidu-q3 via VideoRouter →**](https://videorouter.sh/video/shengshu/vidu-q3?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Shengshu vidu-q3-pro</b> — 2 hosts, from $0.05/s</summary>

| Provider | 540p | 720p | 1080p |
|---|---:|---:|---:|
| WaveSpeedAI | **$0.05** | $0.125 | $0.15 |
| MachGen | $0.053 | **$0.118** | **$0.142** |

[Details](models/shengshu__vidu-q3-pro.md) · [**Call vidu-q3-pro via VideoRouter →**](https://videorouter.sh/video/shengshu/vidu-q3-pro?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Shengshu vidu-q3-pro-fast</b> — 1 host, from $0.118/s</summary>

| Provider | 720p | 1080p |
|---|---:|---:|
| MachGen | $0.118 | $0.148 |

[Details](models/shengshu__vidu-q3-pro-fast.md) · [**Call vidu-q3-pro-fast via VideoRouter →**](https://videorouter.sh/video/shengshu/vidu-q3-pro-fast?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Shengshu vidu-q3-turbo</b> — 3 hosts, from $0.02/s</summary>

| Provider | 360p | 540p | 720p | 1080p |
|---|---:|---:|---:|---:|
| MachGen | – | **$0.02** | $0.045 | – |
| Runware | **$0.026** | $0.0227 | **$0.0357** | **$0.0423** |
| SandBase | $0.04 | $0.04 | $0.077 | $0.08 |

[Details](models/shengshu__vidu-q3-turbo.md) · [**Call vidu-q3-turbo via VideoRouter →**](https://videorouter.sh/video/shengshu/vidu-q3-turbo?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Skywork AI skyreels-v3-talking-avatar</b> — 1 host, from $0.03/s</summary>

| Provider | 480p | 720p |
|---|---:|---:|
| WaveSpeedAI | $0.03 | $0.06 |

[Details](models/skywork-ai__skyreels-v3-talking-avatar.md) · [**Call skyreels-v3-talking-avatar via VideoRouter →**](https://videorouter.sh/video/skywork-ai/skyreels-v3-talking-avatar?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Skywork AI skyreels-v4</b> — 1 host, from $0.11/s</summary>

| Provider | 480p | 720p | 1080p |
|---|---:|---:|---:|
| WaveSpeedAI | $0.11 | $0.14 | $0.35 |

[Details](models/skywork-ai__skyreels-v4.md) · [**Call skyreels-v4 via VideoRouter →**](https://videorouter.sh/video/skywork-ai/skyreels-v4?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Sync Labs sync-lipsync</b> — 1 host, from $0.0117/s</summary>

| Provider | any |
|---|---:|
| Fal | $0.0117 |

[Details](models/sync-labs__sync-lipsync.md) · [**Call sync-lipsync via VideoRouter →**](https://videorouter.sh/video/sync-labs/sync-lipsync?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Sync Labs sync-lipsync-react-1</b> — 1 host, from $0.1667/s</summary>

| Provider | any |
|---|---:|
| Fal | $0.1667 |

[Details](models/sync-labs__sync-lipsync-react-1.md) · [**Call sync-lipsync-react-1 via VideoRouter →**](https://videorouter.sh/video/sync-labs/sync-lipsync-react-1?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Sync Labs sync-lipsync-v2</b> — 1 host, from $0.05/s</summary>

| Provider | any |
|---|---:|
| Fal | $0.05 |

[Details](models/sync-labs__sync-lipsync-v2.md) · [**Call sync-lipsync-v2 via VideoRouter →**](https://videorouter.sh/video/sync-labs/sync-lipsync-v2?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Sync Labs sync-lipsync-v2-pro</b> — 1 host, from $0.0833/s</summary>

| Provider | any |
|---|---:|
| Fal | $0.0833 |

[Details](models/sync-labs__sync-lipsync-v2-pro.md) · [**Call sync-lipsync-v2-pro via VideoRouter →**](https://videorouter.sh/video/sync-labs/sync-lipsync-v2-pro?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Sync Labs sync-lipsync-v3</b> — 1 host, from $0.1333/s</summary>

| Provider | any |
|---|---:|
| Fal | $0.1333 |

[Details](models/sync-labs__sync-lipsync-v3.md) · [**Call sync-lipsync-v3 via VideoRouter →**](https://videorouter.sh/video/sync-labs/sync-lipsync-v3?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>Sync Labs sync-lipsync-v3-image</b> — 1 host, from $0.1333/s</summary>

| Provider | any |
|---|---:|
| Fal | $0.1333 |

[Details](models/sync-labs__sync-lipsync-v3-image.md) · [**Call sync-lipsync-v3-image via VideoRouter →**](https://videorouter.sh/video/sync-labs/sync-lipsync-v3-image?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>veed-fabric-1.0</b> — 1 host, from $0.07/s</summary>

| Provider | 480p | 720p |
|---|---:|---:|
| WaveSpeedAI | $0.07 | $0.14 |

[Details](models/veed__veed-fabric-1.0.md) · [**Call veed-fabric-1.0 via VideoRouter →**](https://videorouter.sh/video/veed/veed-fabric-1.0?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>veed-lipsync-v2</b> — 1 host, from $0.07/s</summary>

| Provider | any |
|---|---:|
| Fal | $0.07 |

[Details](models/veed__veed-lipsync-v2.md) · [**Call veed-lipsync-v2 via VideoRouter →**](https://videorouter.sh/video/veed/veed-lipsync-v2?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>xAI grok-imagine-video</b> — 5 hosts, from $0.05/s</summary>

| Provider | 480p | 720p | 1080p |
|---|---:|---:|---:|
| OpenRouter | **$0.05** | $0.07 | – |
| WaveSpeedAI | **$0.05** | **$0.05** | $0.05 |
| MachGen | $0.0502 | $0.0706 | – |
| Pika | $0.053 | $0.074 | – |
| xAI | $0.5 | $0.7 | – |

[Details](models/xai__grok-imagine-video.md) · [**Call grok-imagine-video via VideoRouter →**](https://videorouter.sh/video/xai/grok-imagine-video?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>xAI grok-imagine-video-1.5</b> — 5 hosts, from $0.08/s</summary>

| Provider | 480p | 720p | 1080p | any |
|---|---:|---:|---:|---:|
| OpenRouter | **$0.08** | **$0.14** | **$0.25** | – |
| Replicate | – | – | – | $0.08 |
| WaveSpeedAI | **$0.08** | **$0.14** | **$0.25** | – |
| MachGen | $0.0808 | $0.1403 | $0.2507 | – |
| xAI | $0.8 | $1.4 | $2.5 | – |

[Details](models/xai__grok-imagine-video-1.5.md) · [**Call grok-imagine-video-1.5 via VideoRouter →**](https://videorouter.sh/video/xai/grok-imagine-video-1.5?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>xAI grok-imagine-video-1.5-lite</b> — 1 host, from $0.02/s</summary>

| Provider | 480p | 720p | 1080p |
|---|---:|---:|---:|
| OpenRouter | $0.02 | $0.03 | $0.14 |

[Details](models/xai__grok-imagine-video-1.5-lite.md) · [**Call grok-imagine-video-1.5-lite via VideoRouter →**](https://videorouter.sh/video/xai/grok-imagine-video-1.5-lite?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>xAI grok-imagine-video-edit</b> — 1 host, from $0.08/s</summary>

| Provider | any |
|---|---:|
| Atlas Cloud | $0.08 |

[Details](models/xai__grok-imagine-video-edit.md) · [**Call grok-imagine-video-edit via VideoRouter →**](https://videorouter.sh/video/xai/grok-imagine-video-edit?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

<details><summary><b>xAI grok-imagine-video-extend</b> — 1 host, from $0.08/s</summary>

| Provider | any |
|---|---:|
| Atlas Cloud | $0.08 |

[Details](models/xai__grok-imagine-video-extend.md) · [**Call grok-imagine-video-extend via VideoRouter →**](https://videorouter.sh/video/xai/grok-imagine-video-extend?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=compare)

</details>

## Use the data

Everything lives in [`data/`](data):

| File | Contents |
|---|---|
| [`data/models.json`](data/models.json) | One object per model: creator, tiers, every provider's price per tier |
| [`data/prices.csv`](data/prices.csv) | Flat table: `model, creator, provider, tier, usd_per_second` — open in any spreadsheet |
| [`data/summary.json`](data/summary.json) | Per model and tier: cheapest, priciest, spread, saving |

```bash
curl -s https://raw.githubusercontent.com/synvia-corp/Awesome-AI-Video-Models/main/data/prices.csv | head
```

```python
import json, urllib.request
url = 'https://raw.githubusercontent.com/synvia-corp/Awesome-AI-Video-Models/main/data/models.json'
models = json.load(urllib.request.urlopen(url))
m = next(m for m in models if m['id'].endswith('seedance-2.5'))
print(sorted((p['prices'].get('720p', 9), p['provider']) for p in m['providers'])[:3])
```

## How the numbers are produced

- **Unit:** USD per second of generated video, per resolution tier. A provider that sells one flat rate for all resolutions is filed under its known tier, or `any`.
- **Price:** the provider's list price — what it charges, before any platform fee. If a provider has several variants of one model (e.g. an image-to-video SKU), the cheapest is shown.
- **Source:** generated from the live [VideoRouter](https://videorouter.sh/models) catalog, which is checked against each provider's published rates and billed amounts. See [`docs/methodology.md`](docs/methodology.md).
- **Reference row:** Higgsfield's own list price (marked †) is shown for the models it sells, from its public estimate API. It is not available through VideoRouter and is never counted as the cheapest host.
- **Scope:** every safe-for-work video model. Adult/NSFW-capable models are not listed. Models whose cost depends on the input clip (video upscalers) are listed with the price shown as *varies by input clip*. Latency, reliability and quality columns are on the roadmap, not in this release.

Found a wrong or stale price, or a missing model/provider? Open an issue or PR — see [CONTRIBUTING.md](CONTRIBUTING.md).

## Call every model through one API

This index is published by [VideoRouter](https://videorouter.sh/?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=footer) — **the cheapest way to access every AI video model.** One API for all of the models above, routed to the cheapest healthy provider with automatic failover, for a 2.5% platform fee on top of provider cost. Using it is optional; the data here is free to use either way.

- 🔎 **[Live price index](https://videorouter.sh/pricing-index?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=footer)** — always current, sortable, with JSON and CSV downloads
- 🚀 **[Sign up and get an API key](https://videorouter.sh/signup?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=footer)** — one key, every provider
- 📘 **[Quickstart](https://videorouter.sh/docs/quickstart?utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=footer)** — first video in minutes
- 🎬 **[Browse every model](https://videorouter.sh/models?out=video&utm_source=github&utm_medium=readme&utm_campaign=awesome-ai-video-models&utm_content=footer)** — per-model pages with provider comparison
- 🐛 **Wrong or stale price?** [Open an issue](https://github.com/synvia-corp/Awesome-AI-Video-Models/issues/new) — we fix it fast

## License

Code: [MIT](LICENSE). Data: [CC BY 4.0](LICENSE-DATA) — free to use commercially; please link back to https://github.com/synvia-corp/Awesome-AI-Video-Models.
