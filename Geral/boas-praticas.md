# Testes:

1. Mock<br /><br />

Mocks com valores default. Se algum teste necessitar de um valor diferente, mudar o retorno somente naquele teste

# Typescript:

1. Import dentro de funções

Exemplo de uma importação default:
`const app = (await import('./config/app')).default`