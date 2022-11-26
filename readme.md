# Sprawdzenie wydajnści aplikacji Web Wildfly

## FMEAv2_JDBC - sprawdzenie wydajności bazy danych

### Poszczególne etapy

- Count tabeli project
- Asercja: 
  count
  \d{3}

### Obciążenie

- Liczba użytkowników: 20
- Czas odpytywania: 10 sek.
- liczba powtórzeń: 2



# FMEAv2 - sprawdzenie aplikacji Web

### Poszczególne etapy

- Logowanie
- Sprawdzenie dostępności Projetku
- Sprawdzenie dostępności Dokumentu

### Obciążenie

- Liczba użytkowników: 20
- Czas odpytywania: 10 sek.
- liczba powtórzeń: 2



## Monitoring

- Prometheus
- Node_exporter
- Postgres_exporter
- Grafana

#### Plugins
 
 https://grafana.com/grafana/dashboards/1860-node-exporter-full/
 
 https://grafana.com/grafana/dashboards/9628-postgresql-database/
 
 
 ## Dodatkowe narzędzia
 
 - Jenkins (uruchomienie testu automatycznie)
 - GitLab (kontrola wersji)
 - DBeaver (obsługa baz danych)
 - VS Code (edytor kodu)

