# LEARNINGS

## 2026-09-23 公開前

- 入口を `index.html` にし、旧名 `torishirabe.html` は転送だけ残した
- viewport にピンチズーム抑止を入れ、ダブルタップと長押しメニューを文書全体で止めた
- 本文欄はスクロールが要るので、`touch-action` は `manipulation` のままにした
- 開始ボタンが背面のボタンより先に来るようにした。背面のボタンを先にタップすると、全面オーバーレイの下で検査が止まる
- harness: PASS（Canvas 320×180、61 RAF/秒）。証跡 `docs/harness-reports/254-torishirabeshitsu-2352-2026-09-23T06-33-22-641Z.md`
