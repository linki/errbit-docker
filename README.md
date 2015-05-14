# errbit-docker

build the errbit image

    $ fig build

bootstrap errbit

    $ fig run app bundle exec rake errbit:bootstrap

run mongo, errbit, and nginx processes

    $ fig up -d

browse to your docker host on port 80
