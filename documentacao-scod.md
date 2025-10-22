
# 🧭 Documentação SCOD

## 📘 Visão Geral
A **SCOD** é uma plataforma SaaS especializada em **monitoramento automatizado de tributos e documentos imobiliários**, como:
- IPTU
- Certidões negativas
- Dívidas ativas
- Contas de consumo
- Taxas diversas (como Marinha, Bombeiro, Foro etc.)

A solução centraliza dados públicos e privados, garantindo que construtoras, incorporadoras, bancos e empresas de diferentes segmentos possam **acompanhar vencimentos, emitir relatórios e evitar multas** por atrasos.

---

## 🏗 Estrutura da Plataforma
A plataforma SCOD é composta pelos seguintes módulos principais:

### 1. **Admin**
Área interna destinada ao gerenciamento de dados, incluindo:
- Cadastro e edição de imóveis
- Administração de certidões
- Configuração de grupos e subgrupos
- Relatórios de integração

### 2. **Módulo de Certidões**
Permite acompanhar e baixar certidões de dois tipos:
- **Certidões Negativas:** com filtros de cidade, estado, grupo, subgrupo e validade.
- **Certidões de Antecedentes:** com filtros de cidade, estado, grupo, subgrupo, órgão responsável, período e situação (com antecedentes / sem antecedentes).

Cada relatório inclui:
- Exportação em Excel
- Mini dashboard com métricas (quantidade por cidade, estado e situação)
- Filtros avançados e pesquisa unificada

### 3. **Módulo de IPTU**
Gerencia tributos municipais, permitindo:
- Visualizar débitos e status de pagamento
- Atualização mensal automatizada via integração
- Download de boletos filtrados por mês
- Edição de nomes e dados dos imóveis (mantendo opção de priorizar dados próprios ou os da prefeitura)

### 4. **Contas de Consumo**
Monitora contas de energia, água e gás, oferecendo:
- Histórico de consumo
- Alertas de vencimento
- Opção de centralização por grupo

---

## ⚙️ Processos Internos

### 🧩 Atualização de Dados
A SCOD realiza **atualizações automáticas mensais** para garantir que as informações públicas estejam sempre sincronizadas com as prefeituras e órgãos emissores.

### 🧠 Integrações
A SCOD permite integrações via API e módulos específicos, como:
- **Integração MEGA (Trisul)**
- **Importação em massa de imóveis e tributos**
- **Histórico de logs com sucesso/erro por envio**

---

## 🧰 Boas Práticas de Documentação (para POs e Devs)

### Estrutura Recomendada
1. **Título** → Nome do módulo ou funcionalidade  
2. **Descrição** → Explicação breve do objetivo  
3. **Fluxo do Usuário** → Etapas principais ou telas envolvidas  
4. **Campos e Dados** → Lista de campos e validações  
5. **Regras de Negócio** → Detalhes sobre como o sistema deve reagir  
6. **Exceções e Erros** → O que ocorre em caso de falha  
7. **Integrações** → Se consome ou envia dados externos  
8. **Referências Visuais** → Print, mockup ou link para Figma  
