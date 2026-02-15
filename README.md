# 🤖 Exercícios Automatizados - DevOps Tools 2026.1

**Professor:** Petros Barreto  
**Disciplina:** DevOps Tools (SI 5º)  
**Instituição:** UNINASSAU Recife

---

## 🎯 Como Funciona

Este repositório usa **GitHub Actions** para validar automaticamente seus exercícios!

### 📖 Guias Completos

- **[🎓 Guia Passo a Passo](GUIA-PASSO-A-PASSO.md)** - Tutorial detalhado para iniciantes
- **[⚡ Guia Rápido](GUIA-RAPIDO.md)** - Resumo de 5 minutos

### Para Alunos

1. **Fork** este repositório
2. **Clone** seu fork para sua máquina
3. Resolva os exercícios na pasta correspondente
4. **Commit** suas alterações
5. **Push** para seu fork
6. Abra um **Pull Request** com título: `[Aula XX] Seu Nome`
7. Aguarde o **bot validar** automaticamente
8. Veja o **feedback** nos comentários do PR
9. Corrija se necessário e faça novo push
10. Quando aprovado, o professor fará o merge

**💡 Dúvidas?** [Abrir Issue](https://github.com/petrosbarreto/devops-tools-2026-exercicios/issues/new/choose)

---

## 📂 Estrutura

```
devops-tools-2026-exercicios/
├── .github/
│   └── workflows/          # GitHub Actions
│       ├── aula01.yml
│       ├── aula02.yml
│       └── ...
├── exercicios/
│   ├── aula01/
│   │   └── README.md       # Instruções do exercício
│   ├── aula02/
│   └── ...
├── leaderboard.html        # Ranking da turma
├── GUIA-PASSO-A-PASSO.md   # Tutorial completo
└── README.md
```

---

## 🏆 Leaderboard

**Ver Ranking:** [https://petrosbarreto.github.io/devops-tools-2026-exercicios/leaderboard.html](https://petrosbarreto.github.io/devops-tools-2026-exercicios/leaderboard.html)

Atualiza automaticamente a cada semana (segunda-feira 00:00 UTC).

---

## 📊 Sistema de Pontuação

Cada exercício vale **0-100 pontos**:

| Critério | Pontos |
|----------|--------|
| **Funcionalidade** | 40 |
| **Boas Práticas** | 30 |
| **Documentação** | 20 |
| **Criatividade** | 10 |
| **TOTAL** | **100** |

**Nota mínima para aprovar:** 70/100

---

## 🎯 Exercícios por Unidade

### UNIDADE I - DevOps Fundamentos (8 exercícios)
01. Introdução ao DevOps - Cultura e Conceitos
02. DevOps + Ágil - Integração de Metodologias
03. Git Branching Strategy - Implementar Git Flow
04. GitHub Actions - Criar Workflow CI
05. CI Pipeline - Build e Testes Automáticos
06. CD Pipeline - Deploy Automático
07. Blue-Green Deployment - Estratégia Zero Downtime
08. Jenkins Pipeline - Alternativa ao GitHub Actions

### UNIDADE II - Containers (10 exercícios)
09. Comparação VMs vs Containers
10. Docker Hello World - Primeiro Container
11. Dockerfile - Criar Imagem Customizada
12. Docker Compose - App Multi-container
13. Docker Networks - Comunicação entre Containers
14. Docker Volumes - Persistência de Dados
15. Container Registry - Publicar Imagem
16. Docker Security - Scan e Hardening
17. Multi-stage Build - Otimização de Imagem
18. Projeto Full Stack - Frontend + Backend + DB

### UNIDADE III - Kubernetes (10 exercícios)
19. Minikube Setup - Cluster Local
20. Pods e Services - Deploy Básico
21. ConfigMaps e Secrets - Configuração
22. Ingress Controller - Roteamento HTTP
23. Persistent Volumes - Storage no K8s
24. HPA - Horizontal Pod Autoscaler
25. Helm Chart - Package da Aplicação
26. Multi-Environment - Dev/Staging/Prod
27. Health Checks - Liveness e Readiness
28. Projeto K8s Completo - App Production-Ready

### UNIDADE IV - Observabilidade (8 exercícios)
29. Three Pillars - Logs, Metrics, Traces
30. Elasticsearch - Índices e Queries
31. Logstash - Pipeline de Processamento
32. Beats - Coleta de Logs e Métricas
33. Kibana Dashboard - Visualização de Dados
34. APM - Application Performance Monitoring
35. Alertas - Configurar Watchers
36. Projeto Final - Stack Completa (App + K8s + ELK)

---

## 🤖 Bot de Validação

O bot valida automaticamente:

✅ Arquivos necessários presentes  
✅ Sintaxe correta (YAML, Dockerfile, etc)  
✅ Boas práticas seguidas  
✅ Documentação adequada  
✅ Código funcional  

Feedback em ~30 segundos após abrir o PR!

---

## 🆘 Precisa de Ajuda?

- **Dúvida sobre exercício:** [Abrir Issue](https://github.com/petrosbarreto/devops-tools-2026-exercicios/issues/new/choose)
- **Bug no sistema:** [Reportar](https://github.com/petrosbarreto/devops-tools-2026-exercicios/issues/new/choose)
- **Guia completo:** [GUIA-PASSO-A-PASSO.md](GUIA-PASSO-A-PASSO.md)

---

## 📚 Recursos

- **Slides:** [devops-tools-2026](https://github.com/petrosbarreto/devops-tools-2026)
- **Docker Docs:** [docs.docker.com](https://docs.docker.com)
- **Kubernetes Docs:** [kubernetes.io](https://kubernetes.io/docs)
- **Elastic Docs:** [elastic.co/guide](https://www.elastic.co/guide/)

---

**Bom semestre e bom código! 🚀**
