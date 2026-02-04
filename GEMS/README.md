# Laboratório de Melhoramento Vegetal do Semiárido

## Nome do Técnico responsável:
**João Paulo Menezes Machado**

## Objetivo do Projeto
O objetivo deste projeto é desenvolver a infraestrutura de rede para o **Laboratório de Melhoramento Vegetal do Semiárido**, permitindo que estudantes e pesquisadores tenham acesso eficiente e seguro a dados, aplicações e recursos de pesquisa. A rede foi projetada para suportar conectividade entre estações de trabalho, servidores e dispositivos opcionais, garantindo segmentação adequada (VLANs), gerenciamento de tráfego e confiabilidade operacional do laboratório.

## Requisitos Específicos do Cliente
1. **Rede Local Segura e Funcional**
   - Conexão entre PCs, servidores e dispositivos IoT opcionais.
   - Segmentação da rede por VLANs para separar diferentes grupos de usuários e funções.

2. **Servidores e Armazenamento**
   - Servidor central para dados de pesquisa.
   - Possibilidade de integração futura com servidor web ou banco de dados.

3. **Infraestrutura Física**
   - Rack para organização dos equipamentos.
   - Cabeamento estruturado (Cat6 ou superior).
   - Nobreak para proteção elétrica e continuidade das operações.

4. **Facilidade de Acesso e Uso**
   - Permitir que estudantes e pesquisadores acessem dados e aplicações sem interrupções.
   - Infraestrutura simples, confiável e de fácil manutenção.

5. **Orçamento**
   - Limite total: R$50.000, garantindo que todos os equipamentos essenciais caibam dentro desse valor.

## Descrição Técnica Resumida
A topologia da rede é composta por estações de trabalho, um servidor central, switches e roteador/gateway, permitindo acesso seguro e segmentado aos recursos do laboratório. VLANs separam as diferentes funções e usuários, enquanto a infraestrutura física conta com rack, cabeamento estruturado e nobreak, garantindo organização, confiabilidade e continuidade das operações.

## Estrutura do Projeto
- `/dockerfiles` – Dockerfile e arquivos para deploy do site.
- `/docs` – Documentação adicional, imagens e PDFs.
- `/site` – Código do site do laboratório.
- `/topologia` – Arquivos da topologia de rede (.imn e PDF).

---

## Link do site de demonstração

Link: http://3.80.141.252

> **Nota:** Este repositório serve como documentação e implementação da rede do Laboratório de Melhoramento Vegetal do Semiárido, podendo ser usado para ensino, simulação e manutenção das operações.
