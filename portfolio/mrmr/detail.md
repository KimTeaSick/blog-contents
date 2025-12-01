---
title: "MRMR - 음성 기반 SNS"
description: "음성 기반 피드·플레이어 UI·SNS 로그인 기반 하이브리드 앱"
date: "2024-04-01"
tags: ["React Native", "Recoil", "Styled-Components", "Firebase"]
github: ""
demo: ""
---

## Overview

MRMR은 음성 기반의 SNS 서비스입니다. 음성으로 이루어진 피드를 업로드하여 공유하는 React Native 기반의 어플리케이션으로, 구독, 보관, 좋아요 상태에 따라 다양한 UI를 제작하였습니다.

## Key Features

- **sytled-component를 이용한 css-in-js 방식 UI 개발**
  - CSS를 사용할 수 없는 **React-Native**환경에서 기존의 React개발과 유사하게 UI작업을 할 수 있는 styled component를 이용해서 작업.
- **React Native를 이용한 IOS, Android 하이브리드 앱 개발**
  - React Native를 사용해 각 OS 정책, OS 기본 UI에 대한 차이를 고려한 하이브리드 앱 개발 진행.
- **Recoil의 atom, selector을 이용한 state관리**
  - 디자인과 기획, 개발을 동시에 진행
  - 때문에 디자인 변동이나, 기능 정의 변경이 많았고, Redux 보다 유연하게 대응 할 수 있는 **recoil**로 개발을 진행.
- **firebase를 이용한 naver, facebook 로그인 구현**

## Tech Stack

React Native, Styled-Components, Recoil, Firebase
