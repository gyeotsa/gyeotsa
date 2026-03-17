<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&height=300&color=gradient&text=Jeong%20Jiwon%20&fontColor=000000&animation=twinkling&reversal=false)

<p align="center">
  <a href="mailto:ice31842@gmail.com"><img src="https://img.shields.io/badge/Gmail-d14836?style=for-the-badge&logo=Gmail&logoColor=white"/></a>
</p>

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=gyeotsa&show_icons=true&theme=radical"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gyeotsa&layout=compact&theme=dracula"/>
</p>

Skills
<p align="center">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-00599C?style=for-the-badge&logo=python&logoColor=FFD400"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/PID Control-000000?style=for-the-badge&logo=PID&logoColor=white"/>
  <img src="https://img.shields.io/badge/Sensor Processing-005C84?style=for-the-badge&logo=Sensor&logoColor=white"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Arduino-039BE5?style=for-the-badge&logo=Arduino&logoColor=white"/>
  <img src="https://img.shields.io/badge/RaspberryPi-039BE5?style=for-the-badge&logo=RaspberryPi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matlab-039BE5?style=for-the-badge&logo=MATLAB&logoColor=white"/>
  <img src="https://img.shields.io/badge/Simulink-039BE5?style=for-the-badge&logo=Simulink&logoColor=white"/>
</p>

📚 Working In Progress
<p align="center">
  <img src="https://img.shields.io/badge/Algorithms-FF6B6B?style=flat-square&logo=TheAlgorithms&logoColor=white"/>
  <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white"/>
</p>

<!--
<details>
<summary>More About Me</summary>
<br>

🎯 Current Focus
• Advanced Game Programming Patterns<br>
• Graphics Programming with DirectX 11<br>
• Unity Performance Optimization<br>
• Problem Solving on BOJ

🏆 Goals for 2024
• Master Unity DOTS<br>
• Develop Portfolio Projects<br>
• Improve Algorithm Skills

</details>
-->
<details>
<summary>Git 컨벤션 가이드</summary>
<div markdown="1">

# Git 컨벤션 가이드

## 📋 개요

이 문서는 evespimrose의 프로젝트에서 사용하는 Git 커밋 컨벤션을 정의합니다. 일관된 커밋 메시지 작성으로 프로젝트 히스토리를 명확하고 추적 가능하게 만듭니다.

## 🏷️ 커밋 메시지 형식

### 기본 형식
```
[타입] 제목

선택적 본문

선택적 푸터
```

### 예시
```
[Feat] 플레이어 이동 시스템 구현

- 조이스틱 컨트롤러 추가
- 애니메이션 상태 머신 연동
- 물리 기반 이동 구현

Closes #123
```

## 📝 커밋 타입

### 🚀 기능 관련
- **`[Feat]`**: 새로운 기능 추가
- **`[Enhance]`**: 기존 기능 개선
- **`[Add]`**: 새로운 파일, 리소스 추가

### 🐛 버그 수정
- **`[Fix]`**: 버그 수정
- **`[Hotfix]`**: 긴급 버그 수정

### 📚 문서화
- **`[Docs]`**: 문서 수정, 추가
- **`[Readme]`**: README 파일 수정
- **`[Comment]`**: 코드 주석 추가/수정

### 🎨 UI/UX
- **`[UI]`**: 사용자 인터페이스 변경
- **`[UX]`**: 사용자 경험 개선
- **`[Style]`**: 스타일, 디자인 변경

### 🔧 설정 및 환경
- **`[Config]`**: 설정 파일 수정
- **`[Build]`**: 빌드 관련 변경
- **`[Deps]`**: 의존성 추가/제거

### 🧹 코드 정리
- **`[Refactor]`**: 코드 리팩토링
- **`[Clean]`**: 코드 정리, 불필요한 코드 제거
- **`[Optimize]`**: 성능 최적화

### 🧪 테스트
- **`[Test]`**: 테스트 코드 추가/수정
- **`[Debug]`**: 디버깅 관련 변경

### 📦 배포
- **`[Release]`**: 릴리즈 준비
- **`[Deploy]`**: 배포 관련 변경

## 📏 제목 작성 규칙

### ✅ 좋은 예시
```
[Feat] 고객 AI 상태 머신 구현
[Fix] 빵 생성 시 메모리 누수 해결
[Docs] API 문서 업데이트
[UI] 메인 메뉴 디자인 개선
```

### ❌ 나쁜 예시
```
[feat] 고객 AI 구현
[Fix] 버그 수정
[Docs] 문서 수정
[UI] UI 개선
```

### 제목 작성 가이드라인
1. **50자 이내**로 작성
2. **동사 원형**으로 마침 (구현, 추가, 수정, 삭제 등)
3. **마침표 사용 지양**
4. **(영문)대문자로 시작**
5. **명확하고 구체적으로** 작성

## 📄 본문 작성 규칙

