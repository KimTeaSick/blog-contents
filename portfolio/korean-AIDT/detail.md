---
title: "국특원 AIDT - 특수학급 국어 디지털 교과서"
description: "접근성 중심 녹음·재생·하이라이팅 인터랙션 학습 플랫폼"
date: "2024-07-19"
tags: ["React", "Accessibility", "MediaDevice API", "Interactive UI"]
github: ""
demo: ""
---

## Overview

특수 학급을 위한 국어 교과서를 제작. 흥미를 유발하며 학습하기 위해 많은 활동을 위주로 구성되어 있습니다.

## Key Features

- MediaDevice API를 활용해 녹음·재생 모듈을 구현하고, 노래 진행에 맞춰 텍스트가 실시간으로 동기화되는 하이라이팅 기능을 제작
- 특수 학급을 위한 접근성 고려
  - 특수 학급를 위한 접근성을 고려하여 컴포넌트별로 aria-label을 적용해 역할을 명확히 정의, aria-index 기반의 컴포넌트 배치로탭 키를 통한 자연스러운 학습 흐름을 구현.
  - 또한 하이라이팅, 배속 조절 등 학습자의 상태와 학습 속도에 맞춘 인터랙티브 기능을 제공하여 개인별 학습 효율을 극대화.

## Tech Stack

React, JavaScript, TypeScript, Styled-Components
