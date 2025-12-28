# IntGest Legislativo 🏛️

![Status](https://img.shields.io/badge/Status-Em_Produção-success?style=for-the-badge) ![Tech](https://img.shields.io/badge/Tech-Flutter_|_Dart-blue?style=for-the-badge)

> **Nota:** Este repositório é um **estudo de caso** de um software proprietário desenvolvido por mim na [IntellGest](https://www.linkedin.com/company/intellgest/). Ele serve como demonstração de portfólio técnico e **não contém o código-fonte original**.

---

## 📱 Sobre o Projeto

O **IntGest Legislativo** é uma solução móvel robusta projetada para modernizar a comunicação entre as Câmaras Municipais e os cidadãos, além de otimizar o trabalho dos parlamentares.

O aplicativo atua como um hub central de transparência e operação legislativa, permitindo o acompanhamento em tempo real de sessões plenárias (físicas e virtuais), acesso à legislação completa (Federal, Estadual e Municipal) e detalhamento da produção dos vereadores.

## 👨‍💻 Meu Papel: Desenvolvimento End-to-End

Como Engenheiro Mobile principal do projeto, fui responsável por **todo o ciclo de vida do produto**, desde a concepção da arquitetura inicial até a publicação final nas lojas (Google Play e App Store).

* **Arquitetura:** Definição de uma estrutura escalável (Clean Architecture) capaz de suportar múltiplas câmaras (multi-tenant) com uma única base de código.
* **Desenvolvimento:** Implementação de 100% do código Flutter/Dart.
* **Deploy & CI/CD:** Gerenciamento das contas de desenvolvedor e processo de publicação e atualização nas lojas da Apple e Google.

## 🚀 Principais Funcionalidades & Desafios

### 1. Integração com Plenário em Tempo Real 🗳️
O maior desafio técnico foi criar uma comunicação bidirecional, estável e de baixa latência entre o aplicativo móvel e o sistema físico do plenário eletrônico.
* **Solução:** Implementação de **WebSockets** para permitir que vereadores registrem presença e acompanhem votações instantaneamente pelo celular, e que cidadãos assistam às sessões virtuais sem atrasos.

### 2. Geração Móvel de Proposições 📜
Desenvolvimento de um módulo complexo que permite aos parlamentares redigir e protocolar proposições legislativas oficiais diretamente do smartphone. Isso envolveu a criação de formulários dinâmicos e validações rigorosas para garantir a integridade jurídica dos documentos.

### 3. Portal de Transparência Centralizado 🔍
Criação de interfaces otimizadas para busca e visualização de grandes volumes de dados públicos, incluindo:
* Perfil completo e produção legislativa de cada vereador.
* Acervo completo de Leis Federais, Estaduais e Municipais.
* Inscrição digital para uso da tribuna.

## 🛠️ Tech Stack & Arquitetura

O projeto foi construído sobre pilares de manutenibilidade e performance:

* **Linguagem:** Dart
* **Framework:** Flutter
* **Gerência de Estado:** MobX + Provider (Separação clara entre UI e Regras de Negócio)
* **Arquitetura:** Clean Architecture modularizado por features
* **Comunicação:** REST APIs e WebSockets
