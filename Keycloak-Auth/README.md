# Keycloak

To understand the contents of your Keycloak installation, see the [directory structure guide](https://www.keycloak.org/server/directory-structure).

To get help configuring Keycloak via the CLI, run:

on Linux/Unix:

    $ bin/kc.sh --http-port=8000

on Windows:

    $ bin\kc.bat --http-port=8000

To try Keycloak out in development mode, run:

on Linux/Unix:

    $ bin/kc.sh start-dev --http-port=8000

on Windows:

    $ bin/kc.sh start-dev --http-port=8000

After the server boots, open http://localhost:8000 in your web browser. The welcome page will indicate that the server is running.

To get started, check out the [configuration guides](https://www.keycloak.org/guides#server).
