<h1 align="center" id="title">BaranGPT</h1>

<p align="center"><img src="https://avatars.steamstatic.com/2904e56a881d6ab0b678191313762051126535d0_medium.jpg" alt="project-image"></p>

<p id="description" align="center">Приватная GPT-Like нейросеть без лимитов и ограничений</p>

<p align="center"><img src="https://img.shields.io/badge/ARC--Test-63/100-pink" alt="shields"> <img src="https://img.shields.io/badge/HellaSwag--Test-91/100-pink" alt="shields"> <img src="https://img.shields.io/badge/MMLU--Test-47/100-pink" alt="shields"> <img src="https://img.shields.io/badge/TruthfulQA--Test-45/100-pink" alt="shields"></p>

<h2>🚀 Демо</h2>

[\[vitalikparkur.pro\]]([vitalikparkur.pro])

<h2>Пользовательский интерфейс:</h2>

<img src="https://sun4-18.userapi.com/impg/Klz1e1vgIamtpvi3gBQ9ZuSeD_LBDc5hTBqq3g/cNaGDDj0d7k.jpg?size=1280x723&amp;quality=96&amp;sign=ec3a4e83930579372a78b2f4102de818&amp;type=album" alt="project-screenshot" width="1100" height="580">

  
  
<h2>🧐 Уникальные возможности</h2>

*   Генерация текста без ограничений (нет лимита на количество символов)
*   Отсутствие сбора информации, ваши чаты не логируются
*   Самообучение - нейросеть сама ищет и обучается на информации в интернете
*   Multi-Language концепт - нейросеть поддерживает все языки мира

<h2>🛠️ API Endpoints</h2>

```
Request: /api/request?data=text&token=test-key | text - текст запроса | token - токен авторизации
200 Response: generatedText
400 Response: {"error": "Missing parameters"}
401 Response: {"status": "Unauthorized"}
500 Response: {"error": "Server not responding or busy"}
```
|
```
Request: /api/auth?token=test-key | token - токен авторизации
200 Response: {"status": "Authorized"}
400 Response: {"error": "Missing parameters"}
401 Response: {"status": "Unauthorized"}
```
|
```
Request: api/clearContext?token=test-key | token - токен авторизации
200 Response: {"status": "Context cleaned"}
400 Response: {"error": "Missing parameters"}
401 Response: {"status": "Unauthorized"}
500 Response: {"status": "Context cleaning failed"}
```
