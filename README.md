# Probá Speco en 60 segundos

Speco revisa la **intención** de cada cambio antes de que alguien escriba código.
Este repo tiene la spec de un banco ficticio: límites de transferencias y revisión de fraude.

## Probalo (funciona desde el celular)

1. Abrí la spec para editarla: **[editar la regla](https://github.com/agustindelmonti/speco-playground/edit/main/specs/006-wire-transfer-limits/spec.md)**
2. Buscá **FR-005** y cambiá `10,000 USD` por `15,000 USD`.
3. *Commit changes…* → *Propose changes* → *Create pull request*.

En unos 30 segundos Speco comenta en tu PR qué cambia en el negocio y qué tarea quedó con el valor viejo.

¿Querés ver una contradicción? Agregá esta línea debajo de FR-010:

    - **FR-012**: When a verified customer confirms a wire, the system MUST charge a fee of 1% of the amount, with a minimum of 2.00 USD

## ¿Lo querés en tus repos?

**[Instalá Speco](https://github.com/apps/speco-pr-review/installations/new)**: un clic, funciona con repos privados. Cada PR que cambie una spec recibe esta revisión.

_Los datos de este repo son de ejemplo._
