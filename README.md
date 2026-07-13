# Younggun Park

Product-oriented Frontend Engineer based in Seoul.

I build React and TypeScript products where Web UI meets Android WebView, Edge devices, cameras, and local networks. At [P2ACH AI](https://p2ach.ai), I turn on-device Vision AI and B2B retail constraints into interfaces and operating workflows that work in the field.

For an offline Vision AI demo, I proposed the device-hosted Web UI and implemented its Next.js static export and Android v1 local server and OTA flow. It has run at 20 external exhibitions with 4 or more Edge devices per event, without a separate server PC, and in an internal demo room every business day for about 1 year and 5 months. While offline, the runtime loads the current local bundle; an update changes the version pointer only after archive extraction succeeds.

I also proposed and implemented a drag-and-drop Dashboard Editor that moved chart changes for 7 new PoCs from about half a day of development followed by QA and a hotfix deployment to about 10 minutes of Ops configuration.

## What I Work On

- Offline-capable Web UI on Android WebView and Edge devices
- Local HTTP serving, static bundles, and versioned update flows
- Data-heavy dashboards, visual editors, and operator self-service
- Shared TypeScript contracts across Web, API, mobile, and Edge
- AI-assisted delivery verified with real data, devices, tests, CI, browser QA, and production telemetry

## How I Build

I start with user and operator constraints, make ownership and failure boundaries explicit, and validate the result in the environment where it will run. I use coding agents across planning, implementation, refactoring, QA, and documentation, but review their output and verify it with the actual system.

## Tools I Often Use

React · TypeScript · Next.js · Vite · React Native · Android WebView · TanStack Query · Zustand · Vitest · Datadog RUM · GitHub Actions · Docker

## Selected Work

- [BrandKit](https://github.com/jadru/brand-kit) — public Next.js and TypeScript product codebase with Vitest and CI ([live product](https://brand-kit.jadru.com/ko))
- [Tauri v2: why I chose it over Electron](https://jadru.com/blog/build-tauri) — WebView, local data, test fallback, and update trade-offs
- [MYMU](https://apps.apple.com/kr/app/mymu-%EB%AF%B8%EC%88%A0%EA%B4%80-%EA%B8%B0%EB%A1%9D-%EB%8B%A4%EC%9D%B4%EC%96%B4%EB%A6%AC/id6757892642) — shipped Expo and React Native exhibition discovery and visit-recording app ([website](https://mymu.app))

## Links

- Website: https://jadru.com
- LinkedIn: https://www.linkedin.com/in/jadru
- Email: [ygpark0922@gmail.com](mailto:ygpark0922@gmail.com)
