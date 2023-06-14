# Helpers:

Helpers são módulos que ajuda a simplificar retornos e evitar repetição de código.<br /><br />

Pode-se usar helpers para definir um padrão de um objeto, como um erro customizado.<br /><br />

Exemplo: helper.ts<br /><br />

```
import { HttpResponse } from '../protocols/https'

export const badRequest = (error: Error): HttpResponse => ({
  statusCode: 400,
  body: error
})
```
