
**This is a practice project for learning purposes.** 

Fork of the repository [new_rep_test](https://github.com/CanUFeelMyHeart/new_rep_test) with an added `/multiply` route and tests for verifying API and math routes.

## Description

A Flask web application with the following routes:

  - `/` — returns `"Hello World!"` (GET)
  - `/add` — adds two numbers provided via query parameters `a` and `b` (GET)
  - `/multiply` — multiplies two numbers provided via query parameters `a` and `b` (GET)
  - `/api` — supports GET and POST:
  - GET — returns JSON: `{"status": "test"}`
  - POST — accepts JSON with fields:
  - `name` (str, required)
  - `age` (int, optional)  

Returns `{"status": "OK"}` for valid input, otherwise `{"status": "bad input"}` with HTTP 400
