# json-server
мои файлы с json для ajax запросов
Стучаться нужно в репозиторий json-server, после чего указывать либо db(получим весь файл), либо ключ обьекта, например roulette-meal

# use example
const runTestFunc = function(interval) {
  $.ajax({
    url: `https://my-json-server.typicode.com/oldmal/json-server/roulette-meal`,
    type: 'GET'
  })
    .done(function(res) {
      console.log(res);
    };
};
