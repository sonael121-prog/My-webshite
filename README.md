# 📘 NotebookLM 활용 블루오션 직무 분석 및 배포 보고서

## 📌 
- **학번:** [202678055]
- **이름:** [손아엘]
- **🚀 웹 사이트 배포 주소(URL):** [https://sonael121-prog.github.io/My-webshite/]

---

## 1. GitHub Pages 개념 정리
GitHub Pages는 GitHub 저장소(Repository)에 있는 HTML, CSS, JavaScript 파일을 직접 웹 브라우저에 호스팅하여, 전 세계 누구나 접속할 수 있는 무료 정적 웹 사이트로 배포해 주는 서비스입니다. 
- **장점:** 별도의 서버 인프라 구축이나 비용 지불 없이, GitHub 계정과 저장소 설정만으로 몇 분 만에 나만의 웹 페이지를 전 세계에 공개할 수 있습니다.
- **작동 원리:** `main` 혹은 `master` 브랜치에 `index.html` 파일을 포함한 소스 코드를 push하면, GitHub Actions가 자동으로 빌드 및 배포 과정을 수행하여 고유한 URL 주소를 생성합니다.

---

## 2. 웹 페이지 제작 및 배포 과정 

### Step 1. NotebookLM을 통한 직무 분석 및 HTML 생성
1. **내용 생성:** NotebookLM에 관련 자료를 업로드한 뒤, **'블루오션 직무 Top 3 분석', '진로를 위한 핵심 역량', '커리어 로드맵'**에 대한 심층 데이터를 추출 및 정리했습니다.
2. **코드 구현:** 추출한 텍스트 데이터를 기반으로 가독성이 높고 구조화된 웹 페이지를 만들기 위해 HTML/CSS 코드를 작성하였습니다. (메인 파일명: `index.html`)

### Step 2. GitHub 저장소(Repository) 생성 및 파일 업로드
1. GitHub에 로그인한 후 새로운 Public 저장소를 생성했습니다.
2. 로컬에서 작업한 `index.html` 파일을 해당 저장소에 업로드(Commit & Push)했습니다.

#### 📸 [배포 과정 캡처 1] GitHub 저장소 파일 업로드 현황
> <img width="976" height="548" alt="image" src="https://github.com/user-attachments/assets/4636c554-7191-45f8-80ed-87e7334d225e" />

### Step 3. 오류 해결
1. HTML 파일에 CSS, JS 까지 같이 작성, 오류 발생
2. 각각 `script.js`, `style.css` 파일에 나누어 작성하여 오류 해결

---

## 3. 웹 사이트 배포 결과 
GitHub Pages를 통해 성공적으로 웹 사이트가 상용 인터넷에 배포되었습니다. 

#### 📸 [배포 결과 캡처] 실제 브라우저 접속 화면
<img width="1918" height="957" alt="배포결과" src="https://github.com/user-attachments/assets/56d6afa5-db73-4184-8ac6-e6a2e5bdaabe" />

---

## 5. 과제 수행 느낀점 
예전 인텔리제이를 통해서 웹사이트 만들기를 해봤던 경험 때문에 HTML 파일 안에 JS, CSS 한번에 넣어도 된다고 생각했었습니다. 
AI를 활용하여 탬플릿을 찾지 않아도 훨씬 빠르게 작업수행이 빨라졌다는 것에 놀랐습니다.
개발환경을 구축하지 않고도 전 세계에 내가 만든 페이지를 공유할 수 있는 오픈소스 생태계의 편리함을 체감했으며, 향후 포트폴리오나 프로젝트를 관리할 때도 GitHub Pages를 적극적으로 활용하면 좋겠다고 느꼈습니다.
