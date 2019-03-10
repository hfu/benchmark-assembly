# benchmark-assembly

```console
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 44.0G  100 44.0G    0     0  2512k      0  5:06:27  5:06:27 --:--:-- 3803k
```

```console
{
  z: 6
  minx: 22
  miny: 24
  maxx: 41
  maxy: 39
  exportConfigPath: ./osmium-export-config.json
  modifyPath: ./modify.js
  pbfDirPath: pbf
  mbtilesDirPath: mbtiles
  concurrent: 2
  planetPath: ../welt/planet-190304.osm.pbf
  skipMiniPlanet: false
  skipExistingPbf: false
  skipExistingMbtiles: false
}
```

```console
[ 0:00] Started osmium extract
[ 0:00]   osmium version 1.7.1
[ 0:00]   libosmium version 2.13.1
[ 0:00] Command line options and default settings:
[ 0:00]   input options:
[ 0:00]     file name: ../welt/planet-190304.osm.pbf
[ 0:00]     file format:
[ 0:00]   output options:
[ 0:00]     file name: /tmp/34103537180a7f15fd79bd597d2ec3c3.osm.pbf
[ 0:00]     file format: pbf,pbf_compression=false,add_metadata=false
[ 0:00]     generator: osmium/1.7.1
[ 0:00]     overwrite: yes
[ 0:00]     fsync: no
[ 0:00]   strategy options:
[ 0:00]     strategy: smart
[ 0:00]     with history: no
[ 0:00]   other options:
[ 0:00]     config file:
[ 0:00]     output directory:
[ 0:00]
[ 0:00] Extracts:
[ 0:00] [01] Output:      /tmp/34103537180a7f15fd79bd597d2ec3c3.osm.pbf
[ 0:00]      Format:      PBF
[ 0:00]      Description:
[ 0:00]      Envelope:    (-56.25,-40.9799,56.25,40.9799)
[ 0:00]      Type:        bbox
[ 0:00]      Geometry:    BOX(-56.25 -40.9798981,56.25 40.9798981)
[ 0:00]
[ 0:00] Additional strategy options:
[ 0:00]   types:
[ 0:00]       multipolygon
[ 0:00]
[ 0:00] Running 'smart' strategy in three passes...
[ 0:00] First pass...
[121:50] Second pass...
[176:29] Third pass...
[304:24] Peak memory used: 0 MBytes
[304:24] Done.

```

/tmp/341035...osm.pbf was 8.0GB.

see also [produce-320.stdout](produce-320.stdout).

