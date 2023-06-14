# Mockando um modulo:
- jest.Mock(ENDEREÇO)

# Tipos de Mock
1. NOME_DA_CLASSE.prototype.NOME_DO_METODO = jest.fn().mockReturnValue(FIXTURE) \
O método da classe será substituida por uma função jest, cujo valor retornado será a Fixture

# Miscelânia:
1. Quero obter um Json final, cujo hoje só tenho uma parte. Poderia mockar a parte que falta para um teste TDD, a partir dele, programar o restante do json desejado.
2. é possível mockar uma função que esteja dentro de outras funções com jest.fn(), a fim de fazer um teste passar
