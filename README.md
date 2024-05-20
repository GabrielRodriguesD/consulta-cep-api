# consulta-cep-api
Projeto de consumo de API de CEP do viaCEP

## APIs

As APis pussuem alguns elementos que servem á sua utilização:

- **Ponto de entrada**: é o endereço do serviço hospedado e que pode ser acessado atraves de um navegador ou uma ferrramenta de cpnsumo APIs. Exemplo: <https://dadosabertos.camara.leg.br>

- **Recursos**: são os serviços de dados disponíveis para consumo. Exemplo: <https://dadosabertos.camara.leg.br/api/v2/deputados>

- **Parâmetros**: são informações ou filtros que servem para enviar dados da consulta ou ainda para serem processados pela API. Os parâmetros podem ser passados para a API através da URL ou no corpo (body) da requisição. Exemplo: <https://dadosabertos.camara.leg.br/api/v2/deputados?nome=tiririca>

- **Metodos**: são as formas de consumo de uma API, que podem ser:
   - _POST_: inserção de dados (**C**REATE)
   - _GET_: obtenção de dados (**R**EAD)
   - _PUT e PATCH_: atualização (**U**PDATE)
   - _DELETE_: remoção de dados (**D**ELETE)