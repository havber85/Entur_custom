# Custome Components HA
Personalized customizations of HA integrations

sensor:
  - platform: entur_custome
    name: Kollektiv
    expand_platforms: false
    show_on_map: true
    number_of_departures: 3
    stop_ids:
      - stop_id: "NSR:StopPlace:59648" # Kjelsås Stasjon
        line_whitelist:
          - "GJB:Line:L3" #Gjøvikbanen R31
