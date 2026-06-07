# 🏢 ImóPro — Portal Imobiliário Completo

Portal imobiliário profissional com **Firebase Firestore** em tempo real.

## 🌐 Links ao vivo

| Página | URL |
|--------|-----|
| 🏠 **Home** | [imopro-portal.vercel.app](https://imopro-portal.vercel.app) |
| 🏢 **Portal** | [imopro-portal.vercel.app/ImoPro_Portal.html](https://imopro-portal.vercel.app/ImoPro_Portal.html) |
| 🔐 **Login** | [imopro-portal.vercel.app/login.html](https://imopro-portal.vercel.app/login.html) |
| 🔬 **Diagnóstico Firebase** | [imopro-portal.vercel.app/firebase-check.html](https://imopro-portal.vercel.app/firebase-check.html) |

## 🔥 Firebase

- **Projeto:** imopro-portal
- **Banco:** Firestore (tempo real com onSnapshot)
- **Auth:** Google + Email/Senha
- **Coleções:** imoveis, leads, contratos, cobr, leads_loc, manutencao, regulacao, documentos

## 📦 Módulos do Sistema

### 🏠 Vendas & CRM
- **Dashboard** — métricas Firebase em tempo real
- **Imóveis** — CRUD completo, grid com filtros, upload de fotos
- **CRM Kanban** — funil 5 etapas (Novo → Fechado)
- **WhatsApp** — templates prontos + disparo para leads
- **Marketing & Banners** — gerador com templates + campanhas

### ⚖️ Operações
- **Regulação de Imóveis** — cadastro e acompanhamento de processos
- **Despachante Imobiliário** — fluxo completo compra/venda + calculadora ITBI
- **Documentos** — repositório centralizado de documentos

### 🏠 Gestão de Locação
- **Dashboard Locação** — métricas Firebase em tempo real
- **Contratos** — CRUD completo com CPF, índice reajuste, IPTU, condomínio
- **Cobranças** — emissão com cálculo automático de multa/juros/desconto
- **Split & Repasses** — configuração percentual por contrato
- **DIMOB** — declaração fiscal com dados do Firebase
- **Imposto de Renda** — simulador carnê-leão/DARF tabela 2026
- **Portal Locatário** — área do inquilino com chamados e boletos
- **Leads Locação** — análise de crédito automática
- **Manutenção** — chamados com prioridade e responsável

### 📊 Sistema
- **Relatórios** — totalizadores Firebase
- **Configurações** — dados da imobiliária + integrações

## ⚙️ Configuração Firebase

Para funcionar na Vercel, adicione o domínio em:
**Firebase Console → Authentication → Settings → Domínios autorizados**

Adicione: `imopro-portal.vercel.app`

Regras Firestore (desenvolvimento):
```
allow read, write: if true;
```

## 🛠️ Stack
- HTML5 + CSS3 + JavaScript ES Modules
- Firebase Firestore (onSnapshot - tempo real)
- Firebase Authentication (Google + Email/Senha)
- Tabler Icons
- Deploy: Vercel + GitHub Pages
