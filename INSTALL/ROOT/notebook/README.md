[Dockerfile](Dockerfile) in this folder is used to create the docker image, [physino/root:notebook](https://hub.docker.com/r/physino/root/tags), in the following way:

```sh
cd /path/to/gears/INSTALL/ROOT/notebook
docker build -t physino/root:notebook .
docker push physino/root:notebook
```

It can be used in the following way:

```sh
cd /path/to/gears
docker compose up
[+] Running 8/8
...
gears-analysis-1  |     To access the notebook, open this file in a browser:
gears-analysis-1  |         file:///root/.local/share/jupyter/runtime/nbserver-11-open.html
gears-analysis-1  |     Or copy and paste one of these URLs:
gears-analysis-1  |         http://3aefd9eb4f5f:8888/?token=19ca614154325439e355baf69574a2683714c988c033d5c8
gears-analysis-1  |      or http://127.0.0.1:8888/?token=19ca614154325439e355baf69574a2683714c988c033d5c8
```

Open the last link in your browser in the host computer and you can use the [jupyter][] notebook to analyze data generated by your [Geant4][] simulation.

[jupyter]: https://jupyter.org
