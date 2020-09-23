# Инструменты для разарботки в докере


## Composer
### for linux
`docker run --rm -it --volume $PWD:/app -w /app composer <command>`
###for Windows
`docker run --rm --interactive --tty --volume %CD%:/app -w /app composer`

## Phpunit
### for linux
`docker run --rm --volume $PWD:/app -w /app php:7.4-cli ./vendor/bin/phpunit tests`

### for windows
`docker run --rm --volume %CD%:/app -w /app php:7.4-cli ./vendor/bin/phpunit tests`
