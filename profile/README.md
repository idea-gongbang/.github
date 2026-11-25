<div align="center">

# app-gongbang

**앱 공방** · 남는 맥북 한 대를 서버 삼아, 아이디어를 앱으로 만드는 공간

![launched](https://img.shields.io/badge/launched-0%20%2F%2010-2ea44f?style=flat-square)
![server](https://img.shields.io/badge/server-MacBook-000000?style=flat-square&logo=apple&logoColor=white)
![visibility](https://img.shields.io/badge/visibility-private-8b949e?style=flat-square&logo=github)

</div>

---

## Mission

```text
LAUNCH  [░░░░░░░░░░░░░░░░░░░░]  0 / 10   (0%)
```

> 완벽한 앱 하나보다, 세상에 나온 앱 열 개.

## Pipeline

```mermaid
flowchart LR
    A([아이디어]) --> B[기획]
    B --> C[개발]
    C --> D[배포]
    D --> E([런칭])
    E -. 피드백 .-> B
```

## Apps

| Slot | App | 한 줄 소개 | Status | Repo |
|:---:|---|---|:---:|---|
| `01` | — | — | ⚪ | — |
| `02` | — | — | ⚪ | — |
| `03` | — | — | ⚪ | — |
| `04` | — | — | ⚪ | — |
| `05` | — | — | ⚪ | — |
| `06` | — | — | ⚪ | — |
| `07` | — | — | ⚪ | — |
| `08` | — | — | ⚪ | — |
| `09` | — | — | ⚪ | — |
| `10` | — | — | ⚪ | — |

<sub>⚪ 빈 슬롯 · 🟡 기획 중 · 🔵 개발 중 · 🟢 런칭</sub>

## Infrastructure

```mermaid
flowchart LR
    Dev[개발 머신] -- git push --> GH[(GitHub<br/>app-gongbang)]
    GH -- deploy --> Srv[MacBook 서버<br/>lid closed · 24/7]
    Srv --> User([사용자])
```

| 항목 | 내용 |
|---|---|
| Server | 남는 MacBook 1대 (클램셸 모드, 상시 가동) |
| Source | 이 조직의 비공개 레포 |
| Stack | 첫 앱에서 결정 |

---

<div align="center">
<sub>since 2026.11 · built on a spare MacBook</sub>
</div>
