# soc-detection-lab — 공격 재현 + 탐지 룰 랩

> 🚧 진행 중 (예정 공개: 2026-12-20)

## 개요
- 목적: 웹 공격을 랩에서 재현하고 로그로 탐지 룰 작성
- 겨냥 직무: 보안관제·탐지 엔지니어링

## 아키텍처
(DVWA/Apache + Splunk 구성도)

## 핵심 결과
- 탐지 시나리오 N개 / 탐지율 __% / 오탐 사례 __건
- 대시보드 스크린샷

## 실행 방법
```bash
docker compose -f lab/docker-compose.yml up -d
```

## 상세 문서
- attacks/<시나리오>/재현절차.md, detections/splunk/*.spl, detections/sigma/*.yml, reports/

## 배운 점

## 법적 고지
격리된 로컬 랩에서만 수행했습니다.
