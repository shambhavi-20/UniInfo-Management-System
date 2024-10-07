# UniInfo-Management-System

Through the project, I aimed to reduce a problem that many high school students face: finding universities that best suit them. 

- I have a CSV to keep track of my data. If you add your data, the columns should be formatted like:
  - Name (Name of Univerity)
  - control (Public/Private University)
  - region (Region of USA)
  - locale (Locale of the University)
  - admrate (Admission Rate)
  - ACT
  - SAT
  - parttime (Percentage of part-time undergrads)
  - avgcost (Average cost of the University)
  - expstu (University expenditure per student)
  - retentionrate (Retention rate)
  - avgincome (Average family income mean earnings 8 years after entry at the University)

- If you do not have already done that, you can create your data using the function **Adm_addnewattribute()**.
- New columns can be added using the function **Adm_addnewattribute()**.
- You can modify the university information based on the university name using the function **Adm_modify()**.
- You can delete the information of the university based on the University name using the function **Adm_delete()**.
- You can search if the university exists in your database and also directly add the university if it does not use the function **user_searchuni**.
- The database can be sorted based on any attribute using the function **user_sort()**.
- A request for a new university can be added using function **user_requestnewuni()**.
- Specific columns can selected using the function **user_selective()**.
- A few metrics can also be calculated: Total sum of test scores (sumtestscores()), average score of ACT for a private university (avgprivate_ACT()), average score of ACT for a public university (avgpublic_ACT()), average score of SAT for a private university (avgprivate_SAT()), average score of SAT for a public university (avgpublic_SAT()).

The rest is an interactive way you can interact with the database and solve the problem of understanding which universities would be the best for you!
