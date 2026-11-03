# lab

**검증 사다리와 그 적용 — 공공데이터 · 트레이딩 · 제조**
*A validation ladder and what it was tested on.*

한 가지 방법을 서로 다른 분야에 걸어 보는 실험실이다. 방법은 단순하다: **통과 조건을 결과보다 먼저 적고, 시험 횟수를 미리 정하고, 봉인 자료는 한 번만 열고, 틀린 것은 장부에 남긴다.**

This repo holds the method and the ledgers of what survived — and what did not.

## 구성

| 폴더 | 내용 |
|---|---|
| [`verify/`](verify) | 검증 방법론. 트레이딩 아이디어를 시험하는 사다리, 기초작업 표준, 기각 기록의 구조 |
| [`gnindexlab/`](gnindexlab) | 경남인덱스랩. 경남 공공데이터를 매달 비교 가능한 글로 만드는 파이프라인 |

처음 읽는다면 [`verify/validation_ladder_v1.md`](verify/validation_ladder_v1.md) 부터.

## 공개 원칙

- **방법과 기각 기록은 공개한다. 실전 값(조건·문턱·크기)은 공개하지 않는다.**
- 이 폴더의 모든 커밋은 올리기 전 자동 검사를 통과해야 한다. 인증 정보나 서버 정보가 걸리면 커밋 자체가 막히고, 막힌 기록만 별도 장부에 남는다.
- 기각된 가설은 지우지 않는다. 같은 질문을 두 번 시험하지 않게 해 주기 때문이다.

## 작성자

박영수 (Youngsu Park) — 26년차 신문기자. 경남 지자체를 출입하며 공공데이터와 알고리즘 트레이딩 검증을 함께 다룬다.
