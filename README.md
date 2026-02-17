# 김정헌

**Frontend Developer**

산업용 X-ray 영상 처리 도메인에서 Canvas 기반 인터랙티브 툴을 만듭니다.<br />
대용량 데이터와 실시간 UI 환경에서 병목을 찾고, 구조적으로 분리하고, 측정해서 개선하는 걸 좋아합니다.

## Tech

- **Core** · Next.js · React · TypeScript
- **State** · Zustand · TanStack Query/Router/Table
- **Visualization** · Konva.js · GeoTIFF · OpenCV.js (WASM)
- **Real-time** · Socket.IO

## Work

**SNUAILAB** SW 개발팀 · 2025.03 ~ 현재
**또박또박** RN 개발 · 2024.08 ~ 2024.11

### X-ray Segmentation Labeling Tool

배터리 셀 X-ray 불량 검출 + AI 학습용 라벨링 툴. 프론트엔드 설계 및 구현 주도.

- Konva.js 레이어 분리로 Canvas 렌더링 **30fps → 60fps**
- XOR 델타 인코딩 + RLE 압축으로 Undo/Redo 메모리 **2GB → 50MB**
- Bitmask 직접 구현 (Uint8Array + BFS), ML 파이프라인 UI, Auto Labeling

### X-ray Super Resolution Tool

고해상도 영상 Denoising + 해상도 향상 파이프라인 UI.

- OpenCV.js WASM 기반 클라이언트 영상처리로 실시간 프리뷰 구현
- Vector Polygon 드로잉 전환으로 메모리 70% 감소

### License Manager

소프트웨어 라이선스 발급/관리 시스템. FSD 4-Layer 아키텍처 설계.

- TanStack Virtual로 1,000건 테이블 **1,000ms → 30ms**
- MSW 기반 API 모킹으로 백엔드 의존성 제거

## Open Source

**[freeze](https://github.com/JeongHeonK/freeze)** · React exit animation 깜빡임 제거 라이브러리
Suspense "무한 Promise throw" 패턴으로 DOM 커밋 차단 · **0.88KB** gzip · 22개 테스트 (Lines 100%, Branch 84%)

**[Claude Code C# Plugin](https://github.com/JeongHeonK/c-sharp-custom-marketplace)** · 사내 C#/.NET팀 온보딩용 마켓플레이스 플러그인
7개 스킬 (Code Review·TDD·MVVM Generator 등) + 12개 Modern C# 규칙 · v1.8.0

## Side Project

**[Trade Log](https://github.com/JeongHeonK/trade-log)** · CRDT 기반 Offline-First 매매일지
Yjs + Dexie 이중 계층 아키텍처 · PWA · 서버비용 $0

## Blog

https://jeongheonk.github.io/blog/

React 디자인패턴, React 내부구조, JS 심화, TypeScript 챌린지 등 49개 아티클

## Contact

[![Email](https://img.shields.io/badge/Email-kdrlawjdgjs%40gmail.com-blue)](mailto:kdrlawjdgjs@gmail.com)
