# Exercício Aula 30: Elasticsearch - Fundamentos

## 🎯 Objetivo

Queries avançadas com agregações

---

## 📋 Requisitos

- Docker e Docker Compose
- 8GB RAM disponível
- Porta 9200, 5601 livres

---

## 📝 Descrição do Exercício

### Contexto

Indexe logs de aplicação no Elasticsearch para permitir buscas rápidas e análises de problemas.

### Tarefas

1. [ ] Configurar stack ELK (docker-compose)
2. [ ] Indexar dados de teste
3. [ ] Criar queries no Kibana
4. [ ] Construir dashboard
5. [ ] Exportar configurações

---

## 🚀 Como Entregar

1. **Fork** este repositório
2. **Clone** seu fork
3. Crie pasta `solucoes/seu-nome/aula30/`
4. Adicione seus arquivos:
   - `README.md` (documentação)
   - Código/configurações
   - Screenshots (se aplicável)
5. **Commit** e **Push**
6. Abra **Pull Request**: `[Aula 30] Seu Nome`

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

- ✅ `docker-compose.yml` válido
- ✅ Stack ELK completa
- ✅ Dashboard exportado (JSON)
- ✅ Queries documentadas

**Feedback automático em ~30 segundos após abrir PR!** 🚀

---

## 💡 Dicas

- ELK Stack precisa de bastante RAM (8GB recomendado)
- Use Kibana Discover para explorar dados antes de criar dashboard
- Grok Debugger ajuda a criar patterns

---

## 📚 Recursos

- [Slides da Aula 30](../../aulas/aula30/slides.md)
- [Documentação oficial](#)
- [Exemplos práticos](#)

---

**Boa sorte! 🚀**

**Dúvidas?** Abra uma [issue](../../issues) com label `dúvida`
