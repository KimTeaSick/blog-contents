---
title: "안전관리 - 건설현장 안전 교육/관리 앱"
description: "React Native 기반 안전 교육 체크 및 작업 프로세스 UX 개선 프로젝트"
date: "2024-03-18"
tags: ["React Native", "Styled-Components", "Redux Toolkit", "Performance"]
github: ""
demo: ""
---

## Overview

건설현장에서 사용하는 안전 관리/교육 앱으로, 많은 체크리스트와 UI 요소들을 다루는 복잡한 모바일 환경을 개선한 프로젝트입니다.

## Key Features

- **React Native를 이용한 앱을 구현**
  - 건설현장을 고려해 직관적이고 상대적으로 크기가 큰 안드로이드 키오스크에 사용하기위해서 **React-Native**로 작업.
- **관심사 분리를 통한 코드 가독성 증가 및 유지보수 용이성 상승**
  - 기존의 컴포넌트는 기능, UI, 상태가 한 곳에 관리, 해당 컴포넌트를 커스텀 훅과 기능, UI가 분리되도록 관심사 별로 분리.
  - 중복된 코드를 줄여, 중복되거나 불필요한 서버의 요청을 없애. 반복되던 네트워크 요청 빈도를 **30%** 감축.
- **교육항목에 대한 모달 데이터를 pre-loading으로 가져와 사용자의 원활한 교육과정 지원**
  - 작업 등록 기능 중 사용자가 충분한 안전 교육을 진행 했는 지 확인하는 모달을 preloading으로 import.
  - 100개가 넘는 확인 항목을 모듈에서 분리해 성능향상 및 사용자 경험을 개선.
- **기존 하나였던 redux InitialState를 tookit 적용과 용도에 맞는 initialState로 나누어 코드의 복잡성을 감소**
  - 하나의 state에서 모든 상태를 관리하고 있는 레거시 코드를 관심사를 분리하여 리팩토링
  - 하나의 initialState가 분리되면서 중복된 코드의 감소

## Tech Stack

React Native, Styled-Components
