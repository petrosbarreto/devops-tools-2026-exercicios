# Exercício Aula 15: Container Registries

## 🎯 Objetivo

Pipeline CI que publica imagem automaticamente

---

## 📋 Requisitos

- Docker instalado (v20.10+)
- Docker Compose (v2.0+)
- 4GB RAM disponível

---

## 📝 Descrição do Exercício

### Contexto

Aplique os conceitos de **Container Registries** em um cenário prático do dia a dia de um profissional DevOps.

### Tarefas

1. [ ] Criar `Dockerfile` otimizado
2. [ ] Construir imagem (`docker build`)
3. [ ] Rodar container (`docker run`)
4. [ ] Publicar no Docker Hub
5. [ ] Documentar comandos usados

---

## 🚀 Como Entregar

1. **Fork** este repositório
2. **Clone** seu fork
3. Crie pasta `solucoes/seu-nome/aula15/`
4. Adicione seus arquivos:
   - `README.md` (documentação)
   - Código/configurações
   - Screenshots (se aplicável)
5. **Commit** e **Push**
6. Abra **Pull Request**: `[Aula 15] Seu Nome`

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

- ✅ `Dockerfile` presente e válido
- ✅ Imagem constrói sem erros
- ✅ Tamanho da imagem razoável (<500MB)
- ✅ Documentação de comandos

**Feedback automático em ~30 segundos após abrir PR!** 🚀

---

## 💡 Dicas

- Use imagens base pequenas (alpine, distroless)
- `.dockerignore` reduz tamanho da imagem
- Multi-stage builds otimizam drasticamente

---

## 📚 Recursos

- [Slides da Aula 15](../../aulas/aula15/slides.md)
- [Documentação oficial](#)
- [Exemplos práticos](#)

---

**Boa sorte! 🚀**

**Dúvidas?** Abra uma [issue](../../issues) com label `dúvida`
