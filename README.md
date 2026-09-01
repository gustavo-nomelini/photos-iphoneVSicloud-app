
# Photos iPhone vs iCloud App 📱💾

## 📌 Descrição
Um utilitário desktop multiplataforma (macOS, Windows e Linux) de código aberto criado para gerenciar, extrair e realizar o backup completo de fotos e vídeos de dispositivos iOS e do iCloud diretamente para unidades de armazenamento local (SSDs). 

O objetivo principal do projeto é oferecer uma solução automatizada para contornar as limitações de download da interface web da Apple (que restringe a 1.000 itens por vez) e evitar a dependência de assinaturas na nuvem ou softwares proprietários de terceiros. A aplicação atua como uma ponte direta entre o ecossistema da Apple e discos rígidos locais.

## 🚀 Funcionalidades Planejadas
* **Extração Direta (USB):** Backup do Rolo da Câmera do iPhone para o SSD sem depender de sincronização online.
* **Sincronização de Nuvem:** Download automatizado da fototeca completa do iCloud.
* **Motor de Deduplicação:** Identificação e limpeza de fotos duplicadas localmente utilizando algoritmos de hashing criptográfico (SHA-256) e perceptual (pHash).
* **Organização Automática:** Leitura de metadados e estruturação inteligente dos diretórios de backup no SSD.

## 🛠️ Stack de Tecnologias
Este projeto foi desenhado com foco em alta performance nativa e portabilidade, utilizando a seguinte arquitetura:

* **Linguagem Principal:** C#
* **Interface Gráfica (UI):** Avalonia UI (Utilizando o padrão de arquitetura MVVM)
* **Runtime:** .NET SDK
* **Comunicação iOS:** Integração planejada via `libimobiledevice` para leitura profunda do sistema de arquivos de dispositivos conectados via USB sem travas comerciais.

## 💻 Como Executar o Projeto Localmente

**Pré-requisitos:**
* Ter o [.NET SDK](https://dotnet.microsoft.com/download) instalado.

**Passo a passo:**
1. Clone o repositório:
   ```bash
   git clone [https://github.com/gustavo-nomelini/photos-iphoneVSicloud-app.git](https://github.com/gustavo-nomelini/photos-iphoneVSicloud-app.git)
