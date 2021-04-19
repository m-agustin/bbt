# Milk tea mock API

Built a mock version of an API and deloyed it onto a cloud platform via. Heroku.
No routing/controllers.
Incorporated github package by [JSON Server](https://github.com/typicode/json-server) onto project to create a mock REST API with zero coding.

Interactive mock API, able to make GET, POST, PUT, DELETE etc requests.

# To GET an individual ID, write:

    fetch('https://bbt-m.herokuapp.com/MilkTea/0')
      .then(response => response.json())
      .then(data => console.log(data));
