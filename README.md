# Chef Claude 🧑‍🍳✨

[![Feito com React](https://img.shields.io/badge/feito%20com-React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Powered by Vite](https://img.shields.io/badge/powered%20by-Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Status do Projeto](https://img.shields.io/badge/status-completo-brightgreen?style=for-the-badge)]()

Um gerador de receitas inteligente construído com **React** e **Vite**, utilizando a **Hugging Face Inference API**.  
Baseado nos ingredientes fornecidos pelo utilizador, gera uma receita personalizada formatada em Markdown!

## 🚀 Tecnologias usadas
- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Hugging Face Inference API](https://huggingface.co/inference-api)
- JavaScript (ES6+)
- HTML5 & CSS3

## 🎯 Funcionalidades
- ➕ Adicionar ingredientes manualmente.
- 🍲 Gerar receitas baseadas nos ingredientes escolhidos.
- 🧹 Interface limpa, responsiva e moderna.
- 📄 Saída formatada em **Markdown** para melhor visualização.
- 🔐 Gestão segura de chaves de API através de variáveis de ambiente.

## 📸 Captura de Ecrã
![Chef Claude Screenshot](./images/chef-claude-png.png)  

## ⚙️ Como correr localmente
```bash
git clone https://github.com/GuilhermeSilvaDev/chef-claude.git
cd chef-claude
npm install
# Criar ficheiro .env com a tua Hugging Face token
# VITE_HF_ACCESS_TOKEN=your_huggingface_token
npm run dev

⚠️ Notas de Segurança

🚨 Nunca partilhes o ficheiro .env ou as tuas chaves de API!
Este projeto já contém um .gitignore para proteger as variáveis de ambiente.
Para deploy público (Netlify, Vercel, etc.), é recomendado usar um backend para proteger as chaves.
📚 Aprendizagens neste projeto

    Criação de componentes React funcionais.

    Gerir estados (useState) e eventos em formulários.

    Integração de API externa (Hugging Face Inference).

    Configuração de variáveis de ambiente no Vite (import.meta.env).

    Boas práticas de segurança em projetos React.

📄 Licença

Projeto criado como parte do curso React - Scrimba.
Uso livre para fins educacionais e pessoais.
👨‍💻 Autor

Guilherme Silva
GitHub