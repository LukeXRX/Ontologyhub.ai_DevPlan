# OntologyHub.ai — Development Blueprint

웹 기반 개발 기획서 사이트입니다.

## 배포 방법

### 방법 1: Vercel CLI (가장 빠름)
```bash
npm i -g vercel
cd ontologyhub-blueprint
vercel login
vercel deploy --prod
```

### 방법 2: Vercel Dashboard
1. https://vercel.com/xs-projects-0338e358 접속
2. "Add New Project" → "Import Third-Party Git Repository" 또는 직접 업로드
3. Framework: "Other" 선택
4. Output Directory: "public" 입력
5. Deploy 클릭

### 방법 3: GitHub 연동
1. 이 폴더를 GitHub 저장소에 push
2. Vercel에서 Import
3. 자동 배포 완료
