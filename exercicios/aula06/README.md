# Exercício Aula 06: Continuous Integration (CI)

## 🎯 Objetivo

Pipeline CI com múltiplos jobs paralelos

---

## 📋 Requisitos

- Repositório GitHub
- GitHub Actions habilitado
- Conhecimento básico de YAML

---

## 📝 Descrição do Exercício

### Contexto

Aplique os conceitos de **Continuous Integration (CI)** em um cenário prático do dia a dia de um profissional DevOps.

### Tarefas

1. [ ] Criar workflow `.github/workflows/ci.yml`
2. [ ] Configurar trigger (push + pull_request)
3. [ ] Adicionar jobs (build, test, lint)
4. [ ] Testar com commit real
5. [ ] Documentar pipeline no README

---

## 🚀 Como Entregar

1. **Fork** este repositório
2. **Clone** seu fork
3. Crie pasta `solucoes/seu-nome/aula06/`
4. Adicione seus arquivos:
   - `README.md` (documentação)
   - Código/configurações
   - Screenshots (se aplicável)
5. **Commit** e **Push**
6. Abra **Pull Request**: `[Aula 06] Seu Nome`

---

## ✅ Critérios de Avaliação

| Critério | Pontos | Descrição |
|----------|--------|-----------|
| **Funcionalidade** | 40 | Código/config funciona conforme especificado |
| **Boas Práticas** | 30 | Organização, nomenclatura, padrões |
| **Documentação** | 20 | README claro, screenshots, explicações |
| **Qualidade** | 10 | Código limpo, comentários, criatividade |
| **TOTAL** | **100** | |

---

## 🤖 Validação Automática

O bot irá verificar:

- ✅ Arquivo `.github/workflows/*.yml` presente
- ✅ Sintaxe YAML válida
- ✅ Jobs configurados corretamente
- ✅ Workflow executou com sucesso

**Feedback automático em ~30 segundos após abrir PR!** 🚀

---

## 💡 Dicas

- Valide YAML online: https://www.yamllint.com/
- GitHub Actions marketplace tem actions prontas
- Use `actions/checkout@v3` para clonar repo no workflow

---

## 📚 Recursos

- [Slides da Aula 06](../../aulas/aula06/slides.md)
- [Documentação oficial](#)
- [Exemplos práticos](#)

---

**Boa sorte! 🚀**

**Dúvidas?** Abra uma [issue](../../issues) com label `dúvida`
