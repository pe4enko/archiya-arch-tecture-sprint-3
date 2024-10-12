Regular **Markdown** here.

<!--
@startuml firstDiagram

Alice -> Bob: Hello
Bob -> Alice: Hi!
	
@enduml
-->

![](firstDiagram.svg)

Some more markdown.


Regular **Markdown** here.

```
@startuml firstDiagram

Alice -> Bob: Hello
Bob -> Alice: Hi!

@enduml
```

Some more markdown.

Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```