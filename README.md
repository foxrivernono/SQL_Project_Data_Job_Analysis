TODO: Update contents of this later
# Introduction
Blablablablabla [project_sql folder](/project_sql/)

# Background
Blablablablabla

# Tools I Used
- **Bla:** blablabla
- **Bla:** blablabla
- **Blabla:** bla

# The Analysis
Bla blah blah blah

### Blah blah blah
Blablablabla

```SELECT
    job_id,
    job_title,
    job_location,
    job_schedule_type,
    salary_year_avg,
    job_posted_date,
    name AS company_name
FROM
    job_postings_fact
LEFT JOIN company_dim ON job_postings_fact.company_id = company_dim.company_id
WHERE
    job_title_short = 'Data Analyst' AND
    job_location = 'Anywhere' AND
    salary_year_avg IS NOT NULL
ORDER BY
    salary_year_avg DESC
LIMIT 10 
```

**Blahblahblah**
Blablablabla

![Top Paying Roles](assets\1_top_paying_roles.png)

Blablablabla

# What I Learned

Blablabla

** Blahblahblah **
blahblablahblah

# Conclusions

1. Blahblahblah
2. Blablablabla
3. Blahblablah

### Closing Thoughts
Blahblahblahblah