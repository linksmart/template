# Foobar
<!-- Short description of the project. -->

Foobar is not a real software. The name is used here as placeholder for a described software. This readme is meant for describing an application but can be adapted to describe a software library by changing `Deployment` section to `Usage`. 

## Getting Started
<!-- Instruction to make the project up and running. -->

The project documentation is available on the [Wiki](https://github.com/cpswarm/template/wiki).

### Deployment
<!-- Deployment/Installation instructions. If this is software library, change this section to "Usage" and give usage examples -->

```bash
docker run -p 8080:80 foobar
```

### Development
<!-- Developer instructions. -->

#### Prerequisite
This projects depends on ZeroMQ. Installation instructions are available [here](http://zeromq.org/intro:get-the-software)

On Debian:
```bash
apt install libzmq3-dev
```

#### Build

```bash
g++ -o app app.cpp
```

## Contributing
Contributions are welcome. 

Please fork, make your changes, and submit a pull request. For major changes, please open an issue first and discuss it with the other authors.


> # Notes
>
> * The above templace is adapted from [[1](https://www.makeareadme.com), [2](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2), [3](https://github.com/dbader/readme-template)].
> * Versioning: Use [SemVer](http://semver.org/) and tag the repository with full version string. E.g. `v1.0.0`
> * License: Provide a [LICENSE](LICENSE) file at the root level. You can use Github to [add a license](https://help.github.com/en/articles/adding-a-license-to-a-repository). Don't forget to replace the [placeholders in the license file](https://github.com/cpswarm/template/blob/master/LICENSE#L189).  
>
> *Remove this section from the actual readme.*
