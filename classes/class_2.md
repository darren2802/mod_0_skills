## class Table

**attributes**

table_number(integer)
number_patrons(integer)
dishes_ordered(hash)
served_by(string)
check_total(float)
check_paid(boolean)
survey_feedback(integer)

**methods**

Initialize(modifies table_number, number_patrons, served_by)

take_order(modifies dishes_ordered and check_total)

pay_check(modifies check_paid)

complete_survey(modifies survey_feedback with value from 1-10)
