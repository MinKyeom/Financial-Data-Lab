# Financial-Data-Lab 📈

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/Framework-Quantitative%20Finance-green.svg" alt="Category">
  <img src="https://img.shields.io/badge/License-MIT-unassigned.svg" alt="License">
</p>

---

## English

### About The Project

**Financial-Data-Lab** is a financial data science laboratory dedicated to bridging the gap between quantitative finance theories and real-world market data. Instead of relying on intuition, this project focuses on implementing, backtesting, and validating various financial indicators and economic models through robust code.

### Key Features & Objectives

- **Theory Validation:** Implementing core financial concepts (e.g., Disparity Index, Momentum, Mean Reversion) using Python to verify their statistical and practical validity.
- **Multi-Angle Analytics:** Screening KOSPI/KOSDAQ market data through diverse quantitative lenses to filter high-probability trading setups.
- **Robust Engineering:** Building efficient, multi-threaded data pipelines equipped with proper exception handling, dual-layer timeouts, and exponential backoff retry mechanisms to handle large-scale API requests without freezing.

### Built With

- **Language:** Python
- **Data Sources:** `FinanceDataReader` (KRX, KOSPI, KOSDAQ)
- **Data Analysis:** `pandas`, `NumPy`
- **Concurrency:** `concurrent.futures` (ThreadPoolExecutor)

---

## Korea

### 프로젝트 소개

**Financial-Data-Lab**은 계량 금융(Quant) 이론과 실제 시장 데이터 사이의 간극을 좁히기 위한 금융 데이터 사이언스 연구소입니다. 단순한 직관이나 감에 의존하는 투자 대신, 코드를 통해 다양한 금융 지표와 경제 모델을 직접 구현하고, 백테스팅하며, 통계적으로 검증하는 데 중점을 둡니다.

### 주요 특징 및 목표

- **금융 이론 검증:** 파이썬을 이용해 핵심 금융 개념(이격도, 모멘텀, 평균 회귀 등)을 코드화하고 실제 시장에서의 유효성을 검증합니다.
- **다각도 시장 분석:** 다양한 정량적(Quantitative) 관점으로 코스피/코스닥 데이터를 스크리닝하여 확률 높은 트레이딩 셋업을 필터링합니다.
- **견고한 엔지니어링:** 대량의 API 요청 시 발생할 수 있는 네트워크 지연 및 차단(Deadlock) 문제를 해결하기 위해, 2중 타임아웃(Timeout) 및 백오프 재시도(Retry) 로직이 적용된 효율적인 멀티스레드 데이터 파이프라인을 구축합니다.

### 사용 기술 및 라이브러리

- **언어:** Python
- **데이터 소스:** `FinanceDataReader` (한국거래소 전종목 데이터)
- **데이터 분석:** `pandas`, `NumPy`
- **동시성 제어:** `concurrent.futures` (ThreadPoolExecutor)

---

## Getting Started / 시작하기

### Prerequisites

```bash
pip install finance-datareader pandas tqdm
```
