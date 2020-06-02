# API de consulta e pesquisa de CEP do Brasil
Base de dados atualizado mensalmente com geocoordenadas e código do IBGE

## Exemplo de uso

```
curl https://cep.awesomeapi.com.br/json/05424020
```
```json
{
  "cep": "05424020",
  "address_type": "Rua",
  "address_name": "Professor Carlos Reis",
  "address": "Rua Professor Carlos Reis",
  "neighborhood": "Pinheiros",
  "city": "Sao Paulo",
  "state": "SP",
  "lat": "-23.5703026",
  "lng": "-46.6967364",
  "ddd": "11",
  "city_ibge": "3550308"
}
```

## Formato de saída
```
curl https://cep.awesomeapi.com.br/json/05424020
curl https://cep.awesomeapi.com.br/xml/05424020
curl https://cep.awesomeapi.com.br/05424020?format=xml
```
```xml
<xml>
    <cep>05424020</cep>
    <address_type>Rua</address_type>
    <address_name>Professor Carlos Reis</address_name>
    <address>Rua Professor Carlos Reis</address>
    <neighborhood>Pinheiros</neighborhood>
    <city>Sao Paulo</city>
    <state>SP</state>
    <lat>-23.5703026</lat>
    <lng>-46.6967364</lng>
    <ddd>11</ddd>
    <city_ibge>3550308</city_ibge>
</xml>

```
> **Formatos suportados**
> - JSON
> - XML
