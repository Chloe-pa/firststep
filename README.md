# Inspyfold (Vite + TypeScript)

이 프로젝트는 기존 단일 HTML 파일을 **Vite + TypeScript** 구조로 분리한 버전입니다.

## 로컬 실행
```bash
npm install
npm run dev
```

## 빌드
```bash
npm run build
```

빌드 결과물은 `dist/`에 생성됩니다.

## GitHub Pages 배포 (가장 단순한 방식)
- `npm run build` 실행
- `dist/` 폴더 내용을 `gh-pages` 브랜치에 올리거나,
- 또는 `docs/` 방식으로 쓰고 싶다면 `dist/`를 `docs/`로 복사한 뒤 Pages 설정에서 `/docs`를 선택하세요.

> `vite.config.ts`에서 `base: './'`로 설정되어 있어 repo 경로와 무관하게 상대경로로 잘 뜹니다.