### 본문이 필요한 경우
- 커밋의 **의도와 배경** 설명
- **변경 사항의 상세 내용**
- **Breaking Changes** 설명
- **관련 이슈 번호** 언급

### 본문 작성 가이드라인
1. **72자마다 줄바꿈(지향)**
2. **왜(Why)** 변경했는지 설명
3. **어떻게(How)** 변경했는지 설명
4. **영향 범위** 명시

### 예시
```
[Feat] 고객 대기열 시스템 구현

- QueueManager 클래스 추가로 대기열 관리
- 포장/매장 식사 고객 구분 처리
- 대기열 위치 자동 조정 기능
- 고객 상태에 따른 우선순위 관리

Resolves #45
```

## 🏷️ 푸터 작성 규칙

### 이슈 참조
```
Closes #123
Fixes #456
Resolves #789
```

### Breaking Changes
```
BREAKING CHANGE: API 구조 변경으로 인한 호환성 문제
- 기존 메서드명 변경: getData() → fetchData()
- 새로운 필수 파라미터 추가
```

### Co-authored-by
```
Co-authored-by: John Doe <john@example.com>
```

## 🎯 Unity 프로젝트 특화 규칙

### 에셋 관련
```
[Asset] 새로운 3D 모델 추가
[Prefab] 플레이어 프리팹 업데이트
[Scene] 메인 씬 레이아웃 변경
[Script] Player 컨트롤러 스크립트 수정
```

### 네임스페이스 관련
```
[BakerySim.Core] GameManager 로직 개선
[BakerySim.Customer] AI 행동 패턴 수정
[BakerySim.Bakery] 상호작용 시스템 개선
```

### 컴포넌트 관련
```
[Component] Rigidbody 설정 최적화
[Animation] 플레이어 애니메이션 추가
[Audio] 사운드 매니저 구현
[UI] 인벤토리 UI 개선
```

## 📋 커밋 전 체크리스트

### ✅ 필수 확인사항
- [ ] 커밋 타입이 적절한가?
- [ ] 제목이 명확하고 구체적인가?
- [ ] 50자 이내로 작성되었는가?
- [ ] 동사 원형으로 시작하는가?
- [ ] 마침표가 없는가?

### ✅ 선택적 확인사항
- [ ] 본문이 필요한가?
- [ ] 관련 이슈가 있는가?
- [ ] Breaking Changes가 있는가?
- [ ] 테스트가 필요한가?

## 🔄 브랜치 전략

### 브랜치 명명 규칙
```
feature/기능명
bugfix/버그명
hotfix/긴급수정명
docs/문서명
refactor/리팩토링명
```

### 예시
```
feature/customer-ai-system
bugfix/bread-spawn-memory-leak
hotfix/critical-crash-fix
docs/api-documentation
refactor/player-movement
```

## 📊 커밋 히스토리 예시

### 좋은 커밋 히스토리
```
[Feat] 고객 AI 상태 머신 구현
[Add] 빵 제조 시스템 추가
[UI] 메인 메뉴 디자인 개선
[Fix] 메모리 누수 문제 해결
[Docs] README 문서 업데이트
[Refactor] 코드 구조 개선
```

### 나쁜 커밋 히스토리
```
[feat] 고객 AI
[add] 빵 시스템
[ui] 메뉴 개선
[fix] 버그 수정
[docs] 문서 수정
[refactor] 코드 정리
```

## 🛠️ 도구 및 설정

### Git Hooks 설정
```bash
# 커밋 메시지 검증
#!/bin/sh
commit_regex='^\[(Feat|Fix|Docs|UI|Refactor|Test|Build|Config|Clean|Optimize|Enhance|Add|Hotfix|Style|UX|Deps|Release|Deploy|Debug)\] .{1,50}$'

if ! grep -qE "$commit_regex" "$1"; then
    echo "❌ 커밋 메시지 형식이 올바르지 않습니다."
    echo "✅ 형식: [타입] 제목 (50자 이내)"
    exit 1
fi
```

### IDE 설정
- **VSCode**: GitLens 확장 사용
- **IntelliJ**: Git 커밋 템플릿 설정
- **Sublime**: Git 커밋 메시지 스니펫

## 📚 참고 자료

- [Conventional Commits](https://www.conventionalcommits.org/)
- [Angular Git Commit Guidelines](https://github.com/angular/angular/blob/main/CONTRIBUTING.md#commit)
- [Udacity Git Commit Message Style Guide](https://udacity.github.io/git-styleguide/)

---

## 🎯 핵심 원칙

1. **일관성**: 모든 커밋에서 동일한 형식 사용
2. **명확성**: 변경 사항을 명확하게 표현
3. **간결성**: 필요한 정보만 포함
4. **추적성**: 이슈와 연결하여 추적 가능
5. **가독성**: 팀원이 쉽게 이해할 수 있도록 작성

이 컨벤션을 따르면 프로젝트의 Git 히스토리가 깔끔하고 이해하기 쉬워집니다! 🚀

</div>
</details>
</div>
