# V.I.A — Sistema de Verificação Inteligente de Acesso

Sistema de controle de acesso com RFID desenvolvido como TCC no SENAI Celso Charuri.

O projeto utiliza ESP32 + RFID para registrar entradas e saídas de usuários em tempo real através de uma aplicação web desenvolvida com Flask.

---

## Tecnologias

* Python
* Flask
* SQLAlchemy
* PostgreSQL
* HTML/CSS/JavaScript
* ESP32
* RFID RC522

---

## Deploy

Aplicação hospedada no Render:

https://v-ia-eyn8.onrender.com/

Banco de dados PostgreSQL hospedado no Neon.

---

## Login de teste

Email:

```txt
via@gmail.com
```

Senha:

```txt
via2026
```

---

## Funcionalidades

* Login de administradores
* Cadastro de usuários
* Cadastro de cartões RFID
* Registro automático de acesso
* Histórico de entradas e saídas
* Controle de permissões
* Painel administrativo

---

## Estrutura do sistema

```txt
ESP32 + RFID
      ↓
Servidor Flask
      ↓
PostgreSQL
      ↓
Painel Web
```

---

## Como executar

Clone o projeto:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Configure o arquivo `.env`:

```env
DATABASE_URL=
SECRET_KEY=
```

Execute o projeto:

```bash
flask run
```

---

## Desenvolvedores

* Rafael Borges Marchetti
* Rafael Rodrigues de Mattos
* João Victhor Kolling
* Diemerson de Matos

---

## SENAI — Curitiba/PR

Projeto desenvolvido para conclusão do curso Técnico em Desenvolvimento de Sistemas.
