---
title: "MFR - 얼굴 인식 기반 출입 등록 WebApp"
description: "TensorFlow 기반 얼굴 인식 + 촬영 자동화 + Pass 인증을 이용한 출입 등록 서비스"
date: "2024-01-10"
tags: ["React", "Redux", "CSS", "WebApp"]
github: ""
demo: ""
---

## Overview

MFR은 얼굴 등록을 통한 출입 등록 시스템으로 TensorFlow를 이용한 얼굴 인식 WebApp 입니다. 카메라와 TensorFlow를 사용해 로딩 시간이 긴 컴포넌트를 lazy loading, preloading을 구현하여 사용자 경험을 개선했습니다. Pass인증을 통해 본인 인증하는 기능과 Fold, Flip 등 디바이스 크기가 다른 기기를 이용할 때도 동일한 경험을 위한 UI를 제작하였습니다.

## Key Features

- **TensorFlow를 이용한 얼굴인식 기능 제작**
  - TensorFlow를 이용해 눈, 코, 입, 귀가 인식 위치에 들어왔을 때 3초간의 카운터 후 사진을 촬영하는 프로세스를 제작.
- **lazy loading으로 초기 js 번들 크기를 대폭 감소 (20% 이상)**
  - 카메라와 TensorFlow를 사용하는 컴포넌트를 lazy loading 초기 js번들의 크기를 **20%** 감소 시킴.
  - 번들의 크기 감소로 초반 로딩 속도가 1.2s에서 0.8s 로 30% 감소

## Tech Stack

React, Redux, CSS
