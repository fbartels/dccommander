# dccommander

`dccommander` is a convienience wrapper ground [commander](https://github.com/SimonBaeumer/commander) that aims to bring the simplicity of `commander` to docker-compose managed container. The script is based on [dcgoss](https://github.com/aelsabbahy/goss/tree/master/extras/dcgoss).

## Usage

### Run

### Edit

### Debugging execution

Specifying the `DEBUG` in the environment not only runs `dccommander` with `set +x`, but also prevents cleaning out the tempdir with the logfile of the container startup.

```bash
DEBUG=true  dccommander edit kopano_konnect
```

### Environment vars and defaults

COMMANDER_OPTS="--concurrent 1"

COMMANDER_FILES_PATH=konnect
