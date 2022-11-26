# Sprawdzenie wydajnści aplikacji Web na Wildfly

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
 
 
 #### Zrzuty ekranu
 
![obraz](https://user-images.githubusercontent.com/75216446/204086746-4a798a31-cb86-4195-a7f8-5168afac06d0.png)

![obraz](https://user-images.githubusercontent.com/75216446/204086763-7c5042c9-0e95-416d-80d9-b086b619f75c.png)

![obraz](https://user-images.githubusercontent.com/75216446/204086820-117c3c75-4213-48a2-9991-034d10d52238.png)

![obraz](https://user-images.githubusercontent.com/75216446/204086846-47412c74-adc5-4010-a371-3c0149a9c5e5.png)

![obraz](https://user-images.githubusercontent.com/75216446/204086885-ec9f103d-6123-464f-8e67-ed554fcbcad2.png)



