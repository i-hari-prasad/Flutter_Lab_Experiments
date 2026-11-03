# 📱 Flutter Laboratory - All 10 Experiments

A comprehensive repository containing 10 Flutter laboratory experiments with a unified **GitHub Pages** web portal to run and test every experiment live in the browser.

---

## 🚀 Live Demo on GitHub Pages
> Once pushed and Pages is enabled, all 10 experiments are available at:  
> **`https://<your-username>.github.io/<your-repo-name>/`**

Each experiment also features a quick floating **"🏠 All Experiments"** button at the top-right corner to jump back to the central hub at any time.

---

## 🧪 Experiments Index

| # | Experiment | Key Concepts & Technologies | Direct Link |
|---|---|---|---|
| **01** | **Fresh Fruits Catalog** | `StatelessWidget`, `ListView`, `Card`, Material 3 Layout | [Launch](./exp_01/) |
| **02** | **ShopEase Catalog** | `StatefulWidget`, Dynamic Product Grid, Responsive UI | [Launch](./exp_02/) |
| **03** | **ShopEase Interactive Store** | Dynamic Shopping Cart, Counter State, Total Calculations | [Launch](./exp_03/) |
| **04** | **Car Mileage Calculator** | `TextEditingController`, Form Validation, Mathematical Computation | [Launch](./exp_04/) |
| **05** | **ShopEase Multi-Screen Navigation** | `Navigator.push / pop`, Route Passing, Model Passing | [Launch](./exp_05/) |
| **06** | **StudentHub SQLite CRUD** | `sqflite`, `sqflite_common_ffi_web`, In-browser SQLite WASM | [Launch](./exp_06/) |
| **07** | **StudentHub Cloud (Firestore)** | `cloud_firestore`, `firebase_core`, Realtime Cloud Sync | [Launch](./exp_07/) |
| **08** | **Student Search Engine** | Cloud Firestore Queries, `StreamBuilder`, Reactive Search | [Launch](./exp_08/) |
| **09** | **Student Record Update** | Firestore Document Updating, Modal Form Dialogs | [Launch](./exp_09/) |
| **10** | **Secure Student Auth** | SHA-256 Crypto Hashing (`crypto`), Password Verification | [Launch](./exp_10/) |

---

## ⚙️ Automated GitHub Pages Hosting (GitHub Actions)

This repository includes a pre-configured CI/CD workflow at [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) that automatically:
1. Clones and sets up the latest stable Flutter SDK.
2. Compiles all 10 Flutter experiments for the web (`flutter build web --base-href ./`).
3. Bundles them alongside the master portal (`index.html`).
4. Deploys directly to **GitHub Pages**.

### Enabling GitHub Pages in Your Repo:
1. Push this repository to your GitHub account:
   ```bash
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git branch -M main
   git push -u origin main
   ```
2. On GitHub, navigate to **Settings** → **Pages** (under "Code and automation").
3. Under **Build and deployment** → **Source**, select **GitHub Actions**.
4. The deployment workflow will trigger automatically and host all 10 experiments live!
