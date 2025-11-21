# Final Project Repositories of Mobile Development 2024/2025 Members

This repository aggregates ten member final project repositories maintained as Git submodules. Each submodule is a complete Flutter mobile project (some include backend services) produced by members of the Mobile Development Academic Division at Google Developer Group on Campus: Universitas Sriwijaya (GDGoC: UNSRI).

This central repo is intended as an index and convenient workspace for reviewing, running, and contributing to the member projects. See [.gitmodules](.gitmodules) for upstream URLs and paths.

---

## Final Projects List

Each entry below links to the submodule (project) README so you can open that project directly.

- [GreenTasker-Bintara/README.md](https://github.com/jazhardcore7/green-tasker/blob/main/README.md) — GreenTasker by [Ahmad Bintara Mansur](https://github.com/jazhardcore7)  
    SDG: 13 — Climate Action  
    Gamified eco-quests where users complete sustainability tasks, upload proof photos and earn XP to level up.

- [EcoTrack-Dayana/README.md](https://github.com/Dayana-K-H/EcoTrack-Application/blob/main/README.md) — EcoTrack by [Dayana Khoiriyah Harahap](https://github.com/Dayana-K-H)  
    SDG: 12 — Responsible Consumption and Production  
    Tracks users' consumption habits and provides eco-feedback and history for sustainable choices.

- [ForgetMeNot-Fachry/README.md](https://github.com/githubbingry/FinalProjectGDG/blob/main/README.md) — ForgetMeNot by [Fachry Ghifary](https://github.com/githubbingry)  
    SDG: 3 — Good Health & Well‑Being  
    Gamified reminder and accountability app where friends/gatekeepers help each other remember tasks with playful penalties, reminders and mini-games.

- [NutriSight-Abel/README.md](https://github.com/FarhanAbelRantisi/NutriSight-App/blob/main/README.md) — NutriSight by [Farhan Abel Rantisi](https://github.com/FarhanAbelRantisi)  
    SDG: 3 & SDG 12 — Good Health & Well‑Being, Responsible Consumption  
    Nutrition-label scanner that extracts nutrient information (OCR + NER) and computes a Nutri‑Grade (A–D) with a hosted API available for classification.

- [LinguaPanel-Haikal/README.md](https://github.com/FrxHaikalPlg/FinalProjectGDG/blob/main/README.md) — LinguaPanel by [M Haikal Ash Shiddiq](https://github.com/FrxHaikalPlg)  
    SDG: 4 — Quality Education  
    Manga-panel translator: Flutter mobile app with a FastAPI backend that detects speech bubbles, runs OCR and LLM-based translation, and renders translated text back to images.

- [EspressYoSelf-Rizki/README.md](https://github.com/rizkisepriadi/Express_yo_self_Final_Project/blob/main/README.md) — Espress Yo Self by [M. Rizki Sepriadi](https://github.com/rizkisepriadi)  
    SDG: 12, SDG 3 & SDG 13 — Responsible Consumption, Good Health & Well‑Being, Climate Action  
    Coffee shop loyalty & rewards app with QR scanning, eco-bonuses and a digital stamp/rewards system. See contributing notes at [EspressYoSelf-Rizki/CONTRIBUTING.md](https://github.com/rizkisepriadi/Express_yo_self_Final_Project/blob/main/CONTRIBUTING.md).

- [HabiVault-Arief/README.md](https://github.com/ariefff666/HabiVault-Final/blob/main/README.md) — HabiVault by [Muhammad Arief Pratama](https://github.com/ariefff666)  
    SDG: 3, SDG 4 & SDG 8 — Good Health, Quality Education, Decent Work & Economic Growth  
    A "Life RPG" habit/skill tracker that gamifies daily missions and skill progression with XP and leveling systems.

- [GymBros-Suheil/README.md](https://github.com/MuhammadSuheil/GymBros/blob/main/README.md) — GymBros by [Muhammad Suheil Ichma Putra](https://github.com/MuhammadSuheil)  
    SDG: 3 — Good Health & Well‑Being  
    Cross-platform workout tracker to log exercises, sets, reps and visualize progress with history and analytics.

- [BluBlu-Najwa/README.md](https://github.com/najwaainayah/Final-Project/blob/main/README.md) — BluBlu by [Najwa Ainayah](https://github.com/najwaainayah)  
    SDG: 4 & SDG 6 — Quality Education & Clean Water and Sanitation  
    An education-first app to raise awareness on water conservation with tips, challenges and daily goals.

- [Askmedia-Syakillah/README.md](https://github.com/Chwakillah/askmedia-id/blob/main/README.md) — Askmedia (Askademia) by [Syakillah Nachwa](https://github.com/Chwakillah)  
    SDG: 4 — Quality Education  
    A student-focused Q&A/forum app for campus knowledge-sharing, posts, comments, bookmarks and informational feeds.

---

## Quickstart — open and run a project locally

1. Initialize and fetch submodules once:
```sh
git submodule update --init --recursive
```

2. Open the submodule folder you want to work on in your editor (for example, VS Code):  
   - [GymBros-Suheil/README.md](https://github.com/MuhammadSuheil/GymBros/blob/main/README.md)  
   - [EspressYoSelf-Rizki/README.md](https://github.com/rizkisepriadi/Express_yo_self_Final_Project/blob/main/README.md)  
   - ...and so on (see list above).

3. For Flutter projects:
   - Install dependencies:
     ```sh
     flutter pub get
     ```
   - Add platform-specific config files as instructed in each submodule README (e.g., `google-services.json`, `GoogleService-Info.plist`).
   - Run:
     ```sh
     flutter run
     ```
   - For web builds, check each submodule's `web/index.html` and use `flutter build web` as needed.

4. Consult an individual submodule's README for project-specific environment variables, backend endpoints, or Docker files (e.g. LinguaPanel backend).

---

## Acknowledgements

- Projects were supervised and evaluated by the Core Team of the Mobile Development Academic Division: ([M. Fazri Nizar](https://github.com/mfazrinizar)).
- Thanks to all members as contributor for their work on these final projects.

---

## Maintenance & Contact

- This repository is an index of submodules and does not replace the canonical upstream repositories listed in [.gitmodules](.gitmodules). For issues, pull requests, or licensing questions, open them in the appropriate upstream submodule repository (URLs are in [.gitmodules](.gitmodules) and each submodule README).
- For repository-level questions, contact the Mobile Development Core Team: [M. Fazri Nizar](https://github.com/mfazrinizar).

---

## License

Each submodule may have its own license. This aggregator repository does not alter those licenses — consult each submodule README and license file for details.
