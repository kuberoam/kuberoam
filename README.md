# 🚀 Roam: Kubernetes Management App

![Roam Banner](https://kuberoam.dev/feature_graphic.png)

**Roam** is a private, no-server Kubernetes client for your **phone** and your **desktop** (macOS, Windows and Linux).

*This repository does not contain the application source code. It is the public home of Roam: download the desktop app from [Releases](https://github.com/kuberoam/kuberoam/releases), report issues and request features.*

## 📥 Download

### 📱 Mobile

<a href="https://apps.apple.com/app/id6794656342"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="40"></a>
<a href="https://play.google.com/store/apps/details?id=dev.roam"><img src=".github/assets/google-play-badge.png" alt="Get it on Google Play" height="40"></a>

### 🖥️ Desktop

| System | Download |
|---|---|
| **Windows** 10/11 (x64) | [Roam-windows-amd64-installer.exe](https://github.com/kuberoam/kuberoam/releases/latest/download/Roam-windows-amd64-installer.exe) |
| **Windows** on ARM | [Roam-windows-arm64-installer.exe](https://github.com/kuberoam/kuberoam/releases/latest/download/Roam-windows-arm64-installer.exe) |
| **Ubuntu 24.04+ / Debian 13+** (x64) | [.deb](https://github.com/kuberoam/kuberoam/releases/latest/download/Roam-linux-amd64.deb) · [.tar.gz](https://github.com/kuberoam/kuberoam/releases/latest/download/Roam-linux-amd64.tar.gz) |
| **Ubuntu 24.04+ / Debian 13+** (ARM64) | [.deb](https://github.com/kuberoam/kuberoam/releases/latest/download/Roam-linux-arm64.deb) · [.tar.gz](https://github.com/kuberoam/kuberoam/releases/latest/download/Roam-linux-arm64.tar.gz) |
| **macOS** 13+ | Coming soon to the Mac App Store |

- **Windows:** the installer isn't code-signed yet. If SmartScreen shows *"Windows protected your PC"*, choose **More info → Run anyway**. It installs WebView2 if your PC doesn't have it.
- **Linux:** `sudo apt install ./Roam-linux-amd64.deb` pulls in GTK and WebKitGTK 4.1. The `.tar.gz` holds the `roam` binary for other distributions with those libraries.
- Every release has a `SHA256SUMS` file. Roam checks [Releases](https://github.com/kuberoam/kuberoam/releases) for updates and verifies downloads against it.

## 🖥️ Roam for Desktop

![Roam desktop](https://kuberoam.dev/desktop/01-home.webp)

The same client, rebuilt for a big screen and a keyboard — apps instead of resource lists, answers instead of dashboards.

* **Starts with what needs you**: crash loops, unschedulable pods, nodes under pressure, failing jobs and expiring certificates, each with a next step.
* **Diagnosis** in plain words: why a workload is failing and what to check next.
* **Changes**: every change to the cluster while Roam runs — who made it (kubectl, Helm, Argo CD), the exact diff, and one-click revert.
* **Health checks**: reliability, security and efficiency scores, and what blocks your next Kubernetes upgrade.
* **Apps and an app map**: Deployments, StatefulSets, Services and Ingresses grouped into apps, with how traffic flows.
* **Logs, shells and files**: live logs with search and severity highlighting, container shells, pod files, and a kubectl/helm terminal (kubectl and helm are built into Roam).
* **Helm, metrics and add-ons**: release history, values diff, upgrade and rollback; metrics with rollouts drawn on the charts; cert-manager, Prometheus Operator and any CRD.
* **Connect your way**: kubeconfig, service-account token, or sign in to Amazon EKS, Google GKE and Azure AKS; SSH bastions supported.
* **Optional AI, bring your own**: explain an incident with an OpenAI-compatible API or a local Ollama model. Off until you configure it.

## 📱 Roam for Mobile

* **Rich Overview Dashboard**: instant health checks with real-time resource utilization, node status and critical cluster-wide events.
* **Node Operations**: inspect nodes and their Pods, and Cordon/Uncordon, Drain (respecting PodDisruptionBudgets) or Delete from your phone.
* **Workload Management**: Deployments, Pods, StatefulSets and more — scale, restart, or view and edit YAML on the fly.
* **Live Log Viewer**: terminal-style streaming with search, regex filtering and severity highlighting.
* **Issue Tracking**: cluster events grouped into Critical, Warning and Info, with on-device AI incident analysis.

## 🔒 Security-First Architecture

* **Zero middlemen**: Roam connects **directly** from your device to your Kubernetes API server. There is no Roam server; your credentials and cluster data never pass through third parties.
* **Encrypted at rest**: credentials are stored with the platform's secure storage — Keychain on iOS and macOS, Keystore on Android, Credential Manager on Windows, Secret Service on Linux.
* **Nothing collected**: no analytics, no telemetry, nothing "phoning home".

---

## 🤝 Feedback, Bug Reports & Feature Requests

We want to build the best Kubernetes experience for you. If you run into a problem or have an idea, we want to hear it!

1. **Bug Reports**: [open a Bug Report](https://github.com/kuberoam/kuberoam/issues/new?template=bug_report.md) — say whether it's the mobile or the desktop app.
2. **Feature Requests**: [submit a Feature Request](https://github.com/kuberoam/kuberoam/issues/new?template=feature_request.md).
3. **General Questions**: open an issue or reach out to support.

*Before opening a new issue, please search the [existing issues](https://github.com/kuberoam/kuberoam/issues) to see if it has already been reported.*

---

## 📩 Support & Contact

For private support or business inquiries:
📧 **Email**: richardpham201@gmail.com

---

### Links
- [Website](https://kuberoam.dev/)
- [Help](https://kuberoam.dev/help)
- [Privacy Policy](https://kuberoam.dev/privacy-policy)
- [Terms of Service](https://kuberoam.dev/terms-of-service)
