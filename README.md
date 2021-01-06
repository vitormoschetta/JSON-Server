# JSON-Server

## Install 

```
npm init -y
```

Alterar **package.json**:
```
  "scripts": {
    "start": "json-server --watch db.json --port 2001"
  }
```

Adicionar json-server:
```
npm install json-server
```


## GET
GetAll
```
http://localhost:2001/products
```


## GET
BetById
```
http://localhost:2001/products/1
```


## POST
Create
```
http://localhost:2001/products
```

Body JSON:
```
{
    "id": "7",
    "name": "Product",
    "price": 8.99
}
```


## PUT
Update

```
http://localhost:2001/products/7
```

Body JSON:
```
{
    "id": "7",
    "name": "Teste",
    "price": 2.10
}
```


## DELETE
GetAll
```
http://localhost:2001/products/7
```

