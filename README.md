# Protótipo: Detecção de Anomalias em Logs de Autenticação

**Disciplina:** Segurança com Big Data e IA  
**Projeto:** Arquitetura de Segurança Cibernética Inteligente  
**Programa:** Segurança com Big Data e IA
**Autores:** Paulo Victor Aragão dos Santos, Renato Lacerda do Couto e Rodrigo Barbosa Pithon

---

## 🎯 Objetivo

Este protótipo demonstra na prática o uso do algoritmo **Isolation Forest** para detectar comportamentos anômalos em logs de autenticação, especialmente tentativas de login fora do horário comercial, com alto número de falhas e origem de IP externo — cenário típico de ataques a APIs em instituições financeiras.

---

## 📁 Estrutura do Protótipo

- `deteccao_anomalias.py` → Script principal de detecção de anomalias
- `dados_sinteticos.csv` → Dataset sintético gerado (5.000 registros)
- `anomalias_visualizacao.png` → Gráfico gerado automaticamente
- `docker-compose-minimal.yml` → Ambiente ELK mínimo para testes
- `README.md` → Este documento

---

## 🚀 Como Executar

### Pré-requisitos

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
