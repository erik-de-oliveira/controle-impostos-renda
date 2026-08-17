# Controle de Dados para Declaração de Imposto de Renda

## Descrição
Esta planilha foi desenvolvida para facilitar a organização de informações necessárias para a declaração de imposto de renda. Ela oferece validações de dados, navegação intuitiva e funções interativas para gestão eficiente de dados fiscais.

## Objetivos
- Centralizar informações de rendimentos para declaração de imposto de renda
- Validar dados de entrada para evitar erros comuns
- Facilitar a navegação entre diferentes tipos de renda
- Calcular automaticamente totais e métricas relevantes

## Estrutura da Planilha

| Aba | Função |
|-----|--------|
| **Dashboard** | Visão geral das principais métricas (totais, contagens, gráficos) |
| **Dados_Principais** | Tabela principal com todos os registros de renda |
| **Filtros** | Controles deslizantes e dropdowns para filtrar por ano, tipo de renda, etc. |
| **Configurações** | Configurações gerais do sistema (cores, unidades, etc.) |

## Funcionalidades Principais

### Validações de Dados
- Campo "Tipo de Renda" com lista de validação (Salário, Investimento, Freelance, Aluguel, etc.)
- Campo "Status" com opções (Pendente, Aprovado, Rejeitado, Concluído)
- Validação de data (ano entre 2020-2026)
- Verificação de valores numéricos positivos

### Navegação Facilitada
- Filtros por ano fiscal
- Filtros por tipo de renda
- Busca por nome ou empresa
- Paginador para grandes volumes de dados

### Funções Interativas
- Cálculo automático de total de rendimentos por ano
- Soma de impostos calculada automaticamente
- Gráficos de distribuição por categoria
- Exportação para CSV

## Como Usar

1. Abra o arquivo `INDECTRAN_SAUDAS.xlsx`
2. Preencha os dados na aba **Dados_Principais**
3. Utilize os filtros na aba **Filtros** para organizar os dados
4. Consulte o **Dashboard** para visualizações rápidas

## Requisitos

- Microsoft Excel 2016 ou superior
- Nenhuma dependência externa

## Licença

MIT License - Livre uso comercial e pessoal.
