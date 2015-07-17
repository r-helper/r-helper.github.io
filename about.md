---
layout: default
title: About
---

# Об этом сайте

Это небольшой учебный сайт, посвященный изучению
и применению языка R.

Блог сайта: [R-helper.blogspot.com](http://R-helper.blogspot.com)

Твиттер: [@R4_helper](https://twitter.com/R4_helper)

---

Пример кода:

```
df <- swiss    
fit <- lm(Fertility ~ Examination + Catholic, data = swiss)    
summary(fit)    
confint(fit)    
ggplot(swiss, aes(x = Catholic, y = Fertility)) +     
  geom_point() +     
  geom_smooth(method = 'lm')    
```

Пример формулы: $ H_0 $

