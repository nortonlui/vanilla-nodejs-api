# Vanilla Node Rest API

API montada somente com JS e Node. Utilizando MVC e arquivo JSON como fonte de dados.

---

URL: `https:\\xxxx\api\products`

VERBO: GET

Traz todos os produtos cadastrados.

---

URL: `https:\\xxxx\api\products\:id`

VERBO: GET

Traz somente um produto

---

URL: `https:\\xxxx\api\products`

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

URL: `https:\\xxxx\api\products\:id`

VERBO: PUT

Atualiza um produto

```JSON
  {
    "title": "Videogame",
    "description": "Nintendo 5 XMAX",

  }

```

---

URL: `https:\\xxxx\api\products\:id`

VERBO: DELETE

Remove um produto

---
