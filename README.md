# IDHM brasileiro em 2010
Código Python para raspar dados de IDHM do Brasil diretamente do site do Programa das Nações Unidas para o Desenvolvimento (PNUD).

O IDHM é o índice de desenvolvimento humano por municípios. O IDHM varia de 0 a 1 e quanto mais próximo do 1, mais desenvolvido é o município.

O código criado com as bibliotecas CSV, Pandas e QuickDA lê o HTML do site em questão e retira as seguintes informações sobre o IDHM dos municípios brasileiros:

|Nome da variável | Descrição |
| --- | --- |
| ranking | Posição do Município no IDHM brasileiro |
| municipio | Cidade |
| estado | Estado |
| idhm_2010 | IDHM do município no ano de 2010 |
| idhm_renda | IDHM de renda do município em 2010 |
| idhm_longev | IDHM de longevidade do município em 2010 |
| idhm_edu | IDHM educacional do município em 2010 |

## Histórico de lançamentos
0.0.1
Trabalho em andamento

## Meta
Renan Cavalcante – @renan_cav – renan376@gmail.com

Distribuído sob a licença MIT. Veja LICENSE para mais informações.

https://github.com/renan-cav

## Contributing
* Faça o fork do projeto (https://github.com/renan-cav/IDHM-Brasil-2010)
* Crie uma branch para sua modificação
* Faça o commit
* Push
* Crie um novo Pull Request
