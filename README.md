# osm-tileserver

+ modified get-shapefiles.py for openstreetmap-carto-4.20.0 (updated download links)
  - place in ~/openstreetmap-carto-4.20.0/scripts/
  - make it executable
    - chmod 775 get-shapefiles.py
+ preconfigured renderd.conf for renderd
  - place in /etc/
  - In the [renderd] section, change to the number of threads according to the number of CPU cores on your server.
    - num_threads=4
