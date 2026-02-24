# Exercícios

Aqui estão os exercícios dado em cada dia de aula, separados por dia.

## Links

- [Exercícios da aula 1](./aula1)
- [Exercícios da aula 2](./aula2)
- [Exercícios da aula 3](./aula3)
- [Exercícios da aula 4](./aula4)
- [Exercícios da aula 5](./aula5)

## Diagrama da aula 2 em Mermaid

```mermaid
flowchart LR

A[É de Animação?]

A -- SIM --> B[É da Disney?]

B -- SIM --> F((Frozen))
B -- NÃO --> S((Shrek))

A -- NÃO --> C[Live Action]
C --> D[É de Terror?]

D -- SIM --> E[É de Comédia?]
E -- SIM --> TMP((Todo Mundo em Pânico))
E -- NÃO --> H((Halloween))

D -- NÃO --> R[Romance]
R --> DR[É de Drama?]
DR -- SIM --> DP((Diário de Uma Paixão))
DR -- NÃO --> PV((Como se Fosse a Primeira Vez))
```
