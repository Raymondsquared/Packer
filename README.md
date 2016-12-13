# Packer

### Packer Validate

```sh
$ packer validate example.json
```

The packer validate Packer command is used to validate the syntax and configuration of a template. The command will return a zero exit status on success, and a non-zero exit status on failure. Additionally, if a template doesn't validate, any error messages will be outputted.

### Packer Build

```sh
$ packer build example.json
```

The packer build Packer command takes a template and runs all the builds within it in order to generate a set of artifacts. The various builds specified within a template are executed in parallel, unless otherwise specified. And the artifacts that are created will be outputted at the end of the build.
