# hello-dagger

This is an example application for use with the Dagger Quickstart. It uses the Vue 3 + Vite template, with minor modifications.

## Play with Dagger
- Install [Dagger](https://dagger.io/docs/install) and related tools
- Type `dagger` in the root of the project
  - `.help` will show you the available commands
    - `build` will build the app
      - `build | as-service | up --ports=8080:80` will run the app as a service, you can access it at `http://localhost:8080`
    - `build-env` will build the app with the env
      - `build-env | terminal --cmd=bash` can interact with the container
    - `test` will run the tests
    - `lint` will run the linter
    - `publish` will publish the image to [ttl.sh container registry](https://ttl.sh/) 

## References
- [Build a CI Pipeline](https://docs.dagger.io/quickstart/ci)