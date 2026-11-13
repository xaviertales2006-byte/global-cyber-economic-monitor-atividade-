# Global Cyber & Economic Real-Time Monitor 🛡️📊

Painel de observabilidade multi-setorial em tempo real integrado com Threat Intelligence OSINT (SANS ISC / DShield e Abuse.ch).

## 👥 Alunos da Dupla
- **Lincoln Figueiredo da silva**
- **Tales Silva Xavier**

## 🧪 Técnicas de Testes Aplicadas
- Testes unitários com **Vitest** cobrindo o rate limiting (**Token Bucket**) e sanitização contra **XSS** (`sanitizeString`).
- Validação de resiliência com **Circuit Breaker** para quedas de APIs OSINT.

## 🚀 Melhorias Implementadas (Clean Code & Segurança)
- **Blindagem Anti-XSS & DDoS:** Sanitização rigorosa de entradas externas e limitação de rajadas de tráfego na borda.
- **Refatoração:** Organização de classes de segurança utilitárias em módulos dedicados (`src/utils/`).
- **Auditoria:** Execução de `npm audit` para validação de dependências seguras.