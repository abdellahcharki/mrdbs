## Aufgabe 1 (Merkmale von Mehrrechner-DBS)

- ❌ Scaleout-Lösungen sind meist teurer als Scaleup-Lösungen  
  *Falsch: Scaleout ist meist günstiger und flexibler als große High-End-Multiprozessoren.*

- ✅ Verteilte DBS unterstellen die geographisch verteilte Nutzung einer einzigen logischen Datenbank  
  *Richtig: Ziel ist eine logische Datenbank über verteilte Standorte hinweg.*

- ❌ Data Warehouses realisieren einen föderierten Zugang zu heterogenen Datenquellen  
  *Falsch: Data Warehouses integrieren Daten physisch, Föderation bleibt virtuell.*

- ❌ Der Zugriff auf heterogene Datenbanken erfordert zunächst die Definition eines globalen Schemas  
  *Falsch: Zugriff ist auch ohne globales Schema möglich, z. B. bei P2P-Systemen.*

---

## Aufgabe 2 (Parallele Datenbanksysteme)

- ✅ um eine hochgradig parallele Bearbeitung von Benutzeranfragen auf großen Datenmengen zu ermöglichen  
  *Richtig: Nur so werden große Anfragen schnell beantwortet.*

- ✅ weil Inter-Query-Parallelität nur begrenzt eine Antwortzeitverbesserung zulässt  
  *Richtig: Inter-Query verbessert den Durchsatz, nicht die Antwortzeit einzelner Anfragen.*

- ✅ um dem Skew-Effekt in den Ausführungszeiten der Teilaufgaben entgegenzuwirken und somit einen besseren Speedup zu erreichen  
  *Richtig: Gleichmäßige Lastverteilung erhöht den Speedup.*

- ✅ weil sie automatisch vom DBS unabhängig von der Anwendungsprogrammierung realisierbar ist  
  *Richtig: Das DBMS kann Intra-Query-Parallelität von sich aus nutzen.*

---

## Aufgabe 3 (Pipeline- und Datenparallelität)

- ✅ Die Optimierung des Durchsatz-Scaleup erfordert möglichst die Nutzung von Daten- und Pipeline-Parallelität  
  *Richtig: Beide Parallelitätsformen steigern den Durchsatz.*

- ✅ Pipeline-Parallelität ermöglicht die überlappte Ausführung verschiedener Operatoren  
  *Richtig: Operatoren können gleichzeitig laufen.*

- ❌ Pipeline-Parallelität setzt ein breites Declustering der Daten voraus  
  *Falsch: Pipeline-Parallelität ist unabhängig vom Declustering der Daten.*

- ❌ Datenparallelität kann selten einen Speedup von mehr als 10 erreichen  
  *Falsch: Mit großen Datenmengen sind auch deutlich höhere Speedups möglich.*

---

## Aufgabe 4 (Speedup-Beispiel)

- ❌ n=100: 2,9  
  *Falsch: Mit 100 Rechnern sollte der Speedup viel höher sein (bis zu 50 bei idealer Parallelisierung).*

- ❌ n=10: 7,3  
  *Falsch: Rechnerisch ergibt sich für n=10 meist ca. 9,6 oder 2,5, aber nicht 7,3.*

- ✅ n=10: 2,5  
  *Richtig: Realistischer Wert, falls z. B. E/A nicht parallelisiert ist.*

- ✅ n=100: 50,0  
  *Richtig: Idealer Speedup bei perfekter Parallelisierung und vernachlässigbarer Kommunikation.*

---

## Aufgabe 5 (Amdahls Gesetz)

- ✅ Für n=100 ergibt sich ein Speedup von 17,5  
  *Richtig: Nach Formel S(100) = 42/2,4 = 17,5.*

- ❌ Für n>25 ist keine Speedup-Verbesserung mehr möglich  
  *Falsch: Speedup steigt weiter, aber der Zugewinn wird kleiner.*

- ✅ Der maximal mögliche Speedup gemäß Amdahls Gesetz ist auf 42/2=21 begrenzt  
  *Richtig: Das ist die theoretische obere Grenze für unendliche Prozessorzahl.*

- ✅ Für n=100 reduziert sich die Bearbeitungszeit auf 2,4 s  
  *Richtig: T(100) = 2 + 0,4 = 2,4 s.*

---

## Aufgabe 6 (Gesetz von Gustafson)

- ✅ Für n=100 beträgt die Bearbeitungszeit 42 s  
  *Richtig: Die Datenmenge wächst mit, die Zeit bleibt konstant.*

- ❌ Für n=10 ergibt sich ein Speedup von 42/6=7  
  *Falsch: Gustafson ergibt einen höheren Speedup.*

- ❌ Für n=10 ergibt sich ein Speedup von 402/42=9,6  
  *Falsch: Die Formel ergibt für n=10 einen anderen Wert; 9,6 ist hier nicht korrekt.*

- ❌ Für n=100 ergibt sich ein Speedup von 95,3  
  *Falsch: Speedup ist mit der Gustafson-Formel niedriger.*

---

## Aufgabe 7 (Shared-Disk vs. Shared-Nothing)

- ✅ IBM unterstüzt sowohl den SN- als auch den SD-Ansatz zur parallelen Datenbankverarbeitung  
  *Richtig: IBM bietet beide Architekturen.*

- ❌ In SD-Systemen können keine verteilte Deadlocks auftreten  
  *Falsch: Auch SD-Systeme können verteilte Deadlocks haben.*

- ❌ Eine nahe Kopplung ist zur Leistungssteigerung bei SD nicht einsetzbar  
  *Falsch: Gerade SD profitiert besonders von naher Kopplung/Speicher.*

- ❌ Die Erstellung einer globalen Log-Datei ist bei SD überflüssig  
  *Falsch: SD braucht meist eine globale Log-Datei für Recovery und Konsistenz.*
