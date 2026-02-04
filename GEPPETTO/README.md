# Projeto de Infraestrutura de Redes - Campus Sertão

## 🆔 Identificação do Projeto
**Técnico Responsável:** Lucas Conceição Celestino

## 📝 Resumo Descritivo
Este projeto consiste na implementação e simulação de uma infraestrutura de rede de alta performance voltada para um Grupo de Pesquisa Acadêmica. O objetivo é estabelecer uma topologia segura e escalável utilizando o emulador CORE, configurada com roteamento dinâmico (**OSPFv2 e OSPFv3**) e endereçamento **Dual Stack (IPv4 e IPv6)**.

A arquitetura proposta visa garantir a soberania dos dados de pesquisa, isolamento de tráfego pesado e integração eficiente ao modelo de "Condomínio de Laboratórios", assegurando alta disponibilidade e velocidade para transferência de datasets científicos.

## 📂 Documentos Técnicos
Os arquivos essenciais para a execução e avaliação do projeto encontram-se na raiz deste repositório:

* **`Dockerfile`**: Arquivo de configuração para a containerização do site de apresentação do projeto (Nginx).
* **`index.html`**: Página web contendo as justificativas técnicas, resultados esperados e benefícios da adesão ao condomínio.
* **`topologia.imn`**: Arquivo do emulador CORE com a configuração completa dos roteadores, switches e estações de trabalho.

## 🚀 Como Executar o Site (AWS/Docker)
Para rodar a apresentação do projeto em uma instância EC2:

1. Clone este repositório.
2. Construa a imagem:
   ```bash
   docker build -t site-projeto .

## Site IP
http://100.48.47.53/
