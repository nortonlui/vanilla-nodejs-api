# Vanilla Node Rest API

API montada somente com JS e Node. Utilizando MVC e arquivo JSON como fonte de dados.

---

URL: `https://sleepy-wildwood-78096.herokuapp.com/api/products`

VERBO: GET

Traz todos os produtos cadastrados.

---

URL: `https://sleepy-wildwood-78096.herokuapp.com/api/products/:id`

VERBO: GET

Traz somente um produto

---

URL: `https://sleepy-wildwood-78096.herokuapp.com/api/products`

VERBO: POST

Cria um produto. Ex.:

```JSON
  {
    "title": "Videogame",
    "description": "Nintendo 5",
    "price": 5000
  }

```

---

URL: `https://sleepy-wildwood-78096.herokuapp.com/api/products/:id`

VERBO: PUT

Atualiza um produto

```JSON
  {
    "title": "Videogame",
    "description": "Nintendo 5 XMAX",

  }

```

---

URL: `https://sleepy-wildwood-78096.herokuapp.com/api/products/:id`

VERBO: DELETE

Remove um produto

---
