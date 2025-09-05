

# 📊 Sistema de Gestão Financeira - Apartamentos

📌 Este README também está disponível em outros idiomas:  

- [🇺🇸 Read in English](README.md)
  
Sistema web para controle financeiro de apartamentos de temporada da **Recife Flats Temporada Ltda**.

---

## 📋 Sobre o Projeto

Este sistema permite acompanhar receitas, despesas e situação do caixa de 4 apartamentos:
- **Apartamento 105** - Edifício Ipê (Boa Viagem) - 2 Quartos
- **Apartamento 203** - Edifício Ipê (Boa Viagem) - 1 Quarto  
- **Apartamento 804** - Edifício Forte São Pedro (Pina) - 2 Quartos
- **Apartamento 1006** - Edifício Golden View (Boa Viagem) - Flat com Piscina

---

## 🚀 Funcionalidades

- ✅ Relatórios mensais detalhados por apartamento  
- ✅ Controle de receitas  
- ✅ Gestão de despesas fixas (condomínio, energia, internet, IPTU)  
- ✅ Acompanhamento de despesas extras  
- ✅ Controle de pagamentos a prestadores de serviço  
- ✅ Resumo consolidado do caixa  
- ✅ Interface responsiva e moderna  

---

## 📁 Estrutura do Projeto

├── index.html              # Página principal com lista de apartamentos
├── style.css               # Estilos CSS do sistema
├── template.html           # Template base para preencher em qualquer apartamento/mês
├── 804-resumo.html         # Resumo completo do Apartamento 804
├── agosto-804.html         # Relatório detalhado Agosto 2025 - Apto 804
├── julho-804.html          # Relatório detalhado Julho 2025 - Apto 804
└── README.md               # Este arquivo

---

## 📝 Sobre o Template

O arquivo **`template.html`** foi criado para servir como **base**.  
Ele vem sem dados preenchidos, apenas com a estrutura de abas, tabelas e resumo do caixa.  

### Como usar o template:
1. Copie o `template.html`.  
2. Renomeie conforme o mês e apartamento desejados (ex: `setembro-105.html`).  
3. Edite:  
   - Cabeçalho (`<h1>` e `<h2>`) → coloque o nome do apartamento e o mês.  
   - Array `dados` no JavaScript → insira receitas e despesas.  

---

## 💻 Exemplo do Array `dados`

```javascript
const dados = [
  // Receitas
  { data: '05/08/2025', tipo: 'Receita', valor: 1200.00, descricao: 'Reserva Airbnb - João Silva' },

  // Despesas Fixas
  { data: '10/08/2025', tipo: 'Despesa', valor: 780.50, descricao: 'Condomínio', categoria: 'Fixa' },
  { data: '11/08/2025', tipo: 'Despesa', valor: 300.00, descricao: 'Energia', categoria: 'Fixa' },

  // Despesas Extras
  { data: '15/08/2025', tipo: 'Despesa', valor: 120.00, descricao: 'Mercado', categoria: 'Extra' },

  // Prestadores
  { data: '20/08/2025', tipo: 'Despesa', valor: 100.00, descricao: 'Adm Gabriela', categoria: 'Prestador' }
];


⸻

🌐 Como Usar

Opção 1: Abrir Localmente
	1.	Faça o download dos arquivos
	2.	Abra index.html em qualquer navegador
	3.	Navegue pelos apartamentos e relatórios mensais

Opção 2: GitHub Pages (Recomendado)

O sistema está hospedado gratuitamente no GitHub Pages:
https://SEUUSUARIO.github.io/NOMEREPOSITORIO

⸻

🔧 Tecnologias Utilizadas
	•	HTML5 – Estrutura das páginas
	•	CSS3 – Estilos e layout responsivo
	•	JavaScript Vanilla – Interatividade e cálculos
	•	Design Responsivo – Funciona em desktop e mobile

⸻

📊 Relatórios Disponíveis

Por Apartamento:
	•	Resumo completo com situação atual do caixa
	•	Relatórios mensais detalhados (Junho a Setembro 2025)

Categorias de Transações:
	•	Receitas: Pagamentos do Airbnb
	•	Despesas Fixas: Condomínio, energia, internet, IPTU, etc.
	•	Despesas Extras: Mercado, manutenção, uber, etc.
	•	Prestadores: Administração, contabilidade, limpeza, etc.

⸻

👥 Como Colaborar

Para Desenvolvedores:
	1.	Faça um fork do repositório
	2.	Clone localmente:

git clone https://github.com/USUARIO/REPO.git


	3.	Crie uma branch:

git checkout -b nova-funcionalidade


	4.	Faça suas alterações
	5.	Commit:

git commit -m "Descrição das mudanças"


	6.	Push:

git push origin nova-funcionalidade


	7.	Abra um Pull Request

Para Colaboradores Diretos:
	1.	Clone o repositório
	2.	Faça as alterações necessárias
	3.	Commit e push diretamente na branch main

⸻

📝 Padrões de Commit

Use mensagens descritivas:
	•	Adiciona relatório setembro 804
	•	Corrige cálculo de despesas fixas
	•	Atualiza design da página principal
	•	Adiciona novo apartamento 105

⸻

🔄 Atualizações Frequentes

O sistema é atualizado mensalmente com:
	•	Novos relatórios financeiros
	•	Receitas do Airbnb
	•	Despesas do período
	•	Situação atual dos caixas

⸻

📞 Suporte

Para dúvidas ou problemas:
	•	Abra uma Issue neste repositório
	•	Contate a administração: Recife Flats Temporada Ltda

⸻

📄 Licença

Uso interno da empresa. Não distribuir sem autorização.

⸻

Última atualização: Setembro 2025
Versão: 1.0
Responsável: Sistema de Gestão Financeira

👩‍💻 Autora: Vanessa Rafaella

---

👉 No teu `README.md` (em inglês), logo no início você pode colocar:  

```markdown
📌 This README is available in other languages:  
- [🇧🇷 Leia em Português](README-pt.md)

Quer que eu já monte esse trechinho inicial pronto para colar no README.md principal em inglês?
