# 🦉 EduQuest — Plataforma de Ensino Gamificado

> **Projeto Acadêmico** — Sistema web de aprendizado gamificado com três perfis de usuário: Aluno, Pais e Professor.

![EduQuest Preview](https://img.shields.io/badge/EduQuest-Plataforma%20Educacional-7C3AED?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgo=)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🎮 Sobre o Projeto

O **EduQuest** é uma plataforma educacional gamificada desenvolvida como projeto acadêmico. A proposta é transformar o estudo em uma experiência de jogo, onde alunos ganham XP, sobem de nível, completam missões e competem em rankings — tudo enquanto aprendem conteúdos escolares reais.

### 💡 Problema que Resolve

O desengajamento dos estudantes com o conteúdo escolar tradicional. Ao aplicar mecânicas de jogos (gamificação), o EduQuest aumenta a motivação e o tempo de estudo de forma orgânica.

---

## ✨ Funcionalidades

### 🦊 Área do Aluno (`dashboard.html`)
- 🎮 **Sistema de XP & Níveis** — Ganhe experiência em cada atividade
- 💰 **Moedas & Loja** — Troque moedas por itens e personalizações
- 🔥 **Streak Diário** — Bônus por dias consecutivos de estudo
- 📋 **Missões** — Diárias, semanais e especiais criadas pelo professor
- 🧠 **Quiz com Timer** — Perguntas cronometradas em 6 matérias
- 🏆 **Ranking** — Tabela de pontuação da turma
- ⏱️ **Modo Foco (Pomodoro)** — Sessões de 25 minutos com bonificação
- 🏅 **Conquistas e Badges** — Desbloqueie ao atingir marcos
- 💬 **Chat com Mascote** — Interação com o mascote Coruja
- 🛒 **Loja de Avatares** — Personalize seu perfil

### 👨‍👩‍👧 Área dos Pais (`pais.html`)
- 📊 Visão geral do desempenho dos filhos
- 📈 Gráfico de progresso semanal e por matéria
- 🎯 Definição e acompanhamento de metas
- 🔔 Alertas de baixo engajamento e conquistas
- 🏅 Histórico de badges conquistados

### 👩‍🏫 Área do Professor (`professor.html`)
- 📊 Dashboard com estatísticas da turma
- 📝 Criação de questões personalizadas por matéria e dificuldade
- 🎯 Criação de missões com recompensas configuráveis
- 👩‍🎓 Tabela detalhada de alunos com XP, streak e status
- 🏆 Ranking dos melhores alunos
- 📈 Relatório de desempenho por matéria
- ⚠️ Lista de alunos que precisam de atenção

---

## 📁 Estrutura do Projeto

```
eduquest/
├── index.html          # Landing page (página inicial)
├── login.html          # Login e cadastro de usuários
├── dashboard.html      # Dashboard do Aluno
├── pais.html           # Área dos Pais / Responsáveis
├── professor.html      # Área do Professor
└── README.md           # Este arquivo
```

---

## 🚀 Como Usar

### Opção 1 — Abrir diretamente no navegador
1. Clone ou baixe este repositório
2. Abra o arquivo `index.html` no navegador
3. Clique em **"Entrar na Plataforma"** para ir ao login

### Opção 2 — GitHub Pages (recomendado)
1. Faça o fork ou envie os arquivos para um repositório GitHub
2. Vá em **Settings → Pages**
3. Em **Source**, selecione `main` branch e pasta `/root`
4. Acesse pelo link gerado: `https://seu-usuario.github.io/eduquest/`

### Credenciais de Demonstração

| Perfil | E-mail | Senha |
|--------|--------|-------|
| 🦊 Aluno | `aluno@demo.com` | `123456` |
| 👨‍👩‍👧 Pais | `pais@demo.com` | `123456` |
| 👩‍🏫 Professor | `prof@demo.com` | `123456` |

> **Nota:** Os dados ficam salvos no `localStorage` do navegador. Para criar uma conta real, use a aba **Cadastro** na tela de login.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|------------|-----|
| **HTML5** | Estrutura das páginas |
| **CSS3** | Estilização, animações, responsividade |
| **JavaScript (Vanilla)** | Lógica de gamificação, localStorage, UI |
| **Google Fonts** | Tipografia (Fredoka One + Nunito) |
| **Web Audio API** | Sons ambientes no modo foco |
| **Canvas API** | Animação de partículas na landing page |

---

## 🎨 Design System

| Elemento | Valor |
|----------|-------|
| Cor primária | `#7C3AED` (Roxo) |
| Cor secundária | `#F59E0B` (Âmbar) |
| Cor de destaque | `#10B981` (Verde) |
| Background | `#0F0A1E` (Roxo escuro) |
| Fonte título | Fredoka One |
| Fonte corpo | Nunito |

---

## 📱 Responsividade

O projeto é totalmente responsivo e funciona em:
- 🖥️ Desktops e monitores
- 💻 Notebooks
- 📱 Smartphones (sidebar recolhida)
- 📲 Tablets

---

## 🔒 Armazenamento de Dados

Todo o armazenamento é feito no **localStorage** do navegador, sem necessidade de banco de dados ou backend. Os dados são salvos localmente no dispositivo do usuário.

```javascript
// Estrutura de um usuário
{
  id: "u_1234567890",
  nome: "Nome do Aluno",
  email: "aluno@email.com",
  role: "aluno", // "aluno" | "pais" | "professor"
  avatar: "🦊",
  moedas: 500,
  xp: 1200,
  nivel: 5,
  streak: 7,
  missoes: [],
  badges: ["🏆", "⭐"],
  createdAt: 1234567890
}
```

---

## 🎓 Contexto Acadêmico

Projeto desenvolvido para a disciplina de **[Nome da Disciplina]** do curso de **[Nome do Curso]** — **[Nome da Faculdade]**.

**Objetivo:** Aplicar conceitos de UX/UI, desenvolvimento web front-end e gamificação para criar uma solução educacional funcional.

---

## 👥 Equipe

| Nome | Função |
|------|--------|
| [Seu Nome] | Desenvolvimento Full-Stack |

---

## 📄 Licença

Este projeto é de uso acadêmico. Todos os direitos reservados aos autores.

---

<div align="center">
  <strong>🦉 EduQuest — Aprenda. Evolua. Conquiste.</strong><br>
  <em>Transformando o estudo em aventura.</em>
</div>
