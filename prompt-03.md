# ELITE-RADAR (V3) - SYSTEM-AKTIVIERUNG

Führe einen Echtzeit-Scan für die unten stehende Watchlist basierend auf der 6-Stufen-Matrix durch. 
HALTUNG: Absolute Ehrlichkeit (Regel 0). Behauptungen müssen durch Live-Daten/Quellen belegt werden.

---

## ⚙️ SYSTEM-KONFIGURATION
"monitoring_config": {
  "active_radar": true,
  "quality_threshold": 7,
  "last_full_scan": "2026-04-09",
  "earnings_mode": "daily_on_event",
  "malus_active": "dilution_gt_5_percent",
  "historical_backtest": "enabled_2008_2025",
  "hallucination_prevention": "forced_source_verification",
  "timestamp_requirement": "strict_live_data"
}

---

## 🎯 DEFINITION: DIE 6-STUFEN-MATRIX
1. PREIS: 5-20 USD.
2. SILENT RECOVERY: R&D >15%, Bruttomargen-Trend positiv.
3. GAAP-PIVOT: Net Income Trend Richtung Profitabilität.
4. INSTITUTIONAL: Insider-Käufe/Besitz stabil.
5. HYPER-SCALE: NDR >120% oder starkes organisches Wachstum.
6. HÄRTETEST: Share Dilution <5% p.a., Runway >18 Monate.

---

## 📋 WATCHLIST ZUM SCANNEN
Ticker: SOFI, HIMS, S, NU, SOUN, ACHR, RELY.

---

## 📤 OUTPUT-FORMAT (STRENGSTENS EINHALTEN)
1. Erzeuge ein JSON-Objekt "watchlist_results" als Text-String (kein Code-Block!), das für jeden Ticker Preis, Quelle, Zeitstempel, Score und Kaufzonen enthält.
2. Erzeuge ein JSON-Objekt "historical_matches" als Text-String (kein Code-Block!), das die DNA-Ähnlichkeit zu historischen Giganten (z.B. CRM, CRWD, CELH) zeigt.
3. Schreibe die Analyse der Ähnlichkeiten und die fundamentale Begründung als freien Text (Prosa) unter die JSON-Strings.