```mermaid
flowchart TD
A([START]) --> B[/INPUT Grade1/]
B --> C[/INPUT Grade2/]
C --> D[/INPUT Grade3/]
D --> E[PROCESS Average = Grade1 + Grade2 + Grade3]
E --> F[/DISPLAY Average/]
F --> G([END])
