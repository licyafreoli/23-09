# 🕹️ Formulário de Inscrição - Campeonato de E-Sports

Este é um formulário de inscrição para um campeonato de e-sports, desenvolvido com **HTML** e estilizado com **Tailwind CSS**. O objetivo é coletar informações essenciais dos jogadores de forma clara e validada.

## ✨ Funcionalidades

O formulário contém os seguintes campos:

- **Nome do Jogador** (campo de texto)
- **Jogo Preferido** (menu `<select>`)
  - Valorant
  - League of Legends (LoL)
  - Counter-Strike (CS)
  - Fortnite
- **Plataforma Utilizada** (opções via radio button)
  - PC
  - Console
  - Mobile
- **Tag do Jogador** (campo de texto)
- **Upload de Gameplay** (aceita arquivos `.mp4` ou `.mov`)
- **E-mail de Contato** (validação automática de e-mail)
- **Número de Telefone**
- **CPF do Jogador** (obrigatório, até 11 caracteres numéricos)
- **Concordância com as Regras**
  - Checkbox: "Li e aceito as regras do campeonato" (obrigatório)
- **Criação de Senha**
  - Campo obrigatório para acesso ao painel do jogador

## 🧪 Tecnologias Utilizadas

- **HTML5**
- **Tailwind CSS**
- (Opcional) **JavaScript** para validações e interações

## ✅ Validações e Regras

- O CPF aceita somente números (até 11 caracteres).
- O e-mail deve estar no formato válido (com `@` e domínio).
- O upload aceita apenas arquivos de vídeo `.mp4` ou `.mov`.
- A senha é obrigatória.
- O formulário não é enviado sem a marcação da caixa de concordância com as regras.


## 🚀 Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Instale o Tailwind CSS (caso esteja usando via CLI):
   ```bash
   npm install -D tailwindcss
   npx tailwindcss init
   ```
3. Compile o CSS:
   ```bash
   npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
   ```
4. Abra o arquivo `index.html` no navegador.

## 📄 Licença

Este projeto é de uso **educacional e demonstrativo**. Sinta-se à vontade para reutilizar, adaptar ou expandir conforme sua necessidade.

---

Desenvolvido para inscrições em campeonatos de e-sports 🎮 com design moderno via Tailwind CSS.
