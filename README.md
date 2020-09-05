# MEU PACOTE
exemplo de utilizacao

```
use Monolog\Logger;
use Monolog\Handler\StreamHandler;


$log = new Logger('name');
$log->pushHandler(new StreamHandler('app.log', Logger::WARNING));

$log->warning('Foo');
$log->error('Bar');

```