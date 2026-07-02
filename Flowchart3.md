```mermaid
flowchart TD
A([START]) --> B[/INPUT number/]
B --> C{number MOD 2 = 0?}
C -- YES --> D[/DISPLAY Even/]
C -- NO --> E[/DISPLAY Odd/]
D --> F([END])
E --> F([END])
