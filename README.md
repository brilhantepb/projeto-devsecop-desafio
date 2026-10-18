# Desafio DevSecOps — Gerenciador de Tarefas

## Sobre o Projeto
Este repositório faz parte do desafio prático do módulo de DevSecOps da ADA Tech.
Você receberá este projeto com vulnerabilidades propositais e uma pipeline incompleta.
Seu objetivo é **implementar a pipeline de segurança** e **corrigir as vulnerabilidades**.

## Estado atual
A pipeline está **incompleta**. Os steps de segurança precisam ser implementados por você.

## Sua missão
1. Implementar os steps de segurança no `pipeline.yml`
2. Fazer a pipeline **quebrar** ao detectar os problemas
3. Corrigir as vulnerabilidades encontradas
4. Fazer a pipeline **passar** com tudo verde ✅
5. Documentar o funcionamento da pipeline neste README

## O que implementar
- [ ] Secrets Scanning com **Gitleaks**
- [ ] SAST com **Semgrep**
- [ ] SCA com **Grype**
- [ ] Assinatura do artefato com cosign
- [ ] Deploy com **GitHub Pages**

## Como a pipeline funciona
**Gitleaks (Secrets Scanning):** Varre o código-fonte em busca de chaves de API, senhas ou tokens expostos acidentalmente, garantindo que credenciais sensíveis não cheguem ao repositório

**Semgrep (SAST):** Realiza análise estática do código para detectar vulnerabilidades de segurança e más práticas (como o uso de `eval()` e `innerHTML` sem sanitização)

**Grype (SCA):** Analisa as dependências declaradas no projeto em busca de vulnerabilidades conhecidas (CVEs) em bibliotecas de terceiros

## URL de Produção
https://brilhantepb.github.io/projeto-devsecop-desafio/

