# Esse é um título do Kderno

Aqui vai um texto para a gente começar.

| ID  | Cliente         | Idade | Sexo |
| --- | --------------- | ----- | ---- |
| 1   | Lucas           | 35    | M    |
| 2   | João das Couves | 32    | M    |

Aqui<mark> vai mais</mark> um texto **em negrito**.

>  Depois adiciono mais alguma coisa

```kderno
{"block": 1, "plugin": "subscriptionblock"}
```

```kderno
{"block": 2, "plugin": "quickessayblock"}
```

```kderno
{"block": 3, "plugin": "embednotebookblock"}
```

Aqui vai um [link para um kderno](/@lucas/meu-kderno-curso-1) que vou mostrar depois.

![Tux, the Linux mascot](https://mdg.imgix.net/assets/images/tux.png?auto=format&fit=clip&q=40&w=100)



## Subtítulo

```mermaid
graph TD;
A-->B;
A-->C;
B-->D;
C-->D;
```

### Sub sub título

# Gestão de projeto

```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       Adding GANTT diagram functionality to mermaid
    excludes    weekends
    %% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)

    section A section
    Completed task            :done,    des1, 2014-01-06,2014-01-08
    Active task               :active,  des2, 2014-01-09, 3d
    Future task               :         des3, after des2, 5d
    Future task2              :         des4, after des3, 5d

    section Critical tasks
    Completed task in the critical line :crit, done, 2014-01-06,24h
    Implement parser and jison          :crit, done, after des1, 2d
    Create tests for parser             :crit, active, 3d
    Future task in critical line        :crit, 5d
    Create tests for renderer           :2d
    Add to mermaid                      :1d
    Functionality added                 :milestone, 2014-01-25, 0d

    section Documentation
    Describe gantt syntax               :active, a1, after des1, 3d
    Add gantt diagram to demo page      :after a1  , 20h
    Add another diagram to demo page    :doc1, after a1  , 48h

    section Last section
    Describe gantt syntax               :after doc1, 3d
    Add gantt diagram to demo page      :20h
    Add another diagram to demo page    :48h
```
