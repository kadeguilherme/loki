# Loki
Nesse projeto vamos intregar a aplicação gerador-log com o Prometheus Loki.
O projeto tem finalidade de simula uma aplicaçao que gere logs.
##  Gerador de Log
  - É usado no projeto o Grafana Loki
  - Gerador de log criar uma pasta /logs, aqui é onde será salvo os logs
## 💻 Pré-requisitos
  - No windows DOCKER Desktop instalado
  - Linux ja tem Docker

## 🚀 Execução do projeto

```bash
# Clone do repositório
$ git clone https://github.com/kadeguilherme/loki.git

# Executar o comando dentro da pasta /Loki 
$ docker-compose up

# Portas 
  localhost:3000 -> web-site Gerador de Log
  localhost:5000 -> Grafana
    usuario : admin
      senha : admin
      
  localhost:9080 -> Promtail

```
<table>
  <td>
  <img src="https://github.com/kadeguilherme/loki/blob/main/grafana.png" alt="Card-01">
  </td>
</table>

## Arquitetura do Projeto
<img src="https://github.com/kadeguilherme/loki/blob/main/Arquitetura%20gerador%20de%20log%20-%20Loki.png" alt="Card-01">


## Feito com ❤
  <table >
    <td align= 'center'>
      <a hrfe= '#'>
         <img src="https://github.com/kadeguilherme/api-pokemon/blob/master/public/emoji.svg" width="100px;" alt="Avatar"/> <br>
        <sub>
          <b>Guilherme Aguiar </b>
        </sub>
  </table>
