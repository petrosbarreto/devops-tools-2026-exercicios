# Exercício Aula 20: Pods e Deployments

## 🎯 Objetivo

Deployment com 3 réplicas + rolling update

---

## 📋 Requisitos

- kubectl instalado
- minikube ou cluster K8s
- Helm 3 instalado
- 8GB RAM disponível

---

## 📝 Descrição do Exercício

### Contexto

Deploy de uma aplicação web no Kubernetes com alta disponibilidade (3 réplicas) e atualizações sem downtime.

### Tarefas

1. [ ] Criar manifests YAML (deployment, service)
2. [ ] Deploy no cluster (`kubectl apply`)
3. [ ] Verificar pods (`kubectl get pods`)
4. [ ] Testar acesso ao serviço
5. [ ] Documentar arquitetura

---

## 🚀 Como Entregar

1. **Fork** este repositório
2. **Clone** seu fork
3. Crie pasta `solucoes/seu-nome/aula20/`
4. Adicione seus arquivos:
   - `README.md` (documentação)
   - Código/configurações
   - Screenshots (se aplicável)
5. **Commit** e **Push**
6. Abra **Pull Request**: `[Aula 20] Seu Nome`

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

- ✅ Manifests YAML válidos
- ✅ Sintaxe Kubernetes correta
- ✅ Deployment com réplicas configuradas
- ✅ Service expondo aplicação

**Feedback automático em ~30 segundos após abrir PR!** 🚀

---

## 💡 Dicas

- Use `kubectl explain` para ver docs de recursos
- `kubectl get events` ajuda no debug
- Labels ajudam a organizar recursos

---

## 📚 Recursos

- [Slides da Aula 20](../../aulas/aula20/slides.md)
- [Documentação oficial](#)
- [Exemplos práticos](#)

---

**Boa sorte! 🚀**

**Dúvidas?** Abra uma [issue](../../issues) com label `dúvida`
