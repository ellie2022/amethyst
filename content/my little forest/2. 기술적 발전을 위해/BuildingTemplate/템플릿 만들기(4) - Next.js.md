---
title:  {"title"}
date: "2023-02-21 14:33:06 "
tags: 
aliases: 
---
### 다시 Mindstone으로

결국 다시 Mindstone으로 돌아왔다.
로컬서버에 돌리기 위해서

    $ npm install --global yarn



이번에는 제대로 기초부터 스터디해 나갈 생각이다.
이 템플릿은 Next.js 기반이므로 일단 Next.js를 공부한다.

### 설치

일단 설치를 한다 :

    $ npx create-next-app my-litte-forest --use-npm

    $ cd my-little-forest

    $ ls
    README.md      next.config.js  package-lock.json  pages/   styles/
    next-env.d.ts  node_modules/   package.json       public/  tsconfig.json

이제 VS code로 열어본다 :

    $ code .

![[vs-code-new-wksp.png]]

VS code의 내부 터미널을 열고 서버를 띄워 본다 :

    npm run dev

![[vc-code-run-dev.png]]

기본 페이지가 뜨는데, 아이콘은 public 폴더안에 있다.
특히 favicon.ico는 크롬 탭에 보이는 아이콘인 것 같다.

![[fabicon-image.png]]


### 유레카!

딱 나에게 필요한 템플릿을 찾았다!
Hugo라는 프레임워크를 이용해 만들어진 [Amethyst](https://amethyst.bencuan.me/)
라는 템플릿이다. 

그래서 템플릿 찾기의 긴 여정(?, 방황)을 끝내고 아메씨스트로 정착하기로 한다. [[아메시스트 템플릿 ]]

