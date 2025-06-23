# 🏕️ Projeto Integrador - E-commerce de Itens de Camping e Sobrevivência - Wilderness Store

Este projeto foi desenvolvido como parte do **Projeto Integrador do SENAI**. A proposta foi criar um protótipo visual de **e-commerce focado em equipamentos para camping, trilhas e sobrevivência**, utilizando apenas **HTML** e **CSS** para a interface, enquanto as soluções de **controle de estoque** e **notificações automatizadas** foram implementadas com **C** (para hardware) e **Python**.

⚠️ **Importante**: O site apresentado é um **protótipo visual** e não possui funcionalidades reais como carrinho de compras, login ou banco de dados. O objetivo foi criar uma interface interativa que simule a navegação de uma loja online e também apresente a possibilidade de automação para controle de estoque.

---

## 📌 Objetivo

Desenvolver a interface de uma loja virtual especializada em **itens de camping, trilha e sobrevivência**, com destaque para a apresentação de produtos como barracas, mochilas, lanternas, facas táticas e kits de primeiros socorros. Além disso, o projeto inclui a simulação de um sistema automatizado para **controle de estoque** e **notificações sobre níveis de produtos**.

---

## 🧱 Tecnologias Utilizadas

- **HTML5 / CSS3** – Para construção da interface visual e estilização do site.
- **C (.ino)** – Código de automação para microcontrolador **ESP32/ESP8266**, simulando sensores de estoque.
- **Python** – Para automação de notificações via **WhatsApp** e **e-mail**.
- **OpenSSL** – Geração de certificado SSL autoassinado para simular a segurança HTTPS.

---

## 🌐 Funcionalidades

### 🌿 **Interface Visual da Loja** (HTML e CSS)
- **Página Inicial** com destaque para categorias como "Equipamentos de Acampamento", "Acessórios de Sobrevivência" e "Kits de Primeiros Socorros".
- **Listagem de Produtos** organizada por categoria e com informações detalhadas sobre cada item.
- **Detalhes do Produto** com imagens, descrição, preços e especificações.
- **Área de Busca** com filtros interativos para facilitar a navegação e encontrar produtos específicos.
- **Simulação de Fluxo de Compra**, com telas de carrinho e checkout (sem funcionalidades reais).

### 🔐 **Simulação de Conexão Segura (SSL)**
- Utilização do **OpenSSL** para criar um **certificado SSL autoassinado**, simulando uma conexão segura **HTTPS**.
- A medida visa representar de maneira simples como a segurança de dados seria implementada em um e-commerce real.

### 📦 **Monitoramento de Estoque** (C)
- **Código em C** desenvolvido para ser executado em microcontroladores como o **ESP8266**.
- Simulação de **sensores de estoque** que medem o nível de itens como barracas, mochilas e lanternas em estoque.
- Os dados de estoque são exportados em tempo real para uma **planilha Google Sheets**, gerando relatórios com o status do inventário.

### 📲 **Notificações Automáticas** (Python)
- **Scripts em Python** para ler os relatórios de estoque da planilha e enviar **alertas automáticos**.
- As notificações incluem mensagens por **WhatsApp**, utilizando a biblioteca **pyautogui**, e **e-mails** informando o status atual do estoque.
- O objetivo é garantir que o administrador da loja seja notificado quando algum item estiver em falta ou com quantidade crítica.

