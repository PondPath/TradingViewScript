# 📘 Indicator Library — Structure & Overview

This folder contains all custom Pine Script **indicators**, organized by type and theme. Each indicator is version-controlled and grouped for clarity, scalability, and reusability.

---

## 📂 Folder Structure
indicator/
│
├── momentum/
│   ├── pp-osc-pro/
│   ├── pond-stoch-pro/
│   ├── pond-advanced-macd/
│
├── trend/
│   ├── pond-ma-pro/
│
├── volatility/
│   ├── pond-multi-bb/
│   ├── pond-bbwp/
│
├── distribution/
│   ├── pond-hpdr/
│
├── structure/
│   ├── pond-pivot/

Each indicator lives in:
///indicator-name-v.pine
---

## 🧭 Category Definitions

| Category       | Description                                                       |
|----------------|-------------------------------------------------------------------|
| **momentum**   | Oscillators that track momentum shifts (e.g., RSI, MACD, Stoch)   |
| **trend**      | Indicators that define directional trends (e.g., MAs, ZLEMA)      |
| **volatility** | Tools measuring expansion/compression of price action             |
| **distribution** | Range-based or percentile bands (e.g., HPDR, confidence zones) |
| **structure**  | Indicators that identify pivots, swing points, or S/R levels      |

---

## ✅ Indicator List

### Momentum
- `pp-osc-pro`
- `pond-stoch-pro`
- `pond-advanced-macd`

### Trend
- `pond-ma-pro`

### Volatility
- `pond-multi-bb`
- `pond-bbwp`

### Distribution
- `pond-hpdr`

### Structure
- `pond-pivot`

---

## 🔄 Versioning Format

Each version lives in its own folder:
indicator///vX.X/-vX.X.pine

Example:
indicator/momentum/pond-stoch-pro/v1.9.1/pond-stoch-pro-v1.9.1.pine

