##Week35_study

Review uge34 findings:  

1. Man skal ikke skrive commits ind, men et link til folderen med netbeans projekt.
2. Der var nogle interessante JPQL queries. Denne her kunne jeg godt have brugt til at finde personen med højeste værdi:  
_SELECT e FROM Employee e WHERE e.salary = (SELECT MAX(z.salary) FROM Employee z)_
