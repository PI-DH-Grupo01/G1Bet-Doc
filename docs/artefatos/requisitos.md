<h1 align="center">Requisitos</h1>

## Histórico de Versão

|    Data    | Versão |                Descrição                |                                                                                                                         Ator(es)                                                                                                                          |
| :--------: | :----: | :-------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| 14/10/2022 |  0.1   | Adiciona requisitos iniciais levantados | [Gabriel Marcolino](https://github.com/GabrielMR360), [Amanda Luiza](https://github.com/amandailg), [Carla Vitoria](https://github.com/Carla-Vitoria), [Júlio Batista](https://github.com/iamjuliobatista), [Alexandre](https://github.com/Alexandrecode) |
| 16/10/2022 |  0.2   |     Adiciona mais regras de negócio     |                                                                          [Gabriel Marcolino](https://github.com/GabrielMR360), [Carla Vitoria](https://github.com/Carla-Vitoria)                                                                          |

## Requisitos Funcionais

|  ID   | Descrição                                       | Prioridade |
| :---: | :---------------------------------------------- | :--------: |
| RF01  | Cadastrar usuário                               |            |
| RF02  | Atualizar informações do usuário                |            |
| RF03  | Excluir usuário                                 |            |
| RF04  | Realizar uma aposta em um time                  |            |
| RF05  | Listar os jogos que estão ocorrendo             |            |
| RF06  | Exibir histórico de apostas                     |            |
| RF07  | Exibir o histórico das últimas partidas do time |            |
| RF08  | Cancelar uma aposta                             |            |
| RF09  | Escolher o tipo de aposta                       |            |
| RF10  | Realizar login do usuário                       |            |

## Regras de negócio

### Regras de restrição

|  ID   | Descrição                                                                               |
| :---: | :-------------------------------------------------------------------------------------- |
| RN01  | O usuário pode realizar somente uma aposta.                                             |
| RN02  | Apostas só serão aceitas antes do jogo começar.                                         |
| RN03  | Só serão aceitas apostas de usuários cadastrados.                                       |
| RN04  | Dados de CPF, email e data de nascimento passarão por validação no momento do cadastro. |
| RN05  | Apostas só serão validadas após comprovação de pagamento.                               |
| RN06  | Odds serão estabelecidas de acordo com o mercado.                                       |

### Regras de cálculo

|  ID   | Descrição                                                                   |
| :---: | :-------------------------------------------------------------------------- |
| RN07  | Valor da aposta caso o usuário acerte = **ODDS x valor apostado**.          |
| RN08  | Valor de multiplas apostas = (multiplicação de cada ODDS) x valor da aposta |

### Regras de diretriz

|  ID   | Descrição                                                |
| :---: | :------------------------------------------------------- |
| RN09  | Somente usuários com mais de 18 anos podem se cadastrar. |

### Regras de causa e efeito

|  ID   | Descrição                                                                        |
| :---: | :------------------------------------------------------------------------------- |
| RN10  | Quando o usuário for apostar qualquer quantia, então ele deve confirmar a aposta |

### Regras de estimulo e resposta 

|  ID   | Descrição                                                                |
| :---: | :----------------------------------------------------------------------- |
| RN11  | Valores ganhos nas apostas poderão levar até 24h para serem depositadas. |
