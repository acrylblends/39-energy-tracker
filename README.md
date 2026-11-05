# Energy Tracker

Building-level energy usage tracker that compares consumption periods, estimates cost from an indicative tariff and records manual meter readings.

An ACRYL Blends blueprint for the **Energy** category (`acrylblends.energy-tracker`, category 39 of 100).

Status: designed, being built. `design/spec.md` is the specification and `design/mockup.html` the mockup (open it in a browser). The app itself,
composed from Cordis plugins (one `plugins/<feature>/` folder and one `blend.yaml` row per feature), lands here when it passes review.

When it is ready you will start it with:

```sh
npm create acrylblends@latest my-app -- --from acrylblends.energy-tracker
cd my-app && npm install && npm run dev
```

Listed on https://acrylblends.github.io/blends and https://acryl.dev/blends.
