<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0D1117,1a1a2e,16213e&height=200&section=header&text=TeraNex%20Tecnologia&fontSize=42&fontColor=58a6ff&fontAlignY=38&desc=Infraestrutura%20que%20funciona.%20Suporte%20que%20resolve.&descAlignY=58&descSize=16&descColor=8b949e" width="100%"/>

[![Website](https://img.shields.io/badge/teranex.inf.br-0D1117?style=flat-square&logo=google-chrome&logoColor=58a6ff&label=site)](https://teranex.inf.br)
[![LinkedIn](https://img.shields.io/badge/TeraNex-0D1117?style=flat-square&logo=linkedin&logoColor=58a6ff&label=linkedin)](https://linkedin.com/company/teranex)
[![Email](https://img.shields.io/badge/contato%40teranex.inf.br-0D1117?style=flat-square&logo=gmail&logoColor=58a6ff&label=email)](mailto:contato@teranex.inf.br)
![Localização](https://img.shields.io/badge/Maceió%2C%20Alagoas-0D1117?style=flat-square&logo=googlemaps&logoColor=58a6ff)

</div>

---

## 🏢 Sobre

A **TeraNex Tecnologia** é uma empresa especializada em **Soluções de Tecnologia da Informação**, com atuação focada em infraestrutura, automação, sistemas corporativos e suporte técnico especializado.

Nosso objetivo é projetar e manter ambientes **seguros, organizados, eficientes e escaláveis**, alinhados às necessidades operacionais e estratégicas de cada cliente — desde pequenas empresas até instituições de ensino e setor público.

---

## 🎯 Missão

Oferecer soluções de TI **confiáveis, bem estruturadas e alinhadas às boas práticas do mercado**, auxiliando organizações na otimização de processos, segurança da informação e continuidade operacional.

Atuamos na interseção entre **suporte técnico especializado**, **administração de servidores** e **desenvolvimento de automações**, promovendo ambientes mais estáveis e produtivos.

---

## 🛠️ Stack & Especialidades

**Infraestrutura & Virtualização**

![Proxmox](https://img.shields.io/badge/Proxmox_VE-E57000?style=flat-square&logo=proxmox&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=flat-square&logo=vmware&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white)

**Redes & Segurança**

![pfSense](https://img.shields.io/badge/pfSense-212121?style=flat-square&logo=pfsense&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![UniFi](https://img.shields.io/badge/UniFi-0559C9?style=flat-square&logo=ubiquiti&logoColor=white)

**Serviços & Identidade**

![Samba4 AD](https://img.shields.io/badge/Samba4_AD-CC0000?style=flat-square&logo=samba&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D6?style=flat-square&logo=microsoft&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Monitoramento & Observabilidade**

![Zabbix](https://img.shields.io/badge/Zabbix-CC0000?style=flat-square)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB_2.x-22ADF6?style=flat-square&logo=influxdb&logoColor=white)

**Automação & Desenvolvimento**

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

---

## 🧭 Nossos Pilares

| Pilar | Descrição |
| :--- | :--- |
| 🔧 **Infraestrutura** | Gestão de servidores, virtualização (Proxmox/VMware), redes LAN/WLAN e serviços em nuvem |
| 🖥️ **Suporte Técnico** | Manutenção preventiva e corretiva, hardware, troubleshooting avançado e suporte a usuários |
| ⚙️ **Automação** | Scripts e ferramentas para deployment, padronização e manutenção de ambientes |
| 📊 **Monitoramento** | Stacks Zabbix + Grafana + InfluxDB para visibilidade total do ambiente |
| 🔐 **Segurança** | Active Directory, controle de acesso, GPOs, proteção de dados e hardening |
| 🌐 **Desenvolvimento** | Sistemas internos, aplicações web e integrações personalizadas |

---

## 📦 Organização dos Repositórios

Os repositórios seguem nomenclatura por prefixo para facilitar navegação e automação:

| Prefixo | Categoria |
| :--- | :--- |
| `infra-` | Infraestrutura, redes e virtualização |
| `monitoring-` | Stacks e dashboards de monitoramento |
| `net-` | Configurações de rede (pfSense, UniFi) |
| `ad-` / `samba-` | Active Directory, GPOs e autenticação |
| `docker-` | Compose stacks e imagens de containers |
| `scripts-` | Automações PowerShell, Bash e Python |
| `docs-` | Documentação institucional e runbooks |
| `cliente-` | Projetos específicos de clientes (privados) |

---

## 🔐 Segurança e Boas Práticas

- 2FA obrigatório para todos os membros
- Controle de acesso baseado em teams e permissões por repositório
- Repositórios sensíveis configurados como privados
- Secrets e variáveis de ambiente nunca versionados
- Branch protection ativa na `main` — alterações exclusivamente via Pull Request

---

## 🔁 Fluxo de Desenvolvimento

```
main        → Produção (protegida, somente via PR)
develop     → Homologação / testes integrados
feature/*   → Novas funcionalidades
fix/*       → Correções de bugs
hotfix/*    → Correções emergenciais de produção
docs/*      → Atualizações de documentação
```

---

## 📌 Padrão de Commits

```
feat:     nova funcionalidade
fix:      correção de bug
docs:     atualização de documentação
chore:    manutenção e configuração
refactor: refatoração sem mudança de comportamento
ci:       pipelines e automação de CI/CD
```

---

## 📄 Licenciamento

Os projetos da organização podem ser:

- 🔒 **Privados** — uso interno ou projetos de clientes
- 🌍 **Públicos** — templates, ferramentas e scripts open source

Cada repositório possui sua licença definida individualmente.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0D1117,1a1a2e,16213e&height=100&section=footer" width="100%"/>

<sub>© 2026 TeraNex Tecnologia · Maceió, Alagoas · Todos os direitos reservados.</sub>

</div>
