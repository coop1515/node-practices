Node Practice

1. 패키지(pacakge)
- 완전한 어플리케이션(nodemon, babel, webpack)
- 프로젝트에서 사용하는 모듈(라이브러리)

2. 의존성(Dependency)
- 개발하는 프로젝트(어플리케이션, 라이브러리)에서 설치하고 사용하는 패키지
- 일반 의존성
    개발하고 있는 프로젝트에서 사용하는 패키지로 꼭 빌드와 배포에 포함되어야 한다.
    $[project-ex01] npm i ...

- 개발 의존성
    개발에 필요하거나 도움이 되는 패키지(Dev, Tools)로 빌드와 배포에 포함되지 않음.
    $[project-ex01] npm i -D ...

3. 패키지 설치
    1. 전역(global) 설치: 에러 프로젝트에서 공용으로 사용하는 도구
    2. 지역(local) 설치: 특정 프로젝트에서 종속적인 도구나 라이브러리
    3. 패키지 설치 ex)
        npm i ejs [local install, general dependency]
        npm i -D nodemon [local install, dev dependency]
        npm i -g gulp [global install, general dependency]
            npx gulp --version
    3-2. 패키지 삭제 예제)
        npm un ejs [local install 삭제]
        npm un -g gulp [global install 삭제]
            npx gulp --version

4. Node(JavaScript) Project 생성
    1) 프로젝트 생성(mkdir)
    2) 프로젝트 이름(cd)
    3) 프로젝트 초기화: 프로젝트 매니페스트(manipest) 파일인 package.json을 생성
        $[project-ex02] npm init -y

5. Module
    1. 코어 모듈: node에서 제공하여 주는 모듈(fs, os, .....)
    2. 파일 모듈: 파일 경로로 불러와서 모듈안의 함수, 객체를 사용한다.
    3. npm 모듈: npm을 통해서 node_modules에 설치하고 사용하는 모듈
        - 원격배포
        - 로컬배포
6.
7.
8.