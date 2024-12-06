# Animal Sounds API

This project is a simple Flask API that returns the sounds made by different animals.

## Endpoints

- **GET /como_hace/\<animal\>**: Returns the sound made by the specified animal.

## Example Usage

```bash
curl http://localhost:5000/api/como_hace/gato
     http://localhost:5000/api/como_hace/perro
     http://localhost:5000/api/como_hace/huron
     http://localhost:5000/api/como_hace/boa
`  

curl https://taller-2-api-rest-wine.vercel.app/api/como_hace/gato
     https://taller-2-api-rest-wine.vercel.app/api/como_hace/perro
     https://taller-2-api-rest-wine.vercel.app/api/como_hace/huron
     https://taller-2-api-rest-wine.vercel.app/api/como_hace/boa   