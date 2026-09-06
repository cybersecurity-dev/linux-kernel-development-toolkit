<div align="center">
    <p align="center">
        <a href="https://github.com/cybersecurity-dev/awesome-linux-kernel-development">
          <img width="8%" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/Tux.svg" />
        </a>
    </p>

# **`LKDT`** | [Linux](https://github.com/cybersecurity-dev/awesome-linux-kernel-development-resources) Kernel [Development](https://github.com/cybersecurity-dev/awesome-linux-kernel-development) Toolkit [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)]()
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]() 
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)]()

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

```mermaid
flowchart TD

    LK[Linux Kernel]

    LK --> CORE[Core Kernel]
    LK --> MM[Memory Management]
    LK --> FS[File Systems]
    LK --> NET[Networking]
    LK --> DRV[Drivers]
    LK --> SEC[Security]
    LK --> VIRT[Virtualization]

    CORE --> SCH[Scheduler]
    CORE --> PROC[Processes]

    MM --> VM[Virtual Memory]
    MM --> SLAB[SLAB/SLUB]

    NET --> TCP[TCP/IP]
    NET --> NF[Netfilter]

    DRV --> PCI[PCI]
    DRV --> USB[USB]
    DRV --> GPU[Graphics]

    style LK fill:#434343,stroke:#000000,color:#ffffff
    style CORE fill:#0b5394,stroke:#073763,color:#ffffff
    style MM fill:#6aa84f,stroke:#38761d,color:#ffffff
    style FS fill:#f1c232,stroke:#bf9000,color:#000000
    style NET fill:#674ea7,stroke:#351c75,color:#ffffff
    style DRV fill:#990000,stroke:#660000,color:#ffffff
```

## 📖 Contents
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)


##

### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/linux-kernel-development-toolkit/graphs/contributors)!

[🔼 Back to top](#lkdt--linux-kernel-development-toolkit-)
