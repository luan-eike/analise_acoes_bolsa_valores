# Analise de ações na B3
Criei este script em Python para trazer as informações do portal Status Invest e salvar em uma planilha.
A ideia é você listar os papeis de ações que você tem interesse em uma lista e o Python irá buscar os principais indicadores das ações listadas.

Estes são os principais indicadores que busquei:
- P/L
- P/VP
- D.Y.
- ROE
- DIV. LIQUIDA
- CAGR LUCRO

As unicas linhas que você deve preencher são as linhas 6 e 7.

path_to_save_file = fr'C:\Users\luane\Downloads\valores.xlsx'
lista_acoes       = ['aure3', 'cxse3', 'amer3']
