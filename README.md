# Sparse · Hybrid Attention 데이터 이동 — 약식 화면

모델별 attention 층 1개 · decode 1스텝에서 데이터가 HBM · 칩 안 메모리 · 연산기 사이를 어떻게 오가는지 커널 단위로 보는 HTML.

- 파일 하나에 다 들어 있음 — 서버 없이 브라우저로 바로 열림
- 화면 위 모델 이동 칩 = 같은 폴더 상대 경로 → GitHub Pages · 파일로 열기 모두 사외망 없이 동작 (글꼴만 Google Fonts)

| 모델 | 파일 |
|---|---|
| 기준선 · DeepSeek-V3.1 | [viewer/mla-v31-lite.html](viewer/mla-v31-lite.html) |
| Sparse · DeepSeek-V3.2 | [viewer/dsa-v32-lite.html](viewer/dsa-v32-lite.html) |
| Sparse · DeepSeek-V4-Flash | [viewer/csa-v4flash-lite.html](viewer/csa-v4flash-lite.html) |
| Hybrid · Kimi K3.1 Pro (KDA + DSA) | [viewer/kda-k3-lite.html](viewer/kda-k3-lite.html) |
| Hybrid · Qwen3.8-Flash-Next (GDN + QSA) | [viewer/qsa-qwen38-lite.html](viewer/qsa-qwen38-lite.html) |
| Hybrid · Qwen3.6-27B (GDN 층) | [viewer/gdn-qwen36-lite.html](viewer/gdn-qwen36-lite.html) |

- 사내 GitHub로 옮겨 Pages 링크로 공유하는 법: [DEPLOY-INTERNAL.md](DEPLOY-INTERNAL.md)
- 원본: [llm-arch-lineage-wiki](https://github.com/KimHyeon-Ji/llm-arch-lineage-wiki) `arch_insight/dataflow-claude` (위키 커밋 `099e77b`)
- 이 저장소는 원본의 `tools/export_repo.py`가 매번 새로 채움 → 여기서 직접 고치지 않음
