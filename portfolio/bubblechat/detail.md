---
title: "버블챗 - AI 캐릭터 대화 서비스"
description: "Emotion 마이그레이션·디자인 시스템 고도화·Vite SSR 제작"
date: "2024-09-22"
tags: ["React", "TypeScript", "Emotion", "Vite SSR", "Design System"]
github: ""
demo: "https://poptale.ai/recommend"
---

## Overview

캐릭터와 AI 모델을 기반으로 상호작용하는 대화형 서비스입니다.

## Key Features

- **styled component에서 emotion으로 마이그레이션 주도**
  - styled component의 서비스가 종료되고, 사용중이던 MUI와의 잦은 충돌을 해결하기 위해 styled-components를 emotion으로 마이그레이션 작업
  - 컴포넌트 호환성 검증, 기존 테마 구조 분석 및 import 변환 스크립트 작성 등 **마이그레이션 프로세스 전반을 주도적으로 설계 및 실행**
- **design system 고도화**
  - default stories를 만들어주는 스크립트를 작성해서, 일괄적이고 표준적인 디자인 시스템 기반을 구축
  - 다양한 형태로 분산되어 있던 컴포넌트를 Atomic한 형태의 폴더 구조로 변경 및 모노레포로 관리
- **vite SSR 기능 제작**
- **태국, 대만, 일본어를 지원하는 서비스를 제작**
  - i18next 기반 번역 파이프라인을 도입하여 **3개국 서비스 동시 서비스 지원**

## Tech Stack

React, Typescript, Styled-Component, Emotion, Vite
