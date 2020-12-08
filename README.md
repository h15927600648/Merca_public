```mermaid
graph LR
t1(WorkPace)
t2(Index/stage)
t3(Repository)
t4(Remote)
t1--add-->t2
t2--commit-->t3
t3--checkout-->t1
t3--push-->t4
t4--clone/fetch-->t3
t4--pull-->t1

```

