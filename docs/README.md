<h1 align="center">ASUS ZenBook Duo 14 UX481 Hackintosh</h1>
<br>
<p align="center">
  <img
      src="https://raw.githubusercontent.com/Qonfused/ASUS-ZenBook-Duo-14-UX481-Hackintosh/main/docs/assets/README/UX481.png"
      alt="UX481FL"
      class="center"
      width=500px
    >
  <br>
  A <b>Hackintosh</b> project for the <b>ASUS ZenBook Duo 14"</b> built on top of the <a href="https://github.com/acidanthera/OpenCorePkg">OpenCore</a> bootloader and <a href="https://github.com/Qonfused/OC-Build">OC-Build</a> build manager.
</p>

<div align="center">

  <a href="/LICENSE">![License](https://img.shields.io/badge/⚖_License-BSD_3_Clause-lightblue?labelColor=3f4551)</a>
  <a href="/docs/CHANGELOG.md">![SemVer](https://img.shields.io/badge/SemVer-v0.5.0-important?logo=SemVer&labelColor=3f4551)</a>
  <a href="">![Supported Models](https://img.shields.io/badge/Supported%20Models-UX481FA%20%7C%20UX481FL-important?labelColor=3f4551)</a>
  <a href="https://github.com/acidanthera/OpenCorePkg/releases">![OpenCore](https://img.shields.io/badge/dynamic/yaml?label=OpenCore&logo=Osano&logoColor=0298e1&labelColor=3f4451&prefix=v&query=OpenCorePkg.version&url=https%3A%2F%2Fraw.githubusercontent.com%2FQonfused%2FASUS-ZenBook-Duo-14-UX481-Hackintosh%2Fmain%2Fsrc%2Fbuild.lock)</a>
  <a href="https://github.com/Qonfused/ASUS-ZenBook-Duo-14-UX481-Hackintosh/actions/workflows/oc-build.yml">![OC Build](https://github.com/Qonfused/ASUS-ZenBook-Duo-14-UX481-Hackintosh/actions/workflows/oc-build.yml/badge.svg?branch=main)</a>

</div>

## ⚙️ Current Progress

> **Note** This repository is still a work in progress.
>
> See this repository's [task board](https://github.com/users/Qonfused/projects/2/views/4) and [issues page](https://github.com/Qonfused/ASUS-ZenBook-Duo-14-UX481-Hackintosh/issues) for current progress.
> Upcoming or planned changes are also tracked on a [roadmap board](https://github.com/users/Qonfused/projects/2/views/9).
> Refer to the [CHANGELOG](/docs/CHANGELOG.md) or [SemVer board](https://github.com/users/Qonfused/projects/2/views/11) for changes implemented per release version.

### macOS version support:
<table>
  <thead>
    <tr>
      <th>macOS Version</th>
      <th colspan=2>Status</th>
      <th>Minimum version</th>
      <th>Maximum version</th>
    </tr>
  </thead>
  <tbody>
  <!-- macOS 13 -->
    <tr>
      <td>
        <img
          src="https://raw.githubusercontent.com/Qonfused/ASUS-ZenBook-Duo-14-UX481-Hackintosh/main/docs/assets/README/ventura.png"
          width=25
          hspace=2
          align="top"
        />
        Ventura
      </td>
      <td style="text-align: center;">✅</td>
      <td>Fully Supported.</td>
      <td><code>(None)</code></td>
      <td><a href="https://apps.apple.com/us/app/macos-ventura/id1638787999"><code>(Latest)</code></a></td>
    </tr>
  <!-- macOS 12 -->
    <tr>
      <td>
        <img
          src="https://raw.githubusercontent.com/Qonfused/ASUS-ZenBook-Duo-14-UX481-Hackintosh/main/docs/assets/README/monterey.png"
          width=22
          hspace=2
          align="top"
        />
        Monterey
      </td>
      <td style="text-align: center;">✅</td>
      <td>Fully Supported.</td>
      <td><code>(None)</code></td>
      <td><a href="https://apps.apple.com/us/app/macos-monterey/id1576738294"><code>(Latest)</code></a></td>
    </tr>
  <!-- macOS 11 -->
    <tr>
      <td>
        <img
          src="https://raw.githubusercontent.com/Qonfused/ASUS-ZenBook-Duo-14-UX481-Hackintosh/main/docs/assets/README/bigsur.png"
          width=25
          hspace=2
          align="top"
        />
        Big Sur
      </td>
      <td style="text-align: center;">✅</td>
      <td>Fully Supported.</td>
      <td><code>(None)</code></td>
      <td><a href="https://apps.apple.com/us/app/macos-big-sur/id1526878132"><code>(Latest)</code></a></td>
    </tr>
<!-- macOS 10.15 -->
    <tr>
      <td>
        <img
          src="https://raw.githubusercontent.com/Qonfused/ASUS-ZenBook-Duo-14-UX481-Hackintosh/main/docs/assets/README/catalina.png"
          width=25
          hspace=2
          align="top"
        />
        Catalina
      </td>
      <td style="text-align: center;">✅</td>
      <td>Fully Supported.</td>
      <td><a href="https://support.apple.com/kb/DL2036?locale=en_US"><code>10.15.4 (19E2265)</code></a></td>
      <td><a href="https://apps.apple.com/sg/app/macos-catalina/id1466841314"><code>(Latest)</code></a></td>
    </tr>
</table>


### Hardware features:
<table>
  <thead>
    <tr>
      <th>Component</th>
      <th>Device</th>
      <th colspan=2>Status</th>
    </tr>
  </thead>
  <tbody>
  <!-- Processor -->
    <tr>
      <td>CPU</td>
      <td>• Intel Core i7-10510U<br>• Intel Core i5-10210U</td>
      <td style="text-align: center;">✅</td>
      <td>Natively supported (since macOS Catalina).</td>
    </tr>
  <!-- Graphics -->
    <tr>
      <td rowspan=2>Graphics</td>
      <td>Intel UHD Graphics 620</td>
      <td style="text-align: center;">✅</td>
      <td>Full acceleration (with DRM).</td>
    </tr>
    <tr>
      <td>Nvidia GeForce MX250 2GB</td>
      <td style="text-align: center;">❌</td>
      <td>Disabled; no macOS support.</td>
    </tr>
  <!-- Displays -->
    <tr>
      <td rowspan=2>Displays</td>
      <td>14" Primary Display<br>(IPS, 1920x1080 @ 60 Hz)</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported (with backlight control).</td>
    </tr>
    <tr>
      <td>12.6" Screenpad Plus Display<br>(IPS, 1920x515 @ 60 Hz)</td>
      <td style="text-align: center;">🚧</td>
      <td>Work in progress (with backlight control).</td>
    </tr>
  <!-- Interfaces -->
    <tr>
      <td rowspan=6>Interfaces</td>
      <td>Built-in Keyboard</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported (with media keys and backlight control).</td>
    </tr>
    <tr>
      <td>Built-in Trackpad</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported (GPIO pinned with multi-touch gestures)</td>
    </tr>
    <tr>
      <td>(Physical) Trackpad Buttons</td>
      <td style="text-align: center;">🚧</td>
      <td>Work in progress (VoodooI2C issue; incorrect button map).</td>
    </tr>
    <tr>
      <td rowspan=2>Touchscreen<br>(Primary Display)<br>(Screenpad Plus Display)</td>
      <td style="text-align: center;">✅</td>
      <td rowspan=2>Fully supported (GPIO pinned with multi-touch gestures)</td>
    </tr>
    <tr>
      <td style="text-align: center;">✅</td>
    </tr>
    <tr>
      <td>Capacitive Stylus</td>
      <td style="text-align: center;">🚧</td>
      <td>Work in progress (works without pressure data).</td>
    </tr>
  <!-- Audio -->
    <tr>
      <td rowspan=2>Audio<br>(Realtek ALC294)</td>
      <td>Built-in speakers</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported (with volume control).</td>
    </tr>
    <tr>
      <td>Built-in microphone</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported.</td>
    </tr>
  <!-- Camera -->
    <tr>
      <td>Camera</td>
      <td>Windows Hello HD Camera</td>
      <td style="text-align: center;">🚧</td>
      <td>Work in progress.</td>
    </tr>
  <!-- Wi-Fi + Bluetooth -->
    <tr>
      <td>Wi-Fi</td>
      <td rowspan=2>Intel AX201<br>(Wi-Fi 6 + Bluetooth 5.0)</td>
      <td rowspan=2 style="text-align: center;">✅</td>
      <td rowspan=2>Fully supported (with limited Continuity support).</td>
    </tr>
    <tr>
      <td>Bluetooth</td>
    </tr>
  <!-- Storage -->
    <tr>
      <td>Storage</td>
      <td>Intel 660p NVMe SSD</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported (with power management).</td>
    </tr>
  <!-- Ports -->
    <tr>
      <td>Ports</td>
      <td>(Left)<br>• 1x 4.5mm DC-in (19V, 3.42A)<br>• 1x HDMI 1.4<br>• 1x USB 3.1 Gen 2 Type-A<br>• 1x USB 3.1 Gen 2 Type-C<br>(Right)<br>• 1x USB 3.1 Gen 1 Type-A<br>• 1x 3.5 mm Audio combo jack<br>• 1x MicroSD card reader</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported.</td>
    </tr>
  <!-- Battery and Power -->
    <tr>
      <td rowspan=2>Battery</td>
      <td>Built-in Battery</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported (with power reading).</td>
    </tr>
    <tr>
      <td>AC Power Adapter</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported (with hotplug and charge limit feature).</td>
    </tr>
  </tbody>
</table>


### Software features:
> **Note** To enable iServices functionality, download [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) and [generate SMBIOS data](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#using-gensmbios) for your machine.
<table>
  <thead>
    <tr>
      <th>Type</th>
      <th>Feature</th>
      <th colspan=2>Status</th>
    </tr>
  </thead>
  <tbody>
  <!-- iServices -->
    <tr>
      <td colspan=2>iServices (iCloud)</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported.</td>
    </tr>
  <!-- Continuity -->
    <tr>
      <td rowspan=6>Continuity</td>
      <td>Airplay to Mac</td>
      <td style="text-align: center;">✅</td>
      <td>Supported.</td>
    <tr>
      <td>Sidecar</td>
      <td style="text-align: center;">✅</td>
      <td>Supported.</td>
    <tr>
      <td>Handoff</td>
      <td style="text-align: center;">✅</td>
      <td>Supported</td>
    </tr>
    <tr>
      <td>Continuity Camera</td>
      <td style="text-align: center;">🚧</td>
      <td>Untested.</td>
    </tr>
    <tr>
      <td>Universal Clipboard</td>
      <td style="text-align: center;">✅</td>
      <td>Supported</td>
    </tr>
    <tr>
      <td>Universal Control</td>
      <td style="text-align: center;">✅</td>
      <td>Supported.</td>
    </tr>
  <!-- Sleep + Wake -->
    <tr>
      <td rowspan=2>Sleep / Wake</td>
      <td>Sleep</td>
      <td style="text-align: center;">✅</td>
      <td>Supported.</td>
    </tr>
    <tr>
      <td>Hibernation</td>
      <td style="text-align: center;">🚧</td>
      <td>Untested.</td>
    </tr>
  <!-- Battery meter -->
    <tr>
      <td colspan=2>Battery Indication</td>
      <td style="text-align: center;">✅</td>
      <td>Fully supported.</td>
    </tr>
</table>

## ⚡ Getting Started
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=521847844)

### 1. Clone this repository using Git

To clone this repository locally with submodules, run:
```sh
git clone --recurse-submodules https://github.com/Qonfused/ASUS-ZenBook-Duo-14-UX481-Hackintosh
cd ASUS-ZenBook-Duo-14-UX481-Hackintosh
```

> **Note**: Optionally, you can add git aliases to always resolve submodules:
> ```sh
> git config --global alias.clone-all 'clone --recurse-submodules'
> git config --global alias.pull-all 'pull --recurse-submodules'
> ```

### 2. Build this repository using OC-Build
> **Note** **OC-Build** must be run in a Linux or macOS environment.
> 
> For Windows users, refer to [aka.ms/wslinstall](aka.ms/wslinstall) and [aka.ms/wsl2](aka.ms/wsl2) for instructions on installing wsl and upgrading to the wsl2 kernel (recommended). You can install Linux directly from the Microsoft Store (e.g. [Ubuntu 20.04.5 LTS](https://apps.microsoft.com/store/detail/ubuntu-20045-lts/9MTTCL66CPXJ)).
>
> For Linux users (or wsl), ensure you have the following commands available:
> - **cURL**
>   - Check with `curl --version`
>   - Install with `sudo apt install curl`
> - **bsdtar**
>   - Check with `bsdtar --version`
>   - Install with `sudo apt install libarchive-tools`
> - **iasl**
>   - Check with `iasl -v`
>   - Install with `sudo apt install acpica-tools`
>
> You may need to upgrade your git version to 2.25.0+ or greater to
> support the **sparse-checkout** git feature required by the OC-Build script.
>
> For example, standard package repos on Ubuntu install git version 2.25.1 by
> default, but you can upgrade git to the latest release candidate by running:
> ```sh
> sudo add-apt-repository ppa:git-core/candidate
> sudo apt update
> ```

To build this project's EFI, run the below command at the root of the project:
```sh
# Run build pipeline for the UX481FA/FL EFI
bash scripts/build.sh
```

You can run a validation script to check the EFI build output with:
```sh
# Verify build output for the UX481FA/FL EFI
bash scripts/validate-efi.sh
```

#### 3. Using this EFI with macOS
Refer to the [Install Guide](https://github.com/Qonfused/ASUS-ZenBook-Duo-14-UX481-Hackintosh/wiki/Install-Guide) and [Post-Install Guide](https://github.com/Qonfused/ASUS-ZenBook-Duo-14-UX481-Hackintosh/wiki/Post-Install-Guide) for installation instructions.

## 🔥 Contributing
Contributions to this project are always welcome! Refer to [CONTRIBUTING.md](https://github.com/Qonfused/ASUS-ZenBook-Duo-14-UX481-Hackintosh/blob/main/docs/CONTRIBUTING.md) for instructions (and tips) on making contributions to this project.

## ⚖️ License
[BSD 3-Clause License](https://github.com/Qonfused/ASUS-ZenBook-Duo-14-UX481-Hackintosh/blob/main/LICENSE).

## 🌟 Credits
- [Apple](https://www.apple.com) for macOS
- [shiecldk](https://github.com/shiecldk) for his contributions, and his work in the original [Zenbook Pro Duo 15" (UX582) OpenCore configuration and guide](https://github.com/shiecldk/ASUS-ZenBook-Pro-Duo-15-OLED-UX582-Hackintosh) that inspired this project.