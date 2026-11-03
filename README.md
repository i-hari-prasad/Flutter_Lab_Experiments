# 📱 Flutter Laboratory Experiments

Interactive showcase of all 10 Flutter laboratory experiments hosted experiment-wise on **GitHub Pages**.

---

## 🌐 Live Hosted Experiments (Experiment-Wise Links)

| Experiment # | Title | Key Concepts & Frameworks | 🚀 Live Hosted App Link | 📁 Source Code |
|:---:|:---|:---|:---:|:---:|
| **01** | **Fresh Fruits Catalog** | `StatelessWidget`, `ListView`, `Card`, Material 3 | [Launch Exp 1](https://i-hari-prasad.github.io/Flutter_Lab_Experiments/exp_01/) | [Code](./exp_01) |
| **02** | **ShopEase Catalog** | `StatefulWidget`, Dynamic Grid/List, State Handling | [Launch Exp 2](https://i-hari-prasad.github.io/Flutter_Lab_Experiments/exp_02/) | [Code](./exp_02) |
| **03** | **ShopEase Interactive Store** | Reactive Cart State, Item Counter, Total Price Math | [Launch Exp 3](https://i-hari-prasad.github.io/Flutter_Lab_Experiments/exp_03/) | [Code](./exp_03) |
| **04** | **Car Mileage Calculator** | `TextEditingController`, Input Validation, Formulas | [Launch Exp 4](https://i-hari-prasad.github.io/Flutter_Lab_Experiments/exp_04/) | [Code](./exp_04) |
| **05** | **ShopEase Navigation** | `Navigator.push / pop`, Route Arguments, Detail Views | [Launch Exp 5](https://i-hari-prasad.github.io/Flutter_Lab_Experiments/exp_05/) | [Code](./exp_05) |
| **06** | **StudentHub SQLite CRUD** | `sqflite`, `sqflite_common_ffi_web`, WASM SQLite | [Launch Exp 6](https://i-hari-prasad.github.io/Flutter_Lab_Experiments/exp_06/) | [Code](./exp_06) |
| **07** | **StudentHub Cloud (Firestore)** | `cloud_firestore`, `firebase_core`, Real-time Cloud | [Launch Exp 7](https://i-hari-prasad.github.io/Flutter_Lab_Experiments/exp_07/) | [Code](./exp_07) |
| **08** | **Student Search Engine** | Firestore Querying, `StreamBuilder`, Dynamic Search | [Launch Exp 8](https://i-hari-prasad.github.io/Flutter_Lab_Experiments/exp_08/) | [Code](./exp_08) |
| **09** | **Student Record Update** | Document Update Operations, Interactive Dialog Forms | [Launch Exp 9](https://i-hari-prasad.github.io/Flutter_Lab_Experiments/exp_09/) | [Code](./exp_09) |
| **10** | **Secure Student Auth** | SHA-256 Hashing (`crypto`), Password Verification | [Launch Exp 10](https://i-hari-prasad.github.io/Flutter_Lab_Experiments/exp_10/) | [Code](./exp_10) |

> 🏠 **Central Hub Portal**: [https://i-hari-prasad.github.io/Flutter_Lab_Experiments/](https://i-hari-prasad.github.io/Flutter_Lab_Experiments/)  
> Every individual experiment has a floating **"🏠 All Experiments"** button at the top-right corner to jump back to the central hub anytime.

---

## ⚡ Automated CI/CD Deployment

This repository includes a GitHub Actions workflow [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) that:
1. Automatically sets up the latest stable Flutter SDK on every push.
2. Compiles every experiment for web (`flutter build web --release --base-href ./`).
3. Deploys each experiment to its respective subpath (`/exp_01/` ... `/exp_10/`) and publishes the root portal to **GitHub Pages**.

### How to Enable GitHub Pages (1-Time Setup on GitHub):
1. Go to repository **Settings** → **Pages** (in the left sidebar under *Code and automation*).
2. Under **Build and deployment** → **Source**, select **GitHub Actions**.
3. That's it! GitHub Actions will compile and host all 10 experiments automatically.
