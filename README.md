Консольная утилита для вывода отчетности отработанного времени и заработанных средств с трекера https://toggl.com

Для корректной работы необходимо в корневую директорию поместить файл config.xml вида:


  <p>
&ltConfig&gt <br/>
  &ltTogglToken&gtВаш токен (можно посмотреть в профиле пользователя)&lt/TogglToken&gt <br/>
&lt/Config&gt <br/>
  </p>

Компиляция: go build te.go

Вызов справки: ./te --help для Linux/Mac или te.exe --help для Windows
