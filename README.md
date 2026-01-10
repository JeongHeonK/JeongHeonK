# 김정헌

**Frontend Developer**

산업용 X-ray 영상 처리 도메인에서 Canvas 기반 인터랙티브 Tool을 개발하고, 대용량 영상 데이터 최적화를 통해 **렌더링 100% 개선(30fps → 60fps), 메모리 60% 감소**를 달성한 프론트엔드 개발자입니다.

## 💼 경력

| 기간 | 회사 | 역할 |
|------|------|------|
| 2025.03 ~ 현재 | SNUAILAB | SW 개발팀 (프론트엔드) |
| 2024.08 ~ 2024.11 | 또박또박 | RN 개발 |

## 🛠 기술 스택

| 카테고리 | 기술 |
|----------|------|
| Framework | Next.js 15, Vite 6 |
| Language | TypeScript 5.7+ |
| UI | React 19, Tailwind CSS 4, Radix UI |
| State | Zustand 5, TanStack Query 5 |
| Canvas | Konva.js, React-Konva |
| Real-time | Socket.IO |
| Image | GeoTIFF, OpenCV.js |

## 🚀 Projects

### 배터리 셀 X-ray 검사 Tool

배터리 셀 X-ray 영상에서 불량을 검출하고 AI 모델을 학습하는 Segmentation Labeling Tool

- Canvas 렌더링 최적화: Konva.js 레이어 분리 → **30fps → 60fps** → 검사 작업 시간 30% 단축
- 메모리 최적화: Zustand useShallow + 도메인별 Store 분리 → **메모리 60% 감소** → 장시간 작업 안정성 확보
- 번들 최적화: Next.js 15 Dynamic Import → **2.6MB → 1.8MB (30%↓)** → 초기 이탈률 15% 개선
- Auto Labeling: gzip 압축 → **377ms → 18ms (95%↓)** → 라벨링 사용성 증가

### 배터리 셀 X-ray Super Resolution Tool 고도화

Denoising + 해상도 향상 파이프라인 UI 및 Label 기반 위치 정보 학습 기능 개발

- Vector 기반 드로잉: Konva.js Vector Polygon → **메모리 70% 감소** → 저사양 PC 안정 구동
- OpenCV.js WASM: 클라이언트 영상처리 → **프로토콜 정의 시간 50% 단축** → 개발 일정 단축
- Socket 통신 안정화: SSE → Socket.IO migration → **리스너 40개 → 4개** → 메모리 안정화

### Super Resolution 결과 뷰어

Low → High → HR+ → HR++ 4단계 영상 품질 비교 UI

- 상태 관리 아키텍처: Zustand 10개 도메인별 Store 분리 → 코드 가독성 50% 향상
- API 코드 최적화: 커스텀 훅 + 제네릭 타입 → API 관련 코드 70% 감소
- 대용량 영상: 타일링 + 레벨별 캐싱 → 16K 영상 실시간 렌더링
- E2E 테스트 인프라: Playwright + Page Object Model → **84개 테스트 작성** → QA 프로세스 효율화
- 이미지 목록 가상화: TanStack Virtual + 스크롤바 UX 개선 + 파일명 토글/접근성 → **DOM 88% 감소** → 검사 작업 사용성 개선

### License Manager

SNUAILAB 소프트웨어 라이선스 발급 및 관리 시스템

- FSD 아키텍처: 4-Layer + 단방향 의존성 → 201개 파일 재구성, 탐색 범위 83% 감소
- 대용량 테이블 가상화: TanStack Virtual → **1,000ms → 30ms (97%↓)** → 데이터 크기 무관 일정한 성능
- 타입 안전 라우팅: TanStack Router → 컴파일 타임 라우트 검증
- MSW 기반 개발: API 모킹 → 백엔드 대기 시간 제거

### 또박또박 - 한국어 발음 교정 앱

한국어 발음 교정 앱의 호흡 훈련 탭 개발

- Layout 초기화: useLayoutEffect + cleanup → 초기 로드 안정화
- 다중 애니메이션 동기화: Moti 선언적 애니메이션 + setTimeout cleanup → 4단계 호흡 시퀀스 안정적 구현

## 🤝 Cross-Functional

- **Backend Collaboration**: Socket.IO 프로토콜 정의 주도, API Response 직접 설계
- **Design Context**: 디자이너 없이 Radix UI 기반 UI/UX 직접 설계
- **AI-Augmented**: Claude Code로 프로젝트 3개 동시 진행, 생산성 3배 향상

## 📫 Contact

[![Email](https://img.shields.io/badge/Email-kdrlawjdgjs%40gmail.com-blue)](mailto:kdrlawjdgjs@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-JeongHeonK-black)](https://github.com/JeongHeonK)
