# Análise

- Definir o que é o sistema
    - o que pertence ao sistema
    - do que é feito 
    - quais as partes

- Atores
    - Quem atua sobre o sistema?
    - Quem é ativo no sistema (faz coisas)
    - Não precisam ser só pessoas
    - É importante definir a classe deles (que tipo de ator é esse)
    -  Demias objetos/partes que compõem o sistema
        - Classificar também as partes (dar nomes aos tipos)

---

```mermaid
graph TD;
    A[ATOR]-->B;
    A-->C[ESTADO];
    B[FUNÇÃO]-->D;
    C-->D[OBJETO];
```
```mermaid
graph LR
    fa:fa-check-->fa:fa-coffee
```
```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice-->>John: Hello John how r u!
    loop Healthcheck
        John-->>John: Fight against hipocondrya
    end
    Note right of John: Rational Toughts <br/> prevail...
    John-->>Alice: Great!
    John-->>Bob: How about u?
    Bob-->>John: Good!
```
