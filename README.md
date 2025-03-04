# Project_Edu_System

## Description
- 교육을 위한 시스템을 구축하기 위한 사이트
- 핵심적인 기본기 위주의 시스템 구축을 목표
- [목표]: 기본적인 학습역량(암기력, 이해력, 분석력, 적응력) 습득
- 국어(문해력, 정보탐색력) / 수학(논리력, 수식이해력) / 과학(적용력, 탐구력) / 영어(문해력, 정보탐색력) / 코딩(문제해결력, 사고력) / 경제(정리력, 분석력) / 법률(체계화, 규칙력) / 심리학(이해력, 홍보력) / 체육(체력, 인내심) / 음악(침착함)
- 각 분야별 검증 시스템 도입(자격증)
- 단계별 최소 기준 존재, 최대 제한 없음
- 나이 제한 없음
- 커뮤니티내 나이 무관하게 상호 존대


## Rule
- 프로젝트 규칙은 진행하며 추가될 수 있음

#### Version
1. version 명은 v0.0.0으로 시작
2. major는 대규모 프로젝트 변경, minor는 기능 추가시 변경, patch는 사소한 변경 사항 및 오류 수정시 변경
3. 문서는 projectName_docType_version_date로 작성
- projEdu_UIDesign_v0.0.0_20250302.pptx

#### Gi Branch 전략
1. 소규모일 때는 GitHub Flow 전략
- main과 feature, hotfix만 사용
- main(출시 버전), feature(기능 추가), hotfix(오류 및 수정사항)

2. 규모가 커진 후 Git Flow 전략
- main, develope, feature, release, hotfix 사용
- main(major 기준의 브랜치), develope(main에서 분기된 개발을 위한 main 역할) feature(기능 추가), release(develope 완료후 출시), hotfix(오류 및 수정사항)


#### Git Commit Message
1. 
```
[feat] content
(branch): main
- detail content

# issue_id
```
- feat:

## Codint Style Guide

#### HTML
- 들여쓰기는 4칸
- layer 구조는 semantic tag 사용. ex) header, main, footer, aside, section, article
- tag는 반드시 닫혀 있어야 함. 단일 태그의 경우 마지막에 /(슬래쉬) 사용
- 2개 이상의 tag는 div로 묶기
- html 속성 사용시 태그명, class, id 이외에는 알파벳 순서로 정렬
- script 태그는 body의 마지막에 배치

#### CSS
- 들여쓰기는 4칸
- 색상값은 변수를 활용하여 작성
- html 태그 순서에 맞추어 css 작성

#### JavaScirpt
- 들여쓰기는 4칸
- 변수명은 camelCase, 메서드명도 camelCase
- 클래스명은 PascalCase
- 파일명은 PascalCase
