# Il monitoraggio dei siti web in chiave devops

Questo è il sorgente del webinar sul monitoraggio dei siti web in chiave devops.

Costruiremo uno stack di monitoraggio basato su Prometheus, blackbox_exporter e Grafana.

I requisiti di questo webinar sono i seguenti:
- Accesso a DockerHub
- docker
- docker-compose


## Prometheus

**Prometheus** è un'applicazione utilizzata per il monitoraggio e la segnalazione degli eventi. Registra le metriche in tempo reale in un database di serie temporali, costruito utilizzando un modello di pull HTTP, con query flessibili e avvisi in tempo reale.

## BlackBox Exporter

Poller per l'estrapolazione dei dati da un sito esterno.

## Grafana

**Grafana** è una applicazione web che consente la visualizzazione e il formato dei dati metrici. Ti consente di creare dashboard e grafici da più fonti, inclusi database di serie temporali.

# Come avviare il servizio

Eseguire `docker-compose up -d` per avviare lo stack.

Accedere al fronted web di Prometheus tramite browser a http://localhost:9090

Accedere al fronted web di Blackbox_exporter tramite browser a http://localhost:9115

Accedere al fronted web di Grafana tramite browser a http://localhost:3000 (username: admin - password: secret)


Per ulteriori informazioni non esitate a contattarci a info@thei.it 
