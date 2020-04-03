Add this to your shell configuration file:
  export PATH="$HOME/.symfony/bin:$PATH"
Start a new shell, and then run 'symfony'

Or install it globally on your system:
  mv /home/ben/.symfony/bin/symfony /usr/local/bin/symfony
and then run 'symfony'

Start Application:
in /docker: docker-compose up
in /src: symfony server:start

add: 
composer require symfony/orm-pack
composer require --dev symfony/maker-bundle
