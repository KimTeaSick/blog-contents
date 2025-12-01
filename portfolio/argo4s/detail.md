---
title: "ARGO 4S - 자동 매매 웹 서비스"
description: "Next.js + FastAPI 기반 자동 매수·매도 시스템"
date: "2025-12-01"
tags: ["Next.js", "FastAPI", "SQLAlchemy", "React Query"]
github: ""
demo: ""
---

## Overview

ARGO 4s 는 사용자가 설정한 조건에 따라 검색된 코인을 매수하고 매도하여 수익을 창출하는 웹 사이트입니다.
이 프로젝트에서는 프론트엔드와 백엔드를 담당하여 개발했습니다.

## Key Features

- **캐싱과 직관적 코드를 위해 react-query를 통한 비동기 상태 관리**
  - 직관적인 상태관리와 캐싱을 통해 네트워크 통신을 최적으로 관리하기 위해 **react query** 도입.
  - 로컬 상태는 **redux toolkit**으로 관리. 코인, 검색 조건, 매매 조건, 유저 정보로 분리하여 관리.
- **컴포넌트 재 사용을 위해 Headless Component를 이용한 UI 종속성 제거**
  - 중복된 기능의 컴포넌트 생성을 방지하고자 **headless** 기법을 이용해 기능과 UI를 분리.
- **fastAPI를 이용한 API Server개발**
  - sqlarchemy를 이용해 **orm** 으로 DB에 접근하여 데이터를 가공, 조회, 수정 작업을 진행
  - jwt를 이용한 로그인을 back과 front 모든 과정을 구현.
  - 스케줄링 모듈을 제작해 사용자에게 **40%** 이상 더 빠른 데이터 제공.
- **Bithumb Open Api를 이용한 기능 개발**

## Tech Stack

Next.js, Typescript, Tailwind, FastAPI, mySQL, AWS Linux
