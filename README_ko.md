# CKS 실전 모의고사 02

## 언어

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![CKS 실전 모의고사 02](https://course-cover.labex.io/cks-practice-exam-02.png?lang=ko)](https://labex.io/ko/courses/cks-practice-exam-02)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/ko/courses/cks-practice-exam-02)

공식 CKS 시험 범위를 포괄하는 다양한 운영 보안 시나리오를 바탕으로, 20 개의 쿠버네티스 보안 챌린지로 구성된 두 번째 독립형 CKS 실전 모의고사입니다.

![kubernetes](https://img.shields.io/badge/kubernetes-whitesmoke?style=for-the-badge&logo=kubernetes)
![cks](https://img.shields.io/badge/cks-whitesmoke?style=for-the-badge&logo=cks)


## 연습

|   인덱스 | 이름                                 | 난이도   | 연습                                                                                                                                        |
|-------|------------------------------------|-------|-------------------------------------------------------------------------------------------------------------------------------------------|
|    01 | 🎯  워크로드의 노드 메타데이터 접근 차단            | 중급    | <a target='_blank' href='https://labex.io/ko/labs/deny-workload-access-to-node-metadata-663200?course=cks-practice-exam-02'>도전 시작</a>     |
|    02 | 🎯  Kubelet 노출에 대한 CIS 결과 검토        | 중급    | <a target='_blank' href='https://labex.io/ko/labs/review-cis-findings-for-kubelet-exposure-663211?course=cks-practice-exam-02'>도전 시작</a>  |
|    03 | 🎯  분할 Ingress 경로를 위한 TLS 재발급       | 중급    | <a target='_blank' href='https://labex.io/ko/labs/reissue-tls-for-a-split-ingress-route-663206?course=cks-practice-exam-02'>도전 시작</a>     |
|    04 | 🎯  네임스페이스 오퍼레이터 역할 범위 지정           | 중급    | <a target='_blank' href='https://labex.io/ko/labs/scope-a-namespace-operator-role-663214?course=cks-practice-exam-02'>도전 시작</a>           |
|    05 | 🎯  유출된 ServiceAccount 토큰 격리        | 고급    | <a target='_blank' href='https://labex.io/ko/labs/contain-a-leaked-serviceaccount-token-663199?course=cks-practice-exam-02'>도전 시작</a>     |
|    06 | 🎯  API 서버 프록시 권한 상승 차단             | 고급    | <a target='_blank' href='https://labex.io/ko/labs/block-api-server-proxy-escalation-663197?course=cks-practice-exam-02'>도전 시작</a>         |
|    07 | 🎯  호스트 디버그 서비스 비활성화                | 중급    | <a target='_blank' href='https://labex.io/ko/labs/disable-a-host-debug-service-663202?course=cks-practice-exam-02'>도전 시작</a>              |
|    08 | 🎯  호스트 로그 수집기 권한 제한                | 중급    | <a target='_blank' href='https://labex.io/ko/labs/restrict-host-log-collector-permissions-663210?course=cks-practice-exam-02'>도전 시작</a>   |
|    09 | 🎯  테넌트 Pod 보안 경계 적용                | 중급    | <a target='_blank' href='https://labex.io/ko/labs/apply-tenant-pod-security-boundaries-663196?course=cks-practice-exam-02'>도전 시작</a>      |
|    10 | 🎯  애플리케이션 시크릿 (Secret) 교체 및 제한     | 중급    | <a target='_blank' href='https://labex.io/ko/labs/rotate-and-constrain-application-secrets-663212?course=cks-practice-exam-02'>도전 시작</a>  |
|    11 | 🎯  DNS 예외를 통한 테넌트 이그레스 (Egress) 격리 | 고급    | <a target='_blank' href='https://labex.io/ko/labs/isolate-tenant-egress-with-dns-exceptions-663204?course=cks-practice-exam-02'>도전 시작</a> |
|    12 | 🎯  웹 파드에서 HostPath 캐시 제거           | 중급    | <a target='_blank' href='https://labex.io/ko/labs/remove-hostpath-cache-from-a-web-pod-663208?course=cks-practice-exam-02'>도전 시작</a>      |
|    13 | 🎯  신뢰할 수 있는 이미지 레지스트리 강제 적용        | 고급    | <a target='_blank' href='https://labex.io/ko/labs/enforce-trusted-image-registries-663203?course=cks-practice-exam-02'>도전 시작</a>          |
|    14 | 🎯  서명된 릴리스 매니페스트 검증                | 중급    | <a target='_blank' href='https://labex.io/ko/labs/validate-a-signed-release-manifest-663215?course=cks-practice-exam-02'>도전 시작</a>        |
|    15 | 🎯  이미지에서 빌드 시크릿 제거하기               | 고급    | <a target='_blank' href='https://labex.io/ko/labs/remove-build-secrets-from-an-image-663207?course=cks-practice-exam-02'>도전 시작</a>        |
|    16 | 🎯  KubeLinter 를 사용한 Helm 출력물 스캔    | 중급    | <a target='_blank' href='https://labex.io/ko/labs/scan-helm-output-with-kubelinter-663213?course=cks-practice-exam-02'>도전 시작</a>          |
|    17 | 🎯  감사 증적을 통한 정책 복구                 | 중급    | <a target='_blank' href='https://labex.io/ko/labs/restore-policy-from-audit-evidence-663209?course=cks-practice-exam-02'>도전 시작</a>        |
|    18 | 🎯  비컨 (Beaconing) 워크로드 격리          | 고급    | <a target='_blank' href='https://labex.io/ko/labs/quarantine-a-beaconing-workload-663205?course=cks-practice-exam-02'>도전 시작</a>           |
|    19 | 🎯  런타임 파일 드리프트 탐지                  | 중급    | <a target='_blank' href='https://labex.io/ko/labs/detect-runtime-file-drift-663201?course=cks-practice-exam-02'>도전 시작</a>                 |
|    20 | 🎯  손상된 작업 토큰 격리                    | 고급    | <a target='_blank' href='https://labex.io/ko/labs/contain-a-compromised-job-token-663198?course=cks-practice-exam-02'>도전 시작</a>           |

## LabEx 소개

[LabEx](https://labex.io) 는 코딩과 기술에 전념하는 대화형 실습 학습 플랫폼입니다. 실험실, AI 지원 및 가상 머신을 결합하여 비디오 없는 실용적인 학습 경험을 제공합니다. 비디오 없는 독점적인 실습 실험실로 엄격한 '실습을 통한 학습' 접근 방식, 브라우저 내 대화형 온라인 환경에서 자동화된 단계별 확인, 스킬 트리 기반 시스템으로 구조화된 콘텐츠 구성, 30 개의 스킬 트리와 6,000 개 이상의 실험실을 포함하는 성장하는 학습 리소스로, [LabEx](https://labex.io) 는 종합적인 실습 교육을 제공합니다. 플랫폼에는 최신 AI 모델을 기반으로 구축된 학습 도우미 Labby 가 포함되어 대화형 학습 경험을 제공합니다.

## 더 보기

- 🔗 [CKS 교육 프로그래밍 코스](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [CKS 교육 프로그래밍 프로젝트](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [CKS 교육 무료 튜토리얼](https://github.com/labex-labs/cks-free-tutorials)

