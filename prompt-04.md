# 🚀 ELITE-RADAR (V3) – AUTONOMER DISCOVERY-MODUS

AKTIVIERUNG: Suche eigenständig am US-Markt nach Wachstumsaktien (5-20 USD), die das Potenzial zum Multibagger haben. 

---

## ⚙️ ENGINE-KONFIGURATION
"monitoring_config": {
  "active_radar": true,
  "discovery_mode": "autonomous_market_scan",
  "quality_threshold": 7,
  "last_full_scan": "2026-04-09",
  "earnings_mode": "daily_on_event",
  "malus_active": "dilution_gt_5_percent",
  "hallucination_prevention": "forced_source_verification",
  "timestamp_requirement": "strict_live_data"
}

---

## 🛠 DIE 6-STUFEN-MATRIX (FILTER-LOGIK)
Finde Aktien, die ALLE folgenden Kriterien erfüllen (nutze Live-Suche/Finanzdaten):
1. PREIS: 5 - 20 USD.
2. SILENT RECOVERY: Hohe R&D-Ausgaben (>15%) und steigende Bruttomargen.
3. FUNDAMENTAL PIVOT: Kurs auf GAAP-Profitabilität oder sinkender Nettoverlust.
4. INSTITUTIONAL: Stabiles Insider-Backing oder nennenswerte Akkumulation.
5. HYPER-SCALE: Starkes organisches Wachstum oder NDR >120%.
6. HÄRTETEST: Jährliche Verwässerung <5%, Cash-Runway >18 Monate.

---

## 📝 DISCOVERY-AUFTRAG
1. Scanne aktuelle Marktberichte, Quartalszahlen (2025/2026) und SEC-Filings.
2. Identifiziere die Top 5-7 Ticker, die diesen Score erreichen.
3. Führe für jeden Ticker einen DNA-Abgleich mit einem historischen Giganten durch (z.B. CRM 2009, NVDA 2016, SHOP 2018).

---

## 📤 OUTPUT-FORMAT (STRENGSTENS EINHALTEN)
Gib die Ergebnisse als ein Array von JSON-Objekten aus. Nutze den folgenden JSON-String-Aufbau (KEIN Code-Block für das JSON, nur Klartext-String im Markdown):

"watchlist_results": [
  {
    "ticker": "BEISPIEL",
    "price_usd": 0.00,
    "match": "NAME (JAHR)",
    "core_reason_short": "Kurzbegründung DNA",
    "core_reason_long": "Ausführliche Analyse des Profit-Hebels und der operativen Parallelen.",
    "source": "Genaue Quelle (URL/Dokument)",
    "check_timestamp": "2026-04-09T00:00:00Z",
    "score": 0,
    "zones": {"interessant": 0.00, "verfuehrerisch": 0.00}
  }
]

Zusätzlich: Schreibe unter das JSON-Objekt eine kurze Zusammenfassung (Prosa), warum genau diese Auswahl heute das stärkste Chancen-Risiko-Verhältnis bietet.