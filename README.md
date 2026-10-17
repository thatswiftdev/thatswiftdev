<!-- you're reading source. respect. the real easter egg is at the bottom. -->

```text
Last login: Mon Dec 2 10:41:51 2019 on ttys001
bk@mainactor ~ % swift run bk
    ____  __ __
   / __ )/ //_/
  / __  / ,<
 / /_/ / /| |
/_____/_/ |_|
```

```bash
bk@mainactor ~ % cat whoami.swift
```

```swift
@MainActor
struct BK: Developer {
    let title = "Jack-of-All-Trades Developer · Mobile Specialist"
    let base  = "Indonesia"
    let focus = ["Swift", "SwiftUI", "design systems → pixel-faithful UI"]

    var work: URL { URL(string: "https://github.com/MainActorDev")! }
    var blog: URL { URL(string: "https://mainactor.dev")! }
}
```

```bash
bk@mainactor ~ % swift build
Fetching https://github.com/MainActorDev
[6/9] Construkt      SwiftUI syntax · UIKit reliability            ★ 20
[5/9] xcbuddy        Xcode CLI · simulators with zero pain
[4/9] Bellwether     in-place refresh signals for UI-test automation
[3/9] butler         reusable agent runtime · tools, memory, MCP
[2/9] ma-ios-common  common utilities for iOS development
[1/9] Foodiary       calorie tracking, made simple
✔ Build complete. 6 shipped, 0 warnings.
```

```bash
bk@mainactor ~ % ls -F ~/stars
ai-llm/46          ios-architecture/24   ios-tooling/14
arabic-nlp/6       ios-networking/17     learning/38
ios-ui/94          other/7               web-design/11

257 repos · 9 curated lists → github.com/thatswiftdev?tab=stars
```

<details>
<summary><code>bk --help</code></summary>

```text
USAGE: bk <command>

  whoami     Jack-of-All-Trades Developer · Mobile Specialist
  org        @MainActorDev — iOS tooling & experiments
  stars      257 repos across 9 curated lists (ls ~/stars)
  blog       mainactor.dev
  x          @MainActorDev
  --private  Declayout — declarative-ish Auto Layout (nice try)
```

</details>

```bash
bk@mainactor ~ % open https://mainactor.dev
```

<!-- the build never stops. -->
