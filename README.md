# DevOps Tools 2026 - Exercícios Práticos 🧪

**Sistema de exercícios automatizados** para a disciplina DevOps Tools (UNINASSAU 2026.1).

---

## 🎯 Como Funciona

1. **Fork** este repositório
2. **Clone** seu fork
3. **Crie branch** por exercício (`git checkout -b exercicio-01-seu-nome`)
4. **Resolva** o exercício na pasta correspondente
5. **Commit + Push** suas alterações
6. **Abra Pull Request** para o repo original
7. **GitHub Actions** valida automaticamente seu código
8. **Pontuação** aparece no leaderboard (se score ≥ 70)

**IMPORTANTE:** PRs **NÃO são mergeados**. Eles ficam abertos/fechados apenas para validação. Isso garante que as soluções permaneçam privadas.

---

## 📊 Leaderboard

Acompanhe o ranking em tempo real:  
**🏆 [Ver Leaderboard](https://petrosbarreto.github.io/devops-tools-2026-exercicios/leaderboard.html)**

Atualização automática a cada PR validado.

---

## 📁 Estrutura dos Exercícios

```
exercicios/
├── aula01/
│   ├── README.md          # Enunciado
│   ├── .github/
│   │   └── workflows/
│   │       └── validate.yml  # Testes automáticos
│   └── solucao/           # Sua solução aqui
├── aula02/
├── aula03/
...
```

---

## 🚀 Guia Rápido

### 1️⃣ Setup Inicial (uma vez)

```bash
# Fork no GitHub (botão "Fork")

# Clone SEU fork
git clone https://github.com/SEU-USUARIO/devops-tools-2026-exercicios.git
cd devops-tools-2026-exercicios

# Configure upstream (repo original)
git remote add upstream https://github.com/petrosbarreto/devops-tools-2026-exercicios.git
```

### 2️⃣ Para Cada Exercício

```bash
# Atualize seu fork
git checkout main
git pull upstream main

# Crie branch
git checkout -b exercicio-01-seunome

# Resolva o exercício (edite arquivos em exercicios/aula01/)
code exercicios/aula01/solucao/

# Commit
git add .
git commit -m "feat(aula01): resolve exercício introdução DevOps"

# Push para SEU fork
git push origin exercicio-01-seunome

# Abra PR no GitHub
# (GitHub vai sugerir automaticamente após o push)
```

### 3️⃣ Acompanhar Validação

Após abrir o PR:
1. Vá na aba **"Checks"** do seu PR
2. Veja os testes rodando
3. **Verde ✅:** Passou! Score aparece no leaderboard
4. **Vermelho ❌:** Falhou. Veja os logs, corrija e faça novo push

---

## 📝 Lista de Exercícios

| Aula | Tema | Dificuldade | Status |
|------|------|-------------|--------|
| 01 | Identificar Silos DevOps | ⭐ Fácil | 🚧 Em breve |
| 02 | Sprint Planning DevOps | ⭐⭐ Médio | 🚧 Em breve |
| 03 | Git Básico (branches, merge) | ⭐ Fácil | 🚧 Em breve |
| 04 | GitHub Actions CI Simples | ⭐⭐ Médio | 🚧 Em breve |
| 05 | Pipeline CI/CD Completo | ⭐⭐⭐ Difícil | 🚧 Em breve |
| 06 | Dockerfile Node.js App | ⭐⭐ Médio | 🚧 Em breve |
| 07 | Multi-stage Dockerfile | ⭐⭐⭐ Difícil | 🚧 Em breve |
| 08 | docker-compose (web+db) | ⭐⭐ Médio | 🚧 Em breve |
| 09 | Build + Push Docker Hub | ⭐⭐ Médio | 🚧 Em breve |
| 10 | Deploy Kubernetes (Minikube) | ⭐⭐⭐ Difícil | 🚧 Em breve |
| 11 | ConfigMap + Secrets | ⭐⭐ Médio | 🚧 Em breve |
| 12 | Ingress + TLS | ⭐⭐⭐ Difícil | 🚧 Em breve |
| 13 | Helm Chart Customizado | ⭐⭐⭐ Difícil | 🚧 Em breve |
| 14 | Agregação Logs (Loki) | ⭐⭐ Médio | 🚧 Em breve |
| 15 | Query Elasticsearch | ⭐⭐ Médio | 🚧 Em breve |
| 16 | Logstash Pipeline (grok) | ⭐⭐⭐ Difícil | 🚧 Em breve |
| 17 | Dashboard Kibana | ⭐⭐ Médio | 🚧 Em breve |
| 18 | **PROJETO FINAL** | ⭐⭐⭐⭐ Desafiador | 🚧 Em breve |

**Total:** 18 exercícios + 1 projeto final

---

## 🏆 Sistema de Pontuação

Cada exercício vale **0-100 pontos**:

- **100:** Perfeito (testes passaram, código limpo, documentado)
- **90-99:** Ótimo (testes OK, pequenos ajustes)
- **80-89:** Bom (funciona, mas pode melhorar)
- **70-79:** Aceitável (mínimo para aparecer no leaderboard)
- **0-69:** Não passou (testes falharam ou incompleto)

**Ranking:**
- 🥇 **Ouro:** 1800-2000 pontos
- 🥈 **Prata:** 1600-1799
- 🥉 **Bronze:** 1400-1599
- 🎖️ **Aprovado:** 1000-1399 (média 7.0)

---

## ❓ FAQs

### **1. Posso ver a solução de outros alunos?**

**NÃO.** PRs não são mergeados, então soluções ficam privadas nos forks de cada um.  
Copiar código é contra as regras e detectável (análise de plágio automática).

### **2. O que fazer se o teste falhar?**

1. Veja os **logs de erro** na aba "Checks" do PR
2. **Corrija** o código localmente
3. **Commit + push** novamente (mesmo branch)
4. O PR será **re-validado automaticamente**

### **3. Posso refazer um exercício?**

**SIM!** Faça novo push no mesmo PR. O score será atualizado.

### **4. Preciso fazer TODOS os exercícios?**

Para média 7.0, precisa de ~1260 pontos (63% de 2000).  
Mas recomendamos fazer todos — o aprendizado é cumulativo!

### **5. Posso trabalhar em grupo?**

**NÃO** nos exercícios individuais.  
**SIM** no projeto final (duplas, com aprovação do professor).

### **6. Quando os exercícios serão liberados?**

Após cada aula. Ex: Aula 01 → Exercício 01 liberado no mesmo dia.

---

## 🛠️ Requisitos Técnicos

- **Git** instalado
- **Conta GitHub** (gratuita)
- **Docker** (a partir da aula 06)
- **Kubectl + Minikube** (a partir da aula 10)

---

## 📧 Suporte

**Dúvidas sobre exercícios:**
- Abra **Issue** neste repo com tag `question`
- Ou pergunte no grupo da turma

**Problemas técnicos (GitHub Actions):**
- Tag `bug` na issue

**Professor:**  
📧 petrosbarreto01@gmail.com

---

## 🔗 Links Úteis

- **[Slides das Aulas](https://github.com/petrosbarreto/devops-tools-2026)**
- **[Leaderboard](https://petrosbarreto.github.io/devops-tools-2026-exercicios/leaderboard.html)**
- **[Como Fazer PR](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)**
- **[Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)**

---

<div align="center">

**🎓 Bons estudos e bom código! 🚀**

![DevOps](https://img.shields.io/badge/DevOps-Practice-FF6B6B?style=for-the-badge)
![GitHub Actions](https://img.shields.io/badge/Auto_Grading-Enabled-2088FF?style=for-the-badge)

**UNINASSAU Recife | 2026.1**

</div>
