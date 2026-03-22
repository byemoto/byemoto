# Евгений Власенко

Информационная безопасность — AppSec, DevSecOps, detection engineering. Связка между тем как атакуют и тем как это детектировать и предотвращать.

## Чем занимаюсь

**DevSecOps** — выстроил стенд на VPS: 23 контейнера, CI/CD pipeline с SAST/DAST/SCA сканированием, vulnerability management, WAF, IPS, SSO, runtime security и AI-анализом результатов через Claude API. Покрытие OWASP Top 10: 6/10 covered, 4/10 partial, 0 gaps.

**Detection Engineering** — пробую писать правила для SIEM систем (Sigma, MaxPatrol, R-Vision). Разбираю реальные техники атак, анализирую артефакты в логах, конвертирую в detection rules. Часть материала с HTB машин.

**HackTheBox** — прохожу машины с упором на Blue Team: какие следы остаются в логах, какие IOC можно вытащить, как задетектировать. Разборы конвертирую в detection rules.

## Репозитории

**[devsecops-stand](https://github.com/byemoto/devsecops-stand)** — DevSecOps стенд: Caddy + Coraza WAF + CrowdSec + Gitea + Woodpecker CI + Semgrep + ZAP + Trivy + Gitleaks + DefectDojo + n8n + Claude AI + Authentik SSO + Grafana + Prometheus + Loki + Falco

**[soc-detection-rules](https://github.com/byemoto/soc-detection-rules)** — detection rules для Sigma, MaxPatrol и R-Vision на основе разбора атак

## Стек
```
Security:   Semgrep, OWASP ZAP, Gitleaks, Trivy, Burp Suite, Coraza WAF, CrowdSec, Falco
SIEM:       MaxPatrol, R-Vision, Sigma
DevOps:     Docker, Caddy, Gitea, Woodpecker CI, n8n, Grafana, Prometheus, Loki
Management: DefectDojo, Authentik (SSO)
Languages:  Python, Bash
```

## Контакты

Telegram: @evgeny_ober
