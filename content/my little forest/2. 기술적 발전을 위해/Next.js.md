---
title:  {"title"}
date: "2023-02-21 14:35:07 "
tags: 
aliases:
---

### 개요 

- Vercel이 만든 open source React front-end framework
- UI와 정적 웹사이트를 만들 때 사용된다.
- 서버 사이드의 rendering 이나 범용 앱에도 사용가능
- UI를 생성하는데 JS와 React component를 사용
- 다른 프레임워크와 차별되는 특징은 페이지의 자동 생성 \
  프로젝트의 파일 구성에 의거해서 만들어짐\
  예를 들어, root 밑에 '\_posts' 라는 폴더가 있다면, Next.js는 폴더 내에 있는 각 markdown 파일을 위한 페이지를 만든다.
- 이 기능은 필요한 페이지를 수동으로 만들 필요가 없어져서 개발 시간을 줄여준다.
- 새로운 컨텐트가 추가될 때마다 자동으로 페이지를 생성해 내는 기능도 특별하다


### 장점

- 동적 기능을 포함하는 정적 웹사이트를 빠르게 만들 수 있다.
- 서버 사이드 rendering과 정적 웹사이트 생성 기능을 제공하기 때문에 SEO (Search Engine Optimization)에 탁월하다
- 스크린 사이즈와 무관하게 좋아 보이는 디자인을 보여준다.

### 단점

- 플러그인이 적다
- 라우팅 제약이 있다.
- 앱에 페이지가 많아지면 빌드시간이 매우 오래 걸린다.

### 주요 기능들
##### Pages : 
Next의 file routing system을 이용해서 페이지를 생성하고 이동할 수 있다.  File routing system을 이용하기 위해서는 'pages/first-post.js'를 만든다.  최초의 route는 통상 'pages/index.js'와 연관되어 있다.

##### 이미지 최적화 :
이미지 컴포넌트는 HTML 요소 'img'를 현대 웹을 위해 개선하고 확장한 개념이다.  디바이스와 무관하게 이미지 크기를 변경하고, 이미지가 보여야 하는 경우에만 이미지를 로드하게 해 준다.

##### TypeScript 지원 :
Next.js는 기존 또는 신규 프로젝트에 모두 TypeScript를 통합할 수 있다.  특히 새로운 프로젝트를 만들 때는 TypeScript를 위해 어떤 설정도 할 필요가 없다.

##### 지원 브라우저 :
IE11을 포함해서 모든 현대 브라우저 지원가능하다. 

##### 데이터 가져오기 :
Next.js에는 두가지 렌더링이 가능하다.
1. Static Generation : \
   빌드할 때 HTML 페이지가 생성되고, CDN이 캐시되고, 요청될 때 이미 빌드된다.
2. Server-side Rendering :\
   이 경우, 동적 페이지가 생성되고 요청시마다 render된다.

##### 레이아웃 :
만일 Navbar와 Footer가 매 페이지마다 필요하다면 이것을 매 페이지마다 넣을 필요가 없다.  Next는 페이지를 컴포넌트로 만들게 해준다.  Navbar와 Footer를 컴포넌트로 wrapping 하면 된다.



### 좀더 찾아볼 주제 :
JavaScript와 TypeScript

#기술일반
