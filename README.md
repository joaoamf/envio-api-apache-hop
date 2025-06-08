# envio-api-apache-hop
Pipeline Apache Hop para enviar dados via API REST

# Envio de Dados via API com Apache Hop

Este projeto demonstra como utilizar o Apache Hop para automatizar o envio de dados a uma API REST.

## 🛠️ Ferramentas
- Apache Hop
- Banco SQLite
- Banco Oracle
- REST API

## 🔁 Pipeline
- **Consulta SQL** → **Transformação de dados** → **Envio via HTTP POST** → **Resposta API com resultado**-

  <h3>📸 Visual do Pipeline</h3>

<p align="center">
  <img src="docs/pipeline-hop.png" width="1000" alt="Pipeline no Apache Hop" />
</p>
<p align="center">
  <img src="docs/dados-sqlite.png" width="1000" alt="Dados no Table Input" />
</p>
<p align="center">
  <img src="docs/db_sqlite.png" width="1000" alt="Dados no SQLite" />
</p>
<p align="center">
  <img src="docs/variavel-content-type.png" width="1000" alt="Incluir Content-Type" />
</p>
<p align="center">
  <img src="docs/transformar-dados-string.png" width="1000" alt="Transformar dados em String" />
</p>
<p align="center">
  <img src="docs/http-post-api.png" width="1000" alt="HTTP POST" />
</p>
<p align="center">
  <img src="docs/http-post-api-header.png" width="1000" alt="HTTP POST HEADER" />
</p>
<p align="center">
  <img src="docs/resposta-api.png" width="1000" alt="DUMMY-Resposta API" />
</p>
<p align="center">
  <img src="docs/dados-inserido.png" width="1000" alt="DUMMY-Resposta API" />
</p>
<p align="center">
  <img src="docs/payload.png" width="1000" alt="Dados Enviado do SQLite" />
</p>
<p align="center">
  <img src="docs/db_oracle.png" width="1000" alt="Dados Inseridos no Oracle" />
</p>

📽️ Demonstração em vídeo:
[Assista](docs/demonstracao.mkv)

## 🔗 Requisitos
- Apache Hop instalado
- Conexão com Oracle e SQLite configurada
- Endpoint da API
