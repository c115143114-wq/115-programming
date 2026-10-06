# AGENTS.md

- Greenfield coursework repo for 計算機程式 (currently just `README.md` + Python `.gitignore`).
- 專案語言為 Python；一律使用 conda 管理套件，環境名稱為 `iem_python`（如 `conda run -n iem_python python ...`）。不要改用 venv / Poetry / uv / pip 直接安裝。
- No source, manifests, lockfiles, tests, lint, CI, or `opencode.json` as of `e39ff8a`. Do not assume any build/test/package manager beyond conda.
- `.gitignore` is the standard Python template only; it does not imply a chosen Python version or dependency tool. Check what actually gets added before running anything.
- 所有回應一律使用繁體中文。
