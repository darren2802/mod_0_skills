## tony is an instance of the Chef class

```
Initialize:
name("Tony")
age(42)
seniority_level(3)
qualifications["Secondary School","Chef level 3", "Souffle level 2"]
salary(40000)
times_dishes_cooked {
  :tomato_soup 17,
  :fillet_steak 13,
  :creme_brule 9
}
```

`cook_dish(tomato_soup: increments tomato_soup in the times_dishes_cooked hash from 17 to 18)`

`take_course("Hygiene in the kitchen", pushes this to the qualifications array)`

`promote(5000, decrements seniority_level to 2 and increases salary by 5000 to 45000)`
