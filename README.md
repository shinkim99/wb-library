# JARVIS Workbench

R&D 프로그램 관리 대시보드. 프로그램의 Module/Skill 구조를 관리하고, AI(Claude/GPT/Gemini)로 자동 분석합니다.

## 실행 방법

```
index.html 더블클릭 → 브라우저에서 바로 열림
```

Node.js, npm, 빌드 과정 불필요. 순수 HTML 파일 하나.

## 주요 기능

- **프로그램 관리**: 파일 드래그로 등록, Rev 자동 버전 관리
- **AI 분석**: 코드를 AI가 분석하여 Module/Skill 자동 등록
- **멀티 AI**: Claude, GPT, Gemini 중 선택하여 사용
- **GitHub 가져오기**: URL 입력으로 공개 저장소 구조 자동 분석
- **워크벤치 관리**: 프로그램을 워크벤치별로 그룹화
- **다크/라이트 모드**

## Claude Code로 수정

```powershell
cd P:\projects\jarvis-workbench
claude
> index.html에서 에러 목록에 심각도 컬럼 추가해줘
```

## 회사/집 동기화

```powershell
# 최초 설정
git clone https://github.com/YOUR_USERNAME/jarvis-workbench.git

# 작업 후 푸시
git add . && git commit -m "update" && git push

# 다른 PC에서 당기기
git pull
```
