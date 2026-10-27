# ActionWM · Acting with World Models

Website for the proposed CVPR 2027 workshop **Acting with World Models: When to Imagine, How to Act, and How to Recover**.

- Website: https://actionwm.github.io/
- Organization: https://github.com/ActionWM

The workshop is at the proposal stage. Acceptance, the exact workshop slot, final attendance, and submission policies are pending. The planned lineup includes six tentative speakers, eight organizers, and eight confirmed program committee members. Talk slots remain preliminary.

## Publishing

GitHub Pages publishes the `main` branch from the repository root. `index.html` is the complete static website with its styles, scripts, fonts, portraits and 9-second robot animation embedded. `.nojekyll` disables Jekyll processing. No build dependencies or API keys are needed to serve this version.

## Editing

The editable multi-file source is preserved in `actionwm-source.zip`. Extract it to update the page, rosters and assets. The source includes a video-capable local preview server and an optional GitHub Actions deployment workflow for its `dist/` layout. The current published repository uses the self-contained root page instead.

After editing the source, regenerate the self-contained `index.html` and replace it in this repository. Any push to `main` updates the Pages website.

## Assets

Robot geometry is from Google DeepMind MuJoCo Menagerie's Franka Panda model, under Apache-2.0. The studio scene and animation illustrate the workshop topic and are not experiment footage. Font, model and portrait attribution records are retained in the source archive and embedded page; see `THIRD-PARTY-NOTICES.md`.
