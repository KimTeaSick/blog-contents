---
title: "길벗 AIDT - 중학교 정보 디지털 교과서"
description: "AI 기반 디지털 교과서 with 알고리즘 체험 UI"
date: "2024-06-27"
tags: ["React", "Styled-Components", "TypeScript", "Interactive UI"]
github: ""
demo: ""
---

## Overview

길벗 사의 중학교 정보 교과서의 AI 디지털 교과서를 제작. 학생들이 읽고 교육하는 읽기 페이지와 교육 내용을 직접 활동으로 배워보는 활동 페이지 제작.

## Key Features

- **알고리즘 게임 직접 구현**
  - 큐를 이용한 알고리즘 탐색하기 게임을 제작
  - 사용자가 명령어 박스에 넣은 명령어를 순차적으로 꺼내서 게임에 반영
  - 내부 로직을 리엑트 커스텀 훅으로 분리하여 관심사를 분리, 심화 게임에서도 동일한 훅을 사용해서 코드의 복잡도를 낮춤
- **다양한 인터랙티브 UI 구현**
  - 교육환경에서 다양한 디바이스를 사용할 것을 고려
  - 모달과 비디오 플레이어, 카드 뉴스 등 styled component theme 를 사용해서 디바이스 사이즈에 맞게 조절

## Tech Stack

React, TypeScript, Styled-Components
