Dumping ground for container and conda environment specification for easy reproducibility. For example to build one specific environment one can run

```console
apptainer build --build-arg ENVFILE="specific/bilby-pipe-live-point-fix.yml" containers/bilby-pipe-live-point-fix.yml ./apptainer.def
```
