# Projeto RUMENS - Campus do Sertão

**Nome do Técnico responsável:** Mariana Souza Nunes

## Resumo descritivo

O presente projeto tem como objetivo planejar e documentar uma infraestrutura de rede de computadores para atender às necessidades do **RUMENS - Grupo de Estudos em Pecuária de Ruminanes do Sertão Sergipano** (Campus do Sertão - UFS), proporcionando suporte tecnológico adequado às atividades de coleta, armazenamento, processamento, análise e compartilhamento de dados científicos.

A proposta visa garantir segurança da informação, conectividade estável com o STI (Campus São Cristóvão) e proteção dos equipamentos (energia e climatização), respeitando o limite orçamentário de R$ 50.000,00 e possibilitando a inclusão do cliente em um projeto de condomínio tecnológico da instituição.

O projeto inclui:

* Aplicação Web desenvolvida em **Python/Flask** para apresentação institucional.
* Containerização completa via **Docker** para implantação em nuvem (AWS).
* Documentação técnica da topologia (Lógica e Física).

## Documentos técnicos

A estrutura de arquivos deste repositório contém:

* `Dockerfile`: Arquivo de configuração para criação da imagem Docker na AWS.
* `app.py`: Código-fonte da aplicação web.
* `static/`: Contém a imagem topologia simulada (`.png`) e da planta baixa do condomínio de laboratórios (`.png`), além da topologia nos formatos dos arquivos (`.imn`) e (`.pdf`).
* `templates/`: Arquivo HTML da interface do site.

## Link do site de demonstração

O site foi configurado para execução em uma instância EC2 na AWS.

* **Endereço da Aplicação (EC2 na AWS):** `http://174.129.8.243/`
