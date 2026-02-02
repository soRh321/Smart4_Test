# Smart4_Test
 AI기획4기 테스트
주요 커밋 헤더 타입 (Type) 
feat: 새로운 기능 추가 (feature)
fix: 버그 수정
docs: 문서 수정 (README, 주석 등)
style: 코드 포맷팅 (코드 변경 없음, 세미콜론 누락, 들여쓰기 등)
refactor: 코드 리팩토링 (기능 변경 없이 코드 구조 개선)
perf: 성능 향상 (Performance improvements)
test: 테스트 코드 추가/수정
build: 빌드 시스템, 외부 종속성 변경 (npm, gradle 등)
ci: CI 설정 파일 및 스크립트 수정
chore: 빌드 업무 수정, 패키지 매니저 설정 등 소스 코드/테스트 파일 수정 외 변경
revert: 커밋 되돌리기 
2. 헤더 구조 및 작성 규칙
형식: type(scope): subject
Scope (선택사항): 변경 사항이 적용되는 범위 (예: feat(api): ...)
Subject (제목): 변경 사항에 대한 짧은 설명
규칙:
제목은 50자 이내로 제한
첫 글자는 대문자로 시작하지 않음 (대부분의 툴링에서 소문자 권장)
마침표로 끝내지 않음
명령문 사용 (예: Add (O), Added (X)) 
3. 기타 유용한 커밋 헤더 (Gitmoji)
🎨 :art:: 코드 구조 개선
⚡️ :zap:: 성능 향상
🔥 :fire:: 코드/파일 제거
🐛 :bug:: 버그 수정
🚑 :ambulance:: 긴급 핫픽스
✨ :sparkles:: 새 기능
📝 :pencil:: 문서 수정
🚀 :rocket:: 배포 관련 
4. 접미사(!) 사용
feat(api)!: ...: 타입 뒤에 !를 붙이면 큰 변화(Breaking Change)를 의미하며, 호환성이 깨지는 변경 사항이 있음을 나타냅니다