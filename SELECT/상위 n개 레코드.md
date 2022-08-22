### 상위 n개 레코드

🔒 [문제 보기](https://school.programmers.co.kr/learn/courses/30/lessons/59405)

```SQL
SELECT Name
from ANIMAL_INS
where DATETIME in
    (select Min(DATETIME)
    from ANIMAL_INS)
```

------
