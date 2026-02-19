<p align="center">
  <img src="https://img.shields.io/badge/AI-Skills%20Collection-8B5CF6?style=for-the-badge&logo=sparkles&logoColor=white" alt="AI Skills Collection"/>
</p>

<h1 align="center">🧠 AI Skills Collection</h1>

<p align="center">
  <strong>Coleção curada de skills de IA para potencializar agentes e assistentes de código.</strong>
  <br/>
  <em>Cada skill é um módulo autocontido com instruções, recursos e playbooks prontos para uso.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Skills-3-blueviolet?style=flat-square" alt="Total Skills"/>
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square" alt="Status"/>
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License"/>
</p>

---

## 📦 Skills Disponíveis

| Skill | Descrição | Resources |
|-------|-----------|-----------|
| 🔗 [**api-documentation-master**](./api-documentation-master/) | Geração completa de documentação de APIs — OpenAPI specs, validação, templates e boas práticas de segurança | `SKILL.md` · `scripts/` |
| 📄 [**documentation-master**](./documentation-master/) | Skill mestre de documentação técnica — gera API docs, arquitetura, READMEs, explica código com diagramas visuais, templates e automação CI/CD | `SKILL.md` · `resources/` (4 playbooks) |
| 📊 [**mermaid-expert**](./mermaid-expert/) | Especialista em diagramas Mermaid — flowcharts, sequência, ERD, estados, Gantt e arquitetura com styling profissional | `SKILL.md` |

---

## 🏗️ Estrutura

```
Skills/
├── api-documentation-master/
│   ├── SKILL.md                          # Instruções principais
│   └── scripts/
│       └── api_validator.py              # Script de validação de APIs
│
├── documentation-master/
│   ├── SKILL.md                          # Skill mestre unificada
│   └── resources/
│       ├── doc-generation-playbook.md    # Geração automatizada de docs
│       ├── code-explanation-playbook.md  # Análise e explicação de código
│       ├── documentation-templates.md   # Templates (README, ADR, Changelog)
│       └── mermaid-diagrams-guide.md    # Guia de diagramas Mermaid
│
├── mermaid-expert/
│   └── SKILL.md                          # Diagramas Mermaid
│
└── README.md
```

---

## 🚀 Como Usar

Cada skill é **autocontida** — basta apontar seu agente de IA para a pasta da skill desejada.

### Com Antigravity / Gemini
```
Leia a skill em ./documentation-master/SKILL.md e aplique ao meu projeto
```

### Manualmente
1. Abra o `SKILL.md` da skill desejada
2. Use como prompt de sistema ou contexto para seu agente
3. Consulte a pasta `resources/` para playbooks e exemplos detalhados

---

## 🧩 Criando Novas Skills

Cada skill segue o formato padrão:

```yaml
---
name: nome-da-skill
description: "Descrição curta do que a skill faz"
---

# Título da Skill

## Use esta skill quando
## Não use esta skill quando
## Instruções
## Resources
```

> **Dica:** Use a skill `documentation-master` para documentar suas próprias skills! 🔄

---

## 📝 Licença

MIT © [ferfoster](https://github.com/ferfoster)
