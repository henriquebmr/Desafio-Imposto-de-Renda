# 📊 Agregador e Controlador para Declaração do Imposto de Renda (IRPF)

Projeto desenvolvido para o desafio prático de Excel da **DIO (Digital Innovation One)**.

## 📄 Descrição do Projeto

Esta ferramenta foi construída em Microsoft Excel para centralizar, organizar e validar as informações essenciais necessárias para a **Declaração de Ajuste Anual do Imposto de Renda**. A planilha conta com layout profissional, navegação simplificada e recursos visuais otimizados para uso no **Excel Online (Web)** e **Excel Desktop**.

---

## 📂 Estrutura do Arquivo (`.xlsx`)

1. **`Dashboard`**: Painel principal com cartões de indicadores (Totais de Rendimentos, Deduções e IRRF Retido), resumos consolidados por categoria via fórmulas automatizadas (`SOMASE`) e controle de evolução patrimonial.
2. **`Rendimentos`**: Tabela detalhada para cadastro de fontes pagadoras, valores brutos, retenção na fonte e status dos comprovantes.
3. **`Deducoes`**: Lançamento organizado de despesas dedutíveis (Saúde, Educação, Dependentes, PGBL, Pensão Alimentícia).
4. **`Bens_e_Direitos`**: Acompanhamento do patrimônio com posição histórica e atual.
5. **`Categorias_Apoio`**: Aba técnica de dados que alimenta os menus suspensos de validação de dados nas demais tabelas.

---

## 🛠️ Funcionalidades e Fórmulas Utilizadas

* **Validação de Dados**: Menus suspensos automatizados em todas as tabelas para preenchimento ágil e sem erros.
* **`SOMASE` / `SUMIF`**: Consolidação automática no Dashboard com base no tipo de rendimento e despesa.
* **`SOMA` / `SUM`**: Totais consolidados de patrimônio, impostos e receitas.
* **Formatação Condicional**: Destaques visuais e padronização monetária brasileira (`R$`).

---

## 🚀 Como Executar no Excel Online

1. Faça upload do arquivo `.xlsx` para o seu **OneDrive**.
2. Abra o arquivo no **Excel Web**.
3. Preencha os dados nas abas de entrada (`Rendimentos`, `Deducoes`, `Bens_e_Direitos`) e acompanhe o resultado consolidado na aba `Dashboard`.

---

## 👤 Autor

Desenvolvido por **Henrique** para o desafio prático da plataforma **DIO**.
