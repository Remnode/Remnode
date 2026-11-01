

<p align="center">
  <img src="media/image.jpg" width="135" alt="Remnode logo" />
</p>

<h1 align="center">REMNODE</h1>

<p align="center">
  <strong>YOUR DESKTOP. YOUR SESSION. YOUR CONTROL.</strong>
</p>

<p align="center">
  A temporary Windows remote desktop environment, powered by GitHub Actions.
</p>

---

## The experience

https://github.com/user-attachments/assets/38bccb93-d721-4771-b8de-795a4ef09436

## Overview

Remnode brings together a Windows environment and remote desktop connectivity in one on-demand workflow.

```mermaid
flowchart TD
    A(["REMNODE"]) --> B["GitHub Actions"]
    B --> C["Windows Environment"]
    C --> D["AnyDesk"]
    C -.-> E["Optional RDP"]
    E --> F["Bore Tunnel"]
    D --> G(["Remote Desktop"])
    F --> G

    style A fill:#18243b,stroke:#6c9ee8,color:#ffffff
    style G fill:#18243b,stroke:#6c9ee8,color:#ffffff
    style B fill:#202b3d,stroke:#64748b,color:#ffffff
    style C fill:#202b3d,stroke:#64748b,color:#ffffff
    style D fill:#202b3d,stroke:#64748b,color:#ffffff
    style E fill:#202b3d,stroke:#64748b,color:#ffffff
    style F fill:#202b3d,stroke:#64748b,color:#ffffff
```

## What makes Remnode

|  | Feature | Description |
|:--:|---|---|
| ◈ | **Windows** | Windows environment on a hosted runner |
| ◉ | **AnyDesk** | Remote desktop connectivity |
| ⇄ | **RDP** | Optional alternative connection |
| ⚡ | **On demand** | Manually launch a session |
| ◇ | **Secret support** | AnyDesk password from GitHub Actions secrets |
| ⏱ | **Extended runtime** | Up to 360 minutes configured job timeout |

## Specifications

| | |
|---|---|
| **Platform** | Windows |
| **Runner** | `windows-latest` |
| **Automation** | GitHub Actions |
| **Launch mode** | Manual |
| **Remote access** | AnyDesk |
| **Optional access** | RDP via Bore |
| **Maximum job timeout** | 6 hours |
| **AnyDesk Password** | RemNode@2026 |

---

<p align="center">
  <strong>REMNODE</strong>
  <br />
  <sub>Simple. Remote. On demand.</sub>
</p>

