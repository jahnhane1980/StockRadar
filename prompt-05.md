# 🚀 ELITE-RADAR (V4.2) – AUTONOMER LIVE-DISCOVERY-MODUS

**MANDATORY START:** Nutze zwingend das Google Search Tool, um US-Aktien zwischen 5-20 USD zu identifizieren, die in den letzten 48 Stunden (Stand April 2026) Quartalszahlen, SEC-Filings oder signifikante News veröffentlicht haben. Ohne initiale Live-Suche ist dieser Auftrag nicht ausführbar.

---

## ⚙️ ENGINE-KONFIGURATION
"monitoring_config": {
  "active_radar": true,
  "discovery_mode": "autonomous_market_scan",
  "quality_threshold": 7,
  "last_full_scan": "2026-04-09",
  "execution_protocol": "step_by_step_search_first",
  "verification": "cross_reference_sec_filings",
  "timestamp_requirement": "strict_live_data"
}

---

## 🛠 DIE 6-STUFEN-MATRIX (FILTER-LOGIK)
Finde Aktien, die ALLE folgenden Kriterien erfüllen (verifiziere jedes Kriterium via Live-Daten):
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
3. Extrahiere für jeden Ticker die exakten Finanzdaten der letzten 3 Quartale.
4. Führe einen DNA-Abgleich mit einem historischen Giganten durch.

---

## 📤 OUTPUT-FORMAT (STRENGSTENS EINHALTEN)
Gib die Ergebnisse als ein Array von JSON-Objekten aus. Nutze den folgenden JSON-String-Aufbau (KEIN Code-Block für das JSON, nur Klartext-String im Markdown):

"watchlist_results": [
  {
    "ticker": "BEISPIEL",
    "price_usd": 0.00,
    "quarterly_history": [
      {"date": "2026-03-31", "revenue": "000M", "eps": "0.00"},
      {"date": "2025-12-31", "revenue": "000M", "eps": "0.00"},
      {"date": "2025-09-30", "revenue": "000M", "eps": "0.00"}
    ],
    "match": "NAME (JAHR)",
    "core_reason_short": "Kurzbegründung DNA",
    "core_reason_long": "Ausführliche Analyse des Profit-Hebels und der operativen Parallelen.",
    "source": "Direkter URL-Link zum Filing oder Report",
    "check_timestamp": "2026-04-09T20:45:00Z",
    "score": 0,
    "zones": {"interessant": 0.00, "verfuehrerisch": 0.00}
  }
]

Zusätzlich: Schreibe unter das JSON-Objekt eine kurze Zusammenfassung (Prosa), warum genau diese Auswahl HEUTE das stärkste Chancen-Risiko-Verhältnis bietet.