# Deploy delta for HyperNoesis/uni (main)
67 files = only what changed vs. live main. Verified on top of live main: pnpm install --frozen-lockfile, tsc, next build all pass.
1. Unzip. On GitHub: HyperNoesis/uni > Add file > Upload files.
2. Drag the contents (apps/, packages/, docs/, package.json, README.md) into the page. Folders keep their paths. Commit to main.
3. Render auto-deploys campus-ng-web / -api / -realtime. Check /healthz on api + realtime, then /play.
