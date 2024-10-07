# Análise Preditiva de Ações

Este projeto é uma aplicação web que permite visualizar dados históricos e prever o comportamento de ações na Bolsa de Valores utilizando o **Streamlit** e o modelo preditivo **Prophet**.

## Funcionalidades

- Seleção de ações de grandes empresas brasileiras e internacionais.
- Visualização de dados históricos de ações.
- Previsão de preços de ações para os próximos meses usando o modelo Prophet.
- Interface simples e intuitiva usando **Streamlit**.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **Streamlit**: Framework para criar interfaces web interativas.
- **yFinance**: Biblioteca para extrair dados financeiros.
- **Prophet**: Biblioteca para previsão de séries temporais.
- **Plotly**: Usada para visualização gráfica dos dados.

## Como Executar o Projeto

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```

2. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

3. Execute a aplicação:
    ```bash
    streamlit run app.py
    ```

## Estrutura do Projeto
📂 projeto-preditivo-acoes  
│  
├── app.py                   # Código principal da aplicação Streamlit  
├── requirements.txt          # Bibliotecas necessárias para rodar a aplicação  
└── README.md                 # Instruções e documentação do projeto  

## Como Usar a Aplicação

1. Ao abrir a aplicação, você pode selecionar a ação de interesse no menu lateral.
2. Escolha a **data inicial** e a **data final** para obter os dados históricos da ação.
3. Defina o número de meses para previsão futura (1 a 24 meses).
4. A aplicação exibirá os dados históricos da ação e a previsão de preço para o período selecionado.

## Ações Disponíveis

A aplicação oferece suporte às seguintes ações:

- Petrobras (PETR4.SA)
- Ambev (ABEV3.SA)
- Magazine Luiza (MGLU3.SA)
- Banco do Brasil (BBAS3.SA)
- Google (GOOG)
- Apple (APPL)
- Microsoft (MSFT)
