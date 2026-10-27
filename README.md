# Acting with World Models

Website for the proposed CVPR 2027 workshop **Acting with World Models: When to Imagine, How to Act, and How to Recover**.

- Website: [awm-workshop.github.io](https://awm-workshop.github.io/)
- Organization: [awm-workshop](https://github.com/awm-workshop), displayed as **Acting with World Models**
- Repository: [awm-workshop/awm-workshop.github.io](https://github.com/awm-workshop/awm-workshop.github.io)

The workshop remains at the proposal stage. Acceptance, the exact workshop slot, talk titles, and submission policies are pending. The lineup comprises five tentative speakers and one confirmed speaker, **Dongfang Liu**, alongside eight organizers and eight confirmed program committee members.

The preliminary four-hour program contains six 20-minute invited-talk slots, each with a 15-minute presentation and 5 minutes of Q&A. Poster discussion and the debate each receive 30 minutes. Final timing remains subject to CVPR scheduling.

## Publishing

GitHub Pages publishes the `main` branch from the repository root. `index.html` is the complete static website with styles, scripts, fonts, portraits, and the 9-second robot animation embedded. `.nojekyll` disables Jekyll processing. No build dependencies or API keys are needed to serve this version.

## Editing

The editable multi-file source is preserved in `actionwm-source.zip`; this filename is retained for compatibility. Its top-level folder is `awm-workshop.github.io/`. Extract it to update the page, rosters, and assets. The source includes a video-capable local preview server and an optional official GitHub Actions workflow that deploys `dist/`. The current repository instead uses the self-contained root page described above.

After editing, regenerate `index.html` and the source archive, then replace both in this repository. Any push to `main` updates the Pages website.

## Assets

Robot geometry is from Google DeepMind MuJoCo Menagerie's Franka Panda model under Apache-2.0. The studio scene and animation illustrate the workshop topic and are not experiment footage. Font, model, and portrait attribution records are retained in the source archive and embedded page; see `THIRD-PARTY-NOTICES.md`.
