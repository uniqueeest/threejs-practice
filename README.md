# Three.js Practice Starter

간단한 회전 큐브 씬으로 시작할 수 있는 Vite + Three.js 기본 템플릿입니다. 이 프로젝트를 바탕으로 다양한 실험을 자유롭게 추가해 보세요.

## 필요 조건
- Node.js 18+
- npm 10+

## 명령어
| 명령어 | 설명 |
| --- | --- |
| `npm install` | 의존성 설치 |
| `npm run dev` | 개발 서버 (기본 포트 5173) |
| `npm run build` | 프로덕션 번들 생성 |
| `npm run preview` | 빌드 결과 확인 서버 |

## 프로젝트 구조
```
.
├── index.html          # 진입 HTML (Vite root)
├── src
│   ├── main.js         # Three.js 초기화 및 애니메이션 루프
│   └── style.css       # 전체 화면 캔버스 스타일
├── public              # 정적 자산 (필요 시 추가)
└── package.json
```

## 다음 단계 아이디어
1. OrbitControls 를 추가해 카메라를 자유롭게 움직여 보세요.
2. Geometry 를 분리해 여러 Mesh 를 배치하거나 GLTF 모델을 불러와 보세요.
3. dat.GUI 또는 lil-gui 를 붙여 파라미터를 실시간으로 조정해 보세요.

필요한 기능이나 설정이 있다면 언제든지 알려주세요!
