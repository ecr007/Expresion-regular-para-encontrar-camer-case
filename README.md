# Expresion-regular-para-encontrar-camer-case

```sql
select * from table where fullname REGEXP BINARY '([A-Z][a-z0-9]+){2}' AND status = 1
```

// ([A-Z][a-z0-9]+){2}
