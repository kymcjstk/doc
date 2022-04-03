Vue.js 개발가이드_v0.1

제/개정 이력
0.1 - 신규 - 2022.04.01 

목차
1. 개발환경 구성 (Nomal)
1.1. Node-js 설치
1.2. vue-cli 설치
1.3. vue.js devtool설치
1.4. JAVA환경 Eclipse vueJs설정 및 구동
2. Vue.js 특성 및 장점
2.1. 특성 및 장점기술
3. Vue.js 기본 샘플개발
3.1. Create 화면개발 및 서버통신/처리
3.2. Read 화면개발 및 서버통신
3.3. List 화면개발 및 서버통신
3.4. Read 화면내에서 Delete 서버통신/처리

가이드 내용
1. 개발환경 구성
1.1. Node-js 설치
- https://nodejs.org/en/download/ 다운로드 및 설치 후,  cmd/console환경에서 설치버전확인 node -v
1.2. vue-cli 설치
- 대규모 애플리케이션 구축시, NPM를 이용한 설치를 권장하며, Webpack등 번들러 작동 및 싱글파일 컴포넌트 생성 도구도 제공함으로 설치
- npm install vue, -npm install -g vue-cli, -npm install -g @vue/cli -> 설치 후, vue --version 확인
1.3. vue.js devtool설치 (개발환경보안상, 기본개발환경이외 별도 Plugin등은 인터넷접속환경에서 설치불가대응필요)
- Visual Studio Code 환경 + Plugin (Vetur, Vue Snippets,Vue-beautify, Volar...등), 각 환경내 마켓설치 또는 파일다운로드 후, package수동설치
- Eclipse 종류 환경 + Plugin ( CodeMix, GWT...등), 각 환경내 마켓설치 또는 파일다운로드 후, package수동설치
- WebBrowser 환경 Debugging ( chrome Extension - Vue.js devtools ), 별도 해당 CRX파일을 다운로드 후, chrome Extension관리에서, 압축해제된 확장 프로그램을 로드 또는 CRX파일 실행설치
- CRX파일 다운로드 방법참조: 1)확장프로그램 정보내, 프로그램ID/설치URL복사 2)https://crxextractor.com/ 등 CRX다운로드에서, CRX다운로드 및 압축저장  (확장프로그램을 수동설치가능)
1.4. JAVA환경 Eclipse vueJs설정 및 구동
- Eclipse SpringBoot Gradle Project Create
- Eclipse Workspace 내, 폴더에서 Vue-Cli 프로젝트 생성, 
- vue create "프로젝트명(폴더)" "--no-git", 설치옵션 선택 후, 설치완료
- 프로젝트 생성 후, 프로젝트실행, npm run serve (프로젝트생성 폴더내에서나 해당 경로지정)
- vue.config.js 설정파일내, 빌드결과 파일위치, index위치, 서버연결url주소 등 설정
- 프로젝트 빌드, npm run build

2. Vue.js 특성 및 장점
2.1. 특성 및 장점기술
- MVVM 패턴의 VIew 모델형 화면단 라이브러리
- View(DOM) - ViewNodel(Vue) - Model(Javascript Objects)
- DOM의 변경 내역을 즉시 반응하여 특정 로직이 수행가능한 장치 와 View내용이 Model과 동기화처리 (Angular, React 기능을 포함)
- 화면을 라이브러리처리로 재사용, 구현속도, 가독성 높임(Angular, React 비슷함),  단, 소스문법 및 개발접근성이 높아 개발이 용이함
- 효용성/처리속도/가독성측면 - Angular <= Vue < React

3. Vue.js 기본 샘플개발
3.1. Create 화면개발 및 서버통신/처리
- 소스파일 참조 
3.2. Read 화면개발 및 서버통신
- 소스파일 참조
3.3. List 화면개발 및 서버통신
- 소스파일 참조
3.4. Read 화면내에서 Delete 서버통신/처리
- 소스파일 참조
