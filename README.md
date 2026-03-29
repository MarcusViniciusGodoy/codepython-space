# 🚀 Django Project

Este projeto foi desenvolvido utilizando o framework **Django**.

---

## 📋 Pré-requisitos

Antes de iniciar, verifique se você possui as seguintes ferramentas instaladas na sua máquina:

### 🔹 Python

```bash
python3 --version
```

ou

```bash
python --version
```

---

### 🔹 Pip

```bash
pip --version
```

ou

```bash
pip3 --version
```

---

### 🔹 Venv (ambiente virtual)

```bash
python3 -m venv --help
```

---

### 🔹 Django (opcional)

```bash
python -m django --version
```

---

## ⚙️ Como rodar o projeto

### 🔹 1. Clonar o repositório

```bash
git clone <URL_DO_REPOSITORIO>
cd <NOME_DO_PROJETO>
```

---

### 🔹 2. Criar ambiente virtual

```bash
python3 -m venv venv
```

---

### 🔹 3. Ativar o ambiente virtual

#### Linux / Mac:

```bash
source venv/bin/activate
```

#### Windows:

```bash
venv\Scripts\activate
```

---

### 🔹 4. Atualizar o pip (recomendado)

```bash
pip install --upgrade pip
```

---

### 🔹 5. Instalar dependências

Se existir um arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

Caso contrário:

```bash
pip install django
```

---

### 🔹 6. Rodar migrações

```bash
python manage.py migrate
```

---

### 🔹 7. Executar o projeto

```bash
python manage.py runserver
```

---

## 🌐 Acessar aplicação

Abra o navegador e acesse:

http://127.0.0.1:8000/

---

## 🛑 Parar o servidor

Pressione:

CTRL + C

---

## 💡 Observações

* Sempre ative o ambiente virtual antes de rodar o projeto
* Utilize `requirements.txt` para gerenciar dependências
* Evite instalar pacotes globalmente

---

## 📁 Estrutura básica

```
├── manage.py
├── venv/
├── app/
├── config/
└── requirements.txt
```

---

## 👨‍💻 Autor

Desenvolvido por **Marcus Vinicius**
