# UML Graph WordScramble

``` mermaid
classDiagram
    class `Game`
    class `GameResult`
    class `program`
    class `WordProvider`

    `program` --> `Game`
    `Game` o--> `GameResult`
    `Game` --> `WordProvider`

    ```