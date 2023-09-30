# Custom Entur
Entur custom integration

sensor:
  - platform: entur_custom
    name: Kollektiv
    expand_platforms: false
    show_on_map: true
    number_of_departures: 3
    stop_ids:
      - stop_id: "NSR:StopPlace:59648" # Kjelsås Stasjon
        line_whitelist:
          - "GJB:Line:L3" #Gjøvikbanen R31
