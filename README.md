

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=900&size=32&pause=1000&color=3B82F6&center=true&vCenter=true&width=800&lines=SQL+Practice+Notes;PostgreSQL+Query+Exercises" alt="Typing SVG" />
</div>


<p align="left">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
</p>

This folder contains a small set of SQL practice questions written in Markdown. Each file pairs a natural-language question with its SQL query, making it easy to review, study, and reuse.

## What’s Inside

- `01.md` to `20.md` for question-and-query practice entries
- `image/` for supporting assets

## Format

Each markdown file follows the same structure:

````md
# Question

Your SQL question here

# Query

```sql
SELECT ...;
```
````

## Example Topics

- Filtering rows with `WHERE`
- Checking for `NULL` values
- Using `BETWEEN` for ranges
- Updating data with `UPDATE`
- Concatenating text fields

## Notes

- The queries are written in a simple, readable style for learning purposes.
- You can expand this set by adding more numbered `.md` files using the same format.

## Database Layout

This project uses the schema shown below:

![Database layout](image/image.png)

The diagram includes the following tables:

- `patients`
- `doctors`
- `admissions`
- `province_names`

