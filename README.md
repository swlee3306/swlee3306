# 이상욱 · Cloud Platform & Go Backend

인프라에서 수집한 데이터를 믿을 수 있는 API와 운영 도구로 만드는 개발자입니다.
Go, OpenStack, Kubernetes를 중심으로 자원 수집·관측성·배포와 개발 자동화를 다룹니다.
반복 작업을 줄이는 것뿐 아니라, 실패했을 때 원인을 찾고 같은 조건으로 다시 검증할 수 있는 구조를 중요하게 생각합니다.

I build infrastructure backends and automation tools with explicit state, observable failures, and reproducible checks.

## Selected work

| 프로젝트 | 살펴볼 문제와 설계 | 상태 |
| --- | --- | --- |
| [infra-orch-studio](https://github.com/swlee3306/infra-orch-studio) | OpenStack plan·승인·apply 흐름, API/runner 분리, 상태·감사 기록 | 플랫폼 프로젝트 |
| [network-collector](https://github.com/swlee3306/network-collector) | OpenStack 수집, Go API, 네트워크 토폴로지와 React UI | 관측성 프로젝트 |
| [gitlab-mr-review-automation](https://github.com/swlee3306/gitlab-mr-review-automation) | GitLab 읽기 전용 연동, 중복 방지, 오래된 커밋 차단, 재시도·작업 소유권 | 범용 reference implementation |
| [gitops-deployment-guardrails](https://github.com/swlee3306/gitops-deployment-guardrails) | Kubernetes 설정 검사와 변경 계획, 값 노출 없는 결과 | 범용 CLI |
| [ai-company-os](https://github.com/swlee3306/ai-company-os) | 작업·승인·실행 증거를 연결하는 Go CLI/API와 웹 UI | 로컬 실험 프로젝트 |
| [make-snmprec](https://github.com/swlee3306/make-snmprec) | SNMP 수집 결과를 시뮬레이션 입력으로 변환 | 네트워크 도구 |

## Where to start

- **플랫폼 설계:** infra-orch-studio의 [탐색 안내](https://github.com/swlee3306/infra-orch-studio/blob/main/docs/PORTFOLIO.md)에서 상태 전이와 검증 경로를 확인할 수 있습니다.
- **관측성 데이터 흐름:** network-collector의 [탐색 안내](https://github.com/swlee3306/network-collector/blob/001-openstack-monitoring/docs/PORTFOLIO.md)에서 collector → 저장소 → API → UI를 확인할 수 있습니다.
- **계정 없이 실행:** 두 Python 자동화 도구는 합성 예제로 실행할 수 있습니다. 실제 외부 연동과 오프라인 검증 범위를 README에서 구분합니다.

## Engineering focus

`Go` · `OpenStack` · `Kubernetes` · `Infrastructure APIs` · `Observability` · `SNMP` · `Automation`

공개 코드·테스트로 확인할 수 있는 내용을 중심으로 설명합니다. 예제의 검증 결과를 실제 운영 규모나 성능 보장으로 확대하지 않습니다.

[프로젝트와 개발 기록](https://swlee3306.github.io/sulee_portfolio/) · [전체 저장소](https://github.com/swlee3306?tab=repositories)
