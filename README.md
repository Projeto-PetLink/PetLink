# 🐾 PetLink

Sistema de gerenciamento de adoção de pets para ONGs e abrigos.

O PetLink conecta adotantes a animais disponíveis para adoção, permitindo que organizações façam o controle completo de pets, solicitações e aprovações de forma simples e organizada.

---

# 📸 Preview

<img src="./docs/banner.png" alt="PetLink Banner">

---

# ✨ Features

O projeto facilita:

- Cadastro de pets para adoção
- Controle de status dos animais
- Galeria de fotos
- Filtros por espécie e idade
- Solicitações de adoção
- Gerenciamento de solicitações
- Aprovação de adoções
- Controle administrativo para ONGs

---

# 👥 Usuários do Sistema

## ❤️ Adotante

O adotante pode:

- Visualizar pets disponíveis
- Filtrar animais
- Ver fotos e informações
- Solicitar adoção
- Acompanhar solicitações

---

## 🛠️ Voluntário (Admin)

O voluntário pode:

- Cadastrar pets
- Editar informações
- Alterar status do pet
- Gerenciar solicitações
- Aprovar ou recusar adoções

---

# 📌 Regras de Negócio

- Um adotante pode solicitar vários pets
- Apenas uma adoção pode ser aprovada por vez
- Pets adotados ficam indisponíveis
- Todas as solicitações ficam registradas

---

# 🧱 Arquitetura

```txt
Frontend → API REST → Banco de Dados
