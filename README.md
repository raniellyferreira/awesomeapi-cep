# API de consulta e pesquisa de CEP do Brasil
Base de dados do IBGE atualizado mensalmente

## Exemplo de uso

```
curl https://cep.awesomeapi.com.br/05424020
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
  "ddd": "11"
}
```

## Pesquisa de CEP (Em desenvolvimento)
```
https://cep.awesomeapi.com.br/search/{criterio de busca}
```
```
curl https://cep.awesomeapi.com.br/search/praca+da+se
```
```json
[
  {
  }
]
```

## Formato de saída
```
curl https://cep.awesomeapi.com.br/jsonp/05424020?callback=jsonp_callback
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
</xml>

```
> **Formatos suportados**
> - JSON
> - JSONP
> - XML
> - HTML
> - CSV
> - SERIALIZED
