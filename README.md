# VJ Physics desktop releases

Public releases-only repository for VJ Physics: release information, documentation and approved downloadable binaries. The application source repository is not hosted here. No user media, projects or signing credentials are included.

VJ Physics is a free offline creative tool. No user account, analytics, automatic updates, cloud project storage or media upload is included. The online preview processes local files and microphone audio on the device. Projects can be exported as JSON and imported into the desktop app.

- Web Preview: https://vj.oghuzhan.work
- Public testing builds are marked **Beta / prerelease** and may be unsigned and unnotarized. They are not verified production releases.
- Production macOS downloads require Developer ID signing and notarization. Windows production follows Microsoft Store certification and Store signing; no pre-certification MSIX is offered as a production download.

Download only the architecture matching your computer. Verify files against `SHA256SUMS.txt` and the platform receipt attached to the same versioned release. Current macOS targets require macOS 13+ Apple Silicon or Intel. Read each release's actual platform-testing and signing limitations.

The application bundles Chromium and Node. End users do not install Node, Python or a local web server. Application source, media, projects and credentials are not uploaded as separate release assets. Packaged JavaScript/resources are necessarily part of each Electron binary.

Website/download hosting providers may process ordinary connection metadata. This is separate from application-level collection of media, microphone audio, projects or rendered frames.
