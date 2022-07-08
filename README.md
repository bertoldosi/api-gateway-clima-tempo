## 📖 Sobre:

Um api gateway desenvolvido em express-gateway para mediar as requisições do client clima-tempo. Com esse gateway é possível obter a temperatura semanal de todas as cidades Brasileira. Também é possível obter a latitude e longetude das cidades.

---

## Funcionalidades


## Previsão do tempo para os próximo 8 (oito) dias

GET /onecall

```bash

curl https://api-gateway-clima-tempo.herokuapp.com/onecall\?lat\=-10.0007936\&lon\=-67.7937152\&appid\=api-key

```

Detalhes dos valores:
| Parâmetros | Descrição |
|---|---|
| `lat` | Latitude da cidade |
| `lon` | Longitude da cidade |
| `appid` | Key que pode ser gerado gratuitamene em https://home.openweathermap.org/api_keys |


## Respostas
Doc completa com todas as repostas https://openweathermap.org/api/one-call-3 

---

Desenvolvido por Matheus Bertoldo !
