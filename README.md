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

### 🤘 [metal-up-your-ass](https://github.com/metal-up-your-ass) — high-gain metal audio plugins

Open-source audio plugins (AU / VST3, built with JUCE 8, AGPLv3), voiced for high-gain metal guitar and bass.

- **[overture](https://github.com/metal-up-your-ass/overture)** · C++ / JUCE 8
  Overdrive / pre-amp tightening stage — the front-of-amp boost that tightens up a high-gain rig.
- **[twist-your-guts](https://github.com/metal-up-your-ass/twist-your-guts)** · C++ / JUCE 8
  Parallax-style bass plugin — split the bass, compress the lows, twist the guts out of the highs.

## Open source, solo

Standalone projects under my own account:

- **[moneymoney-paypal-pos-extension](https://github.com/yves-vogl/moneymoney-paypal-pos-extension)** · Lua — MoneyMoney extension for PayPal POS: card sales, refunds, fees, and payouts. MIT, GPG-signed.
- **[llm-ecosphere](https://github.com/yves-vogl/llm-ecosphere)** · Python — A closed world, small enough to explain an LLM ecosystem completely.
- **[aws-eks-helm-deploy](https://github.com/yves-vogl/aws-eks-helm-deploy)** · Python — Bitbucket Pipe for deploying Helm charts to AWS EKS.

---

<sub>Reach out via [LinkedIn](https://www.linkedin.com/in/yves-vogl-1b372184/) for collaboration, hiring, or speaking inquiries.</sub>
