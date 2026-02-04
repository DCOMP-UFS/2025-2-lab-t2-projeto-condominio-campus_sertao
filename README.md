# Projeto Integrado: Condomínio de Laboratórios de Computação e Pesquisa

**Campus do Sertão - Universidade Federal de Sergipe (UFS)**

## Identificação Institucional

Este projeto consolida a infraestrutura de redes e computação para 05 (cinco) grupos de pesquisa estratégicos, adotando um modelo de gestão unificada para maximizar o investimento em equipamentos de alto valor (Servidores e Soluções Wireless) e padronizar as estações de trabalho.

* **Instituição:** Universidade Federal de Sergipe (UFS)
* **Unidade:** Campus do Sertão
* **Coordenador Geral da Proposta:** Rafael José Coelho Souza

### Grupos Participantes

A infraestrutura atenderá os seguintes laboratórios, cujos detalhamentos técnicos individuais podem ser consultados em seus respectivos repositórios:

* **Lab RUMENS** - [`Projeto RUMENS`](RUMENS/README.md)
* **Lab COMAFS** - [`Projeto COMAFS`](COMAFS/README.md)
* **Lab GEMS** - [`Projeto GEMS`](GEMS/README.md)
* **Lab GEFiVe** - [`Projeto GEFiVe`](GEFiVe/README.md)
* **Lab GEPPETTO** - [`Projeto GEPPETTO`](GEPPETTO/README.md)

## Justificativa Técnico-Científica e Relevância

A fragmentação de recursos em TI historicamente impede a aquisição de equipamentos de infraestrutura robusta. A proposta de **"Condomínio de Laboratórios"** soluciona este problema centralizando o investimento em itens críticos e distribuindo estações de trabalho padronizadas.

A relevância institucional deste projeto se sustenta em três pilares:

1. **Conectividade Total (Campus-Wide):** A implementação de um sistema robusto de Hotspots Wi-Fi (investimento de R$ 84.000,00) garantirá cobertura de alta densidade não apenas nos laboratórios, mas nas áreas comuns e experimentais, vital para pesquisas de campo e IoT.
2. **Poder de Processamento Centralizado:** A aquisição de um Servidor de Alta Performance (32GB RAM/Xeon) permitirá a virtualização de serviços que hoje rodam precariamente em desktops comuns.
3. **Renovação do Parque Computacional:** A compra em lote de 38 Microcomputadores garante homogeneidade na manutenção e capacidade de processamento para todos os grupos envolvidos.

## Plano de Uso Multiusuário

A infraestrutura central operará sob regras estritas de compartilhamento para garantir a longevidade dos equipamentos:

* **Servidor Central:** Hospedará as máquinas virtuais de Banco de Dados, Aplicações Web e o Controlador da Rede Wi-Fi. O acesso administrativo será restrito à equipe de TI do condomínio.
* **Sistema Wi-Fi (Hotspot):** Gerido centralizadamente. Cada grupo de pesquisa terá sua VLAN (Rede Virtual) dedicada, garantindo que o tráfego de dados sensíveis do Lab 04 não interfira na navegação do Lab 01, por exemplo.
* **Manutenção:** Será realizada trimestralmente pela equipe técnica designada, cobrindo limpeza física dos racks e atualização de softwares de segurança.

## Lista de Itens e Orçamento Integrado

O orçamento reflete a estratégia de **Centralizar a Infraestrutura** e **Distribuir o Acesso**. O valor total da proposta está abaixo do teto de R$ 1.000.000,00, totalizando **R$ 243.353,63**.

### Infraestrutura Compartilhada (O Core do Condomínio)

Itens que atendem a todos os grupos simultaneamente.

| Item | Descrição Técnica | Valor Total |
| --- | --- | --- |
| **Solução Wireless** | Sistema de HotSpot Wi-Fi Corporativo (Alta Densidade) | R$ 84.000,00 |
| **Processamento** | Servidor Rack 32GB RAM DDR4 (Virtualização) | R$ 18.940,00 |
| **Georreferenciamento** | Sistema Global de Posicionamento (Uso compartilhado) | R$ 1.537,69 |
| **Subtotal Core** | *Infraestrutura de uso comum* | **R$ 104.477,69** |

### Distribuição aos Laboratórios (As Pontas)

Itens alocados fisicamente nos laboratórios, mas comprados em lote para economia de escala.

| Item | Quantidade | Descrição | Valor Total |
| --- | --- | --- | --- |
| **Estações de Trabalho** | 38 unid. | Computadores Desktop Básicos + Monitores | R$ 123.576,00 |
| **Periféricos** | 38 kits | Teclados ABNT2 e Mouses Ópticos | R$ 1.580,80 |
| **Conectividade Local** | 5 unid. | Switches 24 Portas 10/100/1000 | R$ 9.510,00 |
| **Organização** | 5 unid. | Mini Racks 6U x 350mm (Parede) | R$ 1.439,10 |
| **Energia Local** | 5 unid. | Nobreaks 600VA + Baterias (Proteção de endpoint) | R$ 2.210,00 |
| **Cabeamento** | 7 unid. | Cabos CAT6 (10m) | R$ 294,91 |
| **Sensores (IoT)** | 20 unid. | Sensores térmicos e eletrônicos diversos | R$ 265,13 |
| **TOTAL GERAL** |  |  | **R$ 243.353,63** |

## Cronograma de Execução

* **Fase 1 (Aquisição):** Adesão às Atas de Registro de Preços e emissão de empenho para os itens de TI.
* **Fase 2 (Infraestrutura):** Instalação física dos Mini Racks nos laboratórios e cabeamento estruturado.
* **Fase 3 (Core):** Configuração do Servidor Central e implantação dos pontos de Hotspot Wi-Fi pelo campus.
* **Fase 4 (Deployment):** Instalação e configuração das 38 estações de trabalho e periféricos.
* **Fase 5 (Operação):** Testes de conectividade, criação das VLANs por grupo e entrega oficial.

## Equipe de Trabalho

Para garantir a execução e prestação de contas, ficam designados:

* **Coordenador Geral:** Rafael Coelho
* **Assistente de Compras/Atas:** Lucas Celestino
* **Contador/Tesoureiro:** Mariana Souza Nunes

## Termo de Compromisso de Compartilhamento

Os líderes dos grupos abaixo assinados declaram concordância com o modelo de aquisição unificada (especialmente quanto ao uso compartilhado do Servidor e da Rede Wi-Fi), comprometendo-se a zelar pelo patrimônio distribuído em seus laboratórios.

1. **Mariana Souza Nunes** (Líder Lab. 01 - RUMENS)
2. **Lucas Maycon Oliveira Menezes** (Líder Lab. 02 - COMAFS)
3. **João Paulo Menezes Machado** (Líder Lab. 03 - GEMS)
4. **Rafael José Coelho Souza** (Líder Lab 04 - GEFiVe)
5. **Lucas Conceicao Celestino** (Líder Lab. 05 - GEPPETTO)
