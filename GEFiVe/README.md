# Identificação do Projeto de Redes

## Nome do Técnico responsável:
**Rafael José Coelho Souza**

## Resumo descritivo
Este projeto apresenta a arquitetura lógica e física de redes para o **Grupo de Estudos em Fisiologia Vegetal (GEFiVe)**. Adotando o modelo estratégico de "Condomínio de Laboratórios", a proposta viabiliza o acesso a recursos de segurança e processamento de nível corporativo (Firewall Enterprise, NAS, Virtualização) através do rateio de custos com outros grupos do campus.

O diferencial deste projeto reside na **integração entre TI e Agro**: enquanto a infraestrutura central garante a segurança dos dados, o investimento individual do laboratório foi priorizado para **IoT e Mobilidade**, estendendo a conectividade para estufas e áreas de experimentação via Wi-Fi Outdoor e sensores de monitoramento climático.

## Documentos técnicos

Abaixo estão os artefatos essenciais que detalham o planejamento e a implementação da rede:

### 1. Topologia de Rede
Diagrama visual da infraestrutura lógica e física, demonstrando a hierarquia de conexão (Campus → Laboratório → Estufa), a segmentação por VLANs (IoT, Adm, Visitantes) e a extensão óptica para Access Points Outdoor.
* **Visualizar:** [`docs/topologia.png`](docs/topologia.png)

### 2. Orçamento e Viabilidade (Modelo Condomínio)
Detalhamento financeiro respeitando o teto de R$ 50.000,00. A estratégia de adesão ao condomínio gerou uma economia de infraestrutura que permitiu a aquisição de:
* 1x Switch L3/L2 Intelbras SC 3170-24G-4X (Uplink 10Gbps).
* 2x Access Points (1 Indoor + 1 Outdoor IP67).
* Kit de Sensores IoT e Gateway.
* **Arquivo:** [`docs/orcamento.md`](docs/orcamento.md)

### 3. Levantamento de Requisitos
Documento base contendo as necessidades específicas do cliente (GEFiVe), focadas em mobilidade na estufa, redundância de energia para dataloggers e segurança de dados de pesquisa.

---

### Estrutura do Repositório
A organização dos arquivos neste repositório segue a estrutura abaixo:

```text
/ (Raiz)
├── Dockerfile              <-- (Arquivo de configuração da imagem Docker)
├── docker-compose.yml      <-- (Orquestração do serviço web)
├── index.html              <-- (Código fonte do site institucional)
├── README.md               <-- (Este documento)
└── docs/                   <-- (Documentação complementar)
    ├── topologia-logica.png
    └── orcamento.pdf
```


**IP disponível para o site do GEFiVe: http://100.51.204.194:8080/**
