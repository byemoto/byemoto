# Евгений Власенко

Занимаюсь информационной безопасностью — в основном detection engineering и AppSec. Интересует связка между тем как атакуют и тем как это детектировать и предотвращать.

## Чем занимаюсь

**Detection Engineering** — пишу правила для SIEM систем (Sigma, MaxPatrol, R-Vision). Стараюсь идти от практики: разбираю реальные техники атак, смотрю какие артефакты остаются в логах, потом пишу правило. Часть материала беру с HTB машин.

**DevSecOps** — поднял стенд для практики: Gitea + Woodpecker CI + сканеры (Gitleaks, Semgrep, Trivy) + DefectDojo для управления находками. Подключил Anthropic API через n8n — Claude анализирует результаты сканирования и объясняет находки с примерами исправления.

**HackTheBox** — прохожу машины с упором на Blue Team: что оставляет след в логах, какие IOC можно вытащить, как это можно было задетектировать. Часть разборов конвертирую в detection rules.

## Репозитории

**[devsecops-stand](https://github.com/byemoto/devsecops-stand)** — DevSecOps стенд с CI/CD pipeline, SSO через Authentik и AI-анализом находок

**[soc-detection-rules](https://github.com/byemoto/soc-detection-rules)** — detection rules для Sigma, MaxPatrol и R-Vision на основе разбора атак

## Стек

```
SIEM:       MaxPatrol, R-Vision, Sigma
AppSec:     Semgrep, Gitleaks, Trivy, Burp Suite
DevOps:     Docker, Gitea, Woodpecker CI
Languages:  Python, Bash
```

## Контакты

Telegram: @evgeny_sec
