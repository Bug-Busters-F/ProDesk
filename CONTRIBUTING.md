# Como Contribuir - Seu Passaporte de Entrada

Estamos felizes em receber você aqui e saber que está interessado em contribuir para o nosso projeto. Como um projeto de código aberto, cada contribuição é valorizada e ajuda a impulsionar o crescimento e a qualidade do nosso trabalho.

Este guia foi criado para orientá-lo sobre como você pode participar tanto do **backend** quanto do **mobile**, que fazem parte deste repositório principal.

---

## Código de Conduta

Para garantir um ambiente respeitável e inclusivo, leia e siga nosso [Código de Conduta](./CODE_OF_CONDUCT.md).

---

## Começando a Contribuir

Antes de começar, você precisará configurar algumas ferramentas e preparar seu ambiente de desenvolvimento.

###  Requisitos Gerais

- Uma conta no GitHub  
- Git instalado  
- Um IDE (recomendado: Visual Studio Code)  
- Node.js v22.11.0 ou superior  

---

## Estrutura do Projeto

Este repositório contém dois submódulos:

- `backend` → API e lógica de negócio  
- `mobile` → Aplicação mobile  

---

# Backend

## Requisitos adicionais

- MongoDB Community Server  

---

## Instalação

### 1. Clonar o repositório principal

```bash
git clone https://github.com/Bug-Busters-F/ProDesk
cd ProDesk
```

### 2. Inicializar submódulos

```bash
git submodule update --init --recursive
```

### 3. Acessar o backend

```bash
cd backend
```

### 4. Instalar dependências

```bash
npm install
```

### 5. Configurar variáveis de ambiente

```bash
cp .env.example .env
```

Edite o `.env`:

```env
# DATABASE
MONGO_URI=mongodb://localhost:27017/prodesk

# APP
PORT=3000
NODE_ENV=development
```

---

## Rodar o backend

```bash
npm run start:dev
```

---

#  Mobile

## Requisitos adicionais

- Java JDK 17  
- Android Studio  

---

## Instalação

### 1. Acessar o mobile

```bash
cd mobile
```

### 2. Instalar dependências

```bash
npm install
```

---

## Rodar o mobile

```bash
npx expo start
```