<h1 align="center">NoiseForge Cyber System 🛡️</h1>

<div align="center">
<i>Zaawansowana platforma do generowania kontrolowanego szumu informacyjnego i symulacji cyberzagrożeń.</i>
</div>

🎯 O projekcie

NoiseForge to zautomatyzowane oprogramowanie zaprojektowane w celu symulowania zmasowanych zdarzeń bezpieczeństwa. Platforma pozwala na rygorystyczne testowanie odporności i wydajności systemów detekcji zagrożeń (klasy SIEM/SOC) w środowiskach docelowych, poprzez wstrzykiwanie kontrolowanego, realistycznego obciążenia sieciowego.

🏗️ Architektura Systemu

Platforma opiera się na 5-stopniowej, modułowej architekturze, która gwarantuje pełną kontrolę nad każdą fazą operacji badawczej:

• 📥 Moduł Zbierania Danych – precyzyjna agregacja i normalizacja logów systemowych, adresów IP oraz wejściowych zdarzeń.

• 🔍 Moduł Analizy i Rekonesansu – analiza zebranych informacji (OSINT), wykrywanie anomalii i klasyfikacja podatności.

• 🧠 Moduł Decyzyjny – centralny węzeł autoryzacyjny podejmujący ostateczną decyzję o uruchomieniu i skali kampanii.

• ⚡ Moduł Realizacji Działań – fizyczne generowanie kontrolowanego szumu (m.in. symulowane ataki obciążeniowe DDoS w warstwie L7).

• 📊 Moduł Raportowania i Monitoringu – ciągły nadzór operacyjny, logowanie audytowe i generowanie końcowych metryk skuteczności.

⚙️ Stos Technologiczny

System został zbudowany w oparciu o wysoce wydajne i skalowalne technologie rozproszone:

• Chmura i Orkiestracja: AWS / Azure / GCP, Kubernetes (K8s), Docker

• Sieć i Dystrybucja: Nginx (Load Balancing)

• Silniki i Narzędzia: Python, Apache Spark, Scapy, Custom Scripts

• Warstwa Danych: PostgreSQL, Elasticsearch (Data Lake)

🔒 Bezpieczeństwo i Izolacja

Ze względu na wysoce inwazyjny charakter platformy, zaimplementowano krytyczne mechanizmy zabezpieczające przed niekontrolowanym rozprzestrzenieniem ruchu:

• 🛑 Kill Switch – wielopoziomowy, awaryjny mechanizm natychmiastowego przerwania operacji przy zmianie statusu celu.

• 🛡️ Zgodność – pełna implementacja wymagań standardu OWASP ASVS (Poziom 3).

• 🔐 Izolacja Sieciowa – tunelowanie ruchu (TLS/VPN) wymuszające działanie wyłącznie w granicach zatwierdzonych Rules of Engagement.
