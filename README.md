# Victor, Mobile Engineer | Build Pipelines from Devices to Cloud👋

I specialize in creating Mobile Apps (SwiftUI / React Native) and data pipelines from dashboard to Cloud (React.js，FastAPI & Node.js).

>  *"Whatever you do, work at it with all your heart, as working for the LORD, not for human masters."*
— Colossians 3:23

## Featured Project

- [**EDFViewerLite-MacOS**](https://github.com/zywkloo/EDFViewerLite-MacOS): Native SwiftUI EDF/BDF biomedical waveform viewer focused on Apple-native healthcare tooling.
- [**Wealth Lens**](https://yourlens.vercel.app/): Non-trading investor intelligence layer focused on behavioral clarity and risk context.

<p align="center">
  <a href="https://github.com/zywkloo/EDFViewerLite-MacOS">
    <img src="assets/EDFViewer-preview.png" alt="EDFViewerLite macOS app preview" width="1100" />
  </a>
</p>

<p align="center">
  <a href="https://yourlens.vercel.app/">
    <img src="assets/wealth-lens-preview.png" alt="Wealth Lens product preview" width="1100" />
  </a>
</p>

### Wealth Lens

**Wealth Lens - Better spot your patterns before you invest**

Wealth Lens is a non-trading intelligence layer for investors. It focuses on context and behavioral clarity, not buy/sell instructions.

#### Product Tone

- Observational, non-predictive, non-advisory.
- AI explains context, patterns, and risk posture.
- Users own every execution and allocation decision.

#### Architecture (Web + iOS)

- `web/`: Next.js 14 app (App Router), the primary product surface.
- `ios/WealthIntelligenceDemo/`: SwiftUI prototype aligned to the same product principles.
- `dataset/`: mock CSV data for behavior and scenario simulation.
- `docs/`: product and implementation documentation.
- `policy_v1.json`: policy thresholds and disclaimers used by the insight layer.

#### Core Product Experience

- Portfolio composition, allocation, and net-worth context.
- Behavioral pattern detection (early-add tendency, concentration pressure, trade-window clustering).
- Insight Lens explanations with beginner/pro depth.
- Live quote context via `/api/quotes`.

#### Local Development

**Prerequisites**

- Node.js 18+
- `pnpm`
- Xcode 15+
- `xcodegen` (for iOS project generation)

**Run Web**

```bash
pnpm install
pnpm dev:web
```

**Build Web**

```bash
pnpm build:web
```

**Run iOS Prototype**

```bash
xcodegen generate --spec project.yml --project ios --project-root .
open ios/WealthIntelligenceDemo.xcodeproj
```

#### Deployment

**Web (Vercel)**

- Deploy the Next.js app in `web/`.
- Build command: `pnpm --filter wealth-intelligence-web build` (or root script `pnpm build:web`).
- Route runtime follows Next.js route config (including edge/server behavior per route).
- `vercel.json` currently uses default platform behavior.

**iOS**

- Current flow is manual release from Xcode (`Archive -> Export/TestFlight/App Store`).
- No mobile CI/CD pipeline is configured in this repository yet.

#### Principles

- Behavior mirror, not recommendation.
- Clarity before action.
- Confidence-aware insights.
- Policy-versioned guardrails.

<!-- <p align="center">
  <a href="https://github.com/ZZZ-RecSys/ZZZ-MovieRecSystem">
    <img width="2272" height="1100" alt="zzz-movie-rec-system vercel app_ (1)" src="https://github.com/user-attachments/assets/63d6a6b6-ca4b-444f-a8c5-fbf9b2810ac7" />
  </a>
</p> -->

## About Me

- 💻 **Development**: 6 years in mobile development, 4 years in full-stack data processing.
- 🎮 **Game Design**: As the design lead, achieving No.1 in Sports and No.9 in Games in China's App Store on [May 3, 2015](https://www.linkedin.com/in/yiweiz315/overlay/1605156128130/single-media-viewer?profileId=ACoAAAiuV8IBlPS-3MR67sLJM3hfVdSAEgwG3ZY).
- 🌱 **Hackathons**: Team lead of CuHacking 2019 & 2020 winners ([InGenius / Martello Sponsor Awards](https://devpost.com/zywkloo)).
- ⌨️ **Blogging**: Read my tech thoughts on my [Personal Blog](https://zywkloo.github.io/).
- 📺 **Streaming**: Live Coding Streamer on [twitch.tv/zywkloo](https://www.twitch.tv/zywkloo), streaming LeetCode contests and gaming weekly.

<details>
  <summary>🎓 Degrees</summary>
  
  - 📖 Master of Data Science, UBC, Vancouver, Canada
  - 🍁 B.Sc. in Computer Science, Carleton University, Ottawa, Canada
  - 🏙️ B.Eng. in Urban Planning, Peking University, Beijing, China
  - 🥇 Carleton University Medal in Computer Science, 2020 Fall
</details>

<details>
  <summary>✍🏻 Recent Posts</summary>
  
  - 🛠️ [Worktree Refactor Playbook](https://zywkloo.github.io/blog/worktree-refactor-playbook/)
  - 🏙️ [Choosing the Right JavaScript Data Visualization Framework: Insights and Comparisons](https://zywkloo.medium.com/choosing-the-right-javascript-data-visualization-framework-insights-and-comparisons-6325b8d66969)
  - ⚛️ [3 Lessons Taught w/ React-Part 1:State Updates](https://zywkloo.medium.com/lessons-learned-to-improve-react-performance-b722c9b992e6)
  - ⚛️ [React-Native-Meteor: FB/Google Login & OAuth](https://zywkloo.github.io/React-Native-Meteor-SocialLogin/)
  - 🎲 [Board Game A.I.: from Deep Blue to Alpha Go](https://zywkloo.medium.com/board-game-a-i-from-deep-blue-to-alpha-go-4dffb5276064)
</details>

<!-- <details>
  <summary> 🏛️ Stats About Me </summary>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=zywkloo&show_icons=true&count_private=true&include_all_commits=true&line_height=21" alt="Yw's Github Stats" />
  <img src="https://github-profile-trophy.vercel.app/?username=zywkloo&column=7" alt="Yiwei's Github Trophy" />
</p>
</details> -->

## Connect with Me

<p align="center">
  <!-- LinkedIn -->
  <a href="https://www.linkedin.com/in/yiwei-zhang-4aa93840/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <!-- Devpost -->
  <a href="https://devpost.com/zywkloo">
    <img alt="Devpost" src="https://img.shields.io/badge/Devpost-%230176BE.svg?&style=for-the-badge&logo=devpost&logoColor=white" />
  </a>
  <!-- Personal Blog -->
  <a href="https://zywkloo.github.io/">
    <img alt="Blog" src="https://img.shields.io/badge/Blog-%2333CCCC.svg?&style=for-the-badge&logo=wordpress&logoColor=white" />
  </a>
  <!-- Medium -->
  <a href="https://zywkloo.medium.com/">
    <img alt="Medium" src="https://img.shields.io/badge/Medium-%23000000.svg?&style=for-the-badge&logo=medium&logoColor=white"/>
  </a>
    <!-- Twitch -->
  <a href="https://www.twitch.tv/zywkloo">
    <img alt="Twitch" src="https://img.shields.io/badge/Twitch-%239146FF.svg?&style=for-the-badge&logo=twitch&logoColor=white"/>
  </a>
</p>
<hr>
