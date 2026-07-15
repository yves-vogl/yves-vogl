# Yves Vogl

Principal Solution Architect at [adesso SE](https://adesso.de) — based in Dortmund, Germany.
Cloud infrastructure, platform engineering, and automation by day; independent product and open-source work on the side.

## Where I build

I run several GitHub organizations, each behind a product with a public open-source surface.

### 🎫 [kadenz-live](https://github.com/kadenz-live) — self-hosted event ticketing

[Kadenz](https://kadenz.live) is a ticketing platform for live events: a Rails API, a React web app, and a Flutter scanner, deployed self-hosted-first. The public repos are the pieces that stand on their own.

- **[kadenz-scanner](https://github.com/kadenz-live/kadenz-scanner)** · Flutter (iOS + Android)
  Open-source ticket-validation client. Validation runs fully offline by digest-matching — the HMAC signing secret never touches the device.
- **[kadenz-ci](https://github.com/kadenz-live/kadenz-ci)** · Shell
  Hardened, Cosign-signed self-hosted GitHub Actions runner image — Docker and bare-metal deployment patterns, daily security rebuilds, SBOM included.

### 📸 [PixelCurator](https://github.com/PixelCurator) — on-device photo curation

PixelCurator organizes a photo library with AI that runs entirely on-device — nothing is uploaded to the cloud.

- **[pixelcurator](https://github.com/PixelCurator/pixelcurator)** · Python
  On-device AI photo organizer for the macOS Photos.app — CLIP + NudeNet + face recognition, no cloud upload.
- **[app](https://github.com/PixelCurator/app)** · Swift
  Native SwiftUI app for iPhone / iPad / Mac using on-device PhotoKit + MobileCLIP. A ground-up rebuild of PixelCurator, not a port.

### ⛪ [Basilica Audio](https://github.com/basilica-audio) — sacred-architecture plugin suite

A suite of open-source audio plugins (AU / VST3 / Standalone, JUCE 8, AGPLv3) — thirteen heavyweight DSP tools forming a full mixing chain for symphonic and high-gain metal, from front-of-amp tone through the mastering limiter.

**Guitar & bass**
- **[Overture](https://github.com/basilica-audio/Overture)** — overdrive / pre-amp tightening stage in front of the amp.
- **[Tenebrae](https://github.com/basilica-audio/Tenebrae)** — cascaded, oversampled high-gain distortion with a 3-band tone stack.
- **[Silentium](https://github.com/basilica-audio/Silentium)** — lookahead/hysteresis noise gate with a sidechain high-pass for palm-muted rhythm.
- **[Nave](https://github.com/basilica-audio/Nave)** — partitioned-convolution cabinet IR loader for reamping guitar and bass DI.
- **[Crypta](https://github.com/basilica-audio/Crypta)** — parallax-style bass: split the lows, compress them, twist the guts out of the highs.

**Orchestral & vocal**
- **[Aureate](https://github.com/basilica-audio/Aureate)** — tape/console saturation glue for strings, brass and layered tracks.
- **[Seraph](https://github.com/basilica-audio/Seraph)** — choir & vocal processor: air, de-essing and doubling for operatic vocals.
- **[Miserere](https://github.com/basilica-audio/Miserere)** — parallel vocal chain: a direct path plus opto-sandwich, FET-smash and slap-delay busses.
- **[Requiem](https://github.com/basilica-audio/Requiem)** — cinematic convolution reverb with cathedral and hall spaces.
- **[Firmament](https://github.com/basilica-audio/Firmament)** — mid/side stereo widener and imager with bass-mono.

**Mix & master**
- **[Lancet](https://github.com/basilica-audio/Lancet)** — dynamic EQ with six surgical, threshold-driven bands and per-band gain-reduction metering.
- **[Triptych](https://github.com/basilica-audio/Triptych)** — 3-band multiband compressor with a Linkwitz-Riley crossover.
- **[Apotheosis](https://github.com/basilica-audio/Apotheosis)** — brickwall true-peak limiter with oversampled true-peak detection.

## Open source, solo

Standalone projects under my own account:

- **[moneymoney-paypal-pos-extension](https://github.com/yves-vogl/moneymoney-paypal-pos-extension)** · Lua — MoneyMoney extension for PayPal POS: card sales, refunds, fees, and payouts. MIT, GPG-signed.
- **[llm-ecosphere](https://github.com/yves-vogl/llm-ecosphere)** · Python — A closed world, small enough to explain an LLM ecosystem completely.
- **[aws-eks-helm-deploy](https://github.com/yves-vogl/aws-eks-helm-deploy)** · Python — Bitbucket Pipe for deploying Helm charts to AWS EKS.

---

<sub>Reach out via [LinkedIn](https://www.linkedin.com/in/yves-vogl-1b372184/) for collaboration, hiring, or speaking inquiries.</sub>
