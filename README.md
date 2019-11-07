# json-server
мои файлы с json для ajax запросов

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
