---
layout: post
title:  "데드락"
date:   2022-04-14 14:49:24 +0900
categories: 운영체제
---
## 데드락 해결 방법
- 데드락 발생 필요조건 중 하나를 제거
  - exclusive use of resource
    - 모든 자원을 공유 허용, 현실적으로 ㅂㄹ가능
  - 선점 불가능한 리소스
  - hold and wait
  - circular waith