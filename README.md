# Динамический WEB
## Требуется:
Развернуть vagrant стэнд с проброшенными на локалхост портами в nginx, каждый порт на свой сайт.
# Вполнение, демонстрация.
Разворачиваем стенд: \
`vagrant up` \
`vagrant ssh`

Запускаем наши сервисы: \
`cd /vagrant/provision/app-release/ && docker-compose up -d`

