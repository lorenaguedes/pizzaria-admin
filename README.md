
```markdown
# 🍕 Pizzaria Admin
Bem-vindo ao **Pizzaria Admin**, o sistema de administração perfeito para gerenciar sua pizzaria de forma eficiente e moderna. Com este projeto, você pode controlar pedidos, cardápio, clientes e muito mais, tudo em um só lugar! 🚀

---

## ✨ Funcionalidades

- **Gestão de Pedidos**: Acompanhe pedidos em tempo real. 📋  
- **Cardápio Digital**: Atualize o cardápio facilmente. 🍕🍝  
- **Integração com Câmera**: Tire fotos dos pratos diretamente do app. 📸  
- **Manipulação de Arquivos**: Armazene e gerencie arquivos no dispositivo. 📁  
- **Multiplataforma**: Funciona em Android, iOS e navegadores. 📱💻  

---

## 🛠️ Tecnologias Utilizadas

- **Node.js** 🟢  
- **Cordova** 📱  
- **Plugins do Cordova**:
  - `cordova-plugin-advanced-http` 🌐  
  - `cordova-plugin-camera` 📷  
  - `cordova-plugin-file` 📂  

---

## 🚀 Como Começar

### Pré-requisitos

- [Node.js](https://nodejs.org/) (versão 16 ou superior)  
- [Cordova](https://cordova.apache.org/) (instalado globalmente via npm)  
- Um emulador ou dispositivo físico para testar o aplicativo.  

### Instalação

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/lorenaguedes/pizzaria.admin.git
   cd pizzaria.admin
   ```

2. **Instale as dependências**:

   ```bash
   npm install
   ```

3. **Adicione plataformas** (Android, por exemplo):

   ```bash
   cordova platform add android
   ```

4. **Execute o projeto**:

   - Para rodar no navegador:

     ```bash
     cordova run browser
     ```

   - Para rodar no emulador Android:

     ```bash
     cordova run android
     ```

   - Para rodar no dispositivo físico (conectado via USB):

     ```bash
     cordova run android --device
     ```

---

## 📂 Estrutura do Projeto

```
pizzaria.admin/
├── www/                  # Arquivos HTML, CSS e JS
├── plugins/              # Plugins do Cordova
├── platforms/            # Plataformas adicionadas (Android, iOS)
├── config.xml            # Configuração do Cordova
├── package.json          # Dependências e scripts
└── README.md             # Este arquivo
```






