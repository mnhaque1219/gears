### Tophat geometry

```sh
$ gears tophat.mac
```

You need to install [dawn][] and [HepRApp][] to view the results.

[dawn]:https://geant4.kek.jp/~tanaka/DAWN/About_DAWN.html
[HepRApp]: https://www.slac.stanford.edu/~perl/HepRApp/

### Hemispherical HPGe detector

Run the following command to produce four png files showing how to create a hemispherical Ge detector with holders using boolean operation step by step:

~~~sh
$ ./cut.sh
~~~

One has to have the shell command *convert* available to generate the png files. Detailed settings and usage of DAWN are demonstrated in cut.mac and cut.sh
