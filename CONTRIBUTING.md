# Contribuindo com projetos TeraNex

## Pré-requisitos

- Acesso à organização GitHub `teranex`
- 2FA habilitado na conta GitHub
- Familiaridade com o fluxo de branches e padrão de commits abaixo

## Fluxo de branches

```
main        → Produção (protegida, somente via Pull Request)
develop     → Homologação / testes integrados
feature/*   → Novas funcionalidades
fix/*       → Correções de bugs
hotfix/*    → Correções emergenciais de produção
docs/*      → Atualizações de documentação
```

Exemplos de nomes de branch:
```
feature/monitoramento-disk-alert
fix/zabbix-agent-timeout
hotfix/ad-sync-falha-prod
docs/runbook-pfsense-backup
```

## Padrão de commits

```
feat:     nova funcionalidade
fix:      correção de bug
docs:     atualização de documentação
chore:    manutenção e configuração
refactor: refatoração sem mudança de comportamento
ci:       pipelines e automação de CI/CD
```

Formato completo:
```
<tipo>(<escopo opcional>): <descrição curta>

<corpo opcional — explica o porquê, não o quê>

Closes #<número da issue>
```

Exemplo:
```
fix(zabbix): corrigir timeout do agente em hosts Windows

O valor padrão de 3s causava falsos alertas em servidores com carga elevada.
Ajustado para 10s conforme recomendação do fabricante.

Closes #42
```

## Abrindo um Pull Request

1. Crie uma branch a partir de `develop` (ou `main` para hotfixes)
2. Faça commits atômicos e descritivos
3. Abra o PR apontando para `develop` (ou `main` para hotfixes)
4. Preencha o template de PR completamente
5. Aguarde revisão de pelo menos um membro da equipe
6. Não faça merge sem aprovação

## Revisão de código

- PRs para `main` requerem aprovação obrigatória
- Comentários de revisão devem ser resolvidos antes do merge
- Use "Request changes" para bloqueios, "Comment" para sugestões não-bloqueantes

## Secrets e segurança

- Nunca versione credenciais, tokens ou chaves
- Use GitHub Secrets para variáveis sensíveis em workflows
- Em caso de commit acidentual com credencial: revogue imediatamente e notifique a equipe

## Dúvidas

Abra uma [issue de suporte](../../issues/new?template=suporte.yml) ou entre em contato pelo e-mail contato@teranex.inf.br.
