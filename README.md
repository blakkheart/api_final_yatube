# api_final

api_final is a Python DRF API for yatube project (front-end is not included).

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install api_final's dependencies.

```bash
(venv) pip install -r requirements.txt
```

## Usage

```python

# returns all posts
'GET' request to /api/v1/posts/
# output example JSON:
{
  "count": 123,
  "next": "http://api.example.org/accounts/?offset=400&limit=100",
  "previous": "http://api.example.org/accounts/?offset=200&limit=100",
  "results": [
    {
      "id": 0,
      "author": "string",
      "text": "string",
      "pub_date": "2021-10-14T20:41:29.648Z",
      "image": "string",
      "group": 0
    }
  ]
}

# you can see all allowed requests and examples in <static/redoc.yaml>
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[YaPracticum](https://practicum.yandex.ru)