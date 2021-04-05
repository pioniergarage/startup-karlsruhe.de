![Ein Screenshot der Seite für Startups in Karlsruhe](https://github.com/pioniergarage/startup-karlsruhe.de/raw/master/.github/page.jpg)

# Startup-Karlsruhe - Die Startup-Szene in Karlsruhe

Startup-Karlsruhe.de bietet einen [Überblick über die Karlsruher Startup-Szene](http://startup-karlsruhe.de) und die wichtigsten Anlaufstellen, um interessierten Startups, Entrepreneuren und Gründern einen erleichterten Einstieg zu ermöglichen. Das Projekt wurde ursprünglich von Andreas Dittes ins Leben gerufen und an die [PionierGarage](http://pioniergarage.de) übertragen.

## Als Startup erscheinen

Du hast ein Startup und willst auch in der Liste genannt werden? Dann erstelle ein [Issue](https://github.com/pioniergarage/startup-karlsruhe.de/issues) und gib folgende Details an:

- der Name deines Startups
- die Website
- eine Beschreibung deines Startups in einem Satz

Wir kümmern uns um den Rest.

## Deployment

- `docker-compose run jekyll jekyll build`
- Danach den Inhalt des neu erzeugten Ordners `_site` per FTP auf den Server laden.
- `docker-compose down` to clean up

## Development server

- `docker-compose up`
- Danach kann die Website unter [localhost:4000](localhost:4000) aufgerufen werden
- `docker-compose down` to clean up

## Update packages

- `docker-compose up`
- `docker exec -it <container-id> bash`
- `bundle update`

## Weitere Informationen

- Generator: [Jekyll](https://jekyllrb.com)
- Template: Aesthetic by [gettemplates.co](https://gettemplates.co)
- Author: [@lorey](https://github.com/lorey) and [@dome4](https://github.com/dome4)
- [Install Docker](https://docs.docker.com/engine/install/ubuntu/)
- [Install Docker Compose](https://docs.docker.com/compose/install/)
