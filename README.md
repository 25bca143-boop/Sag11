

## Issues

Stores information about books borrowed by members.

| Column | Description |
|---|---|
| issue_id | Primary key |
| member_id | Foreign key referencing members |
| book_id | Foreign key referencing books |
| issue_date | Date when the book was issued |
| due_date | Expected return date |
| return_date | Actual return date |

## Members

Stores information about library members.

| Column | Description |
|---|---|
| member_id | Primary key |
| member_name | Name of member |
| member_type | Student or Faculty |
| joined_date | Date of joining |

## Books

Stores information about library books.

| Column | Description |
|---|---|
| book_id | Primary key |
| title | Book title |
| author | Book author |
| category | Book category |
| price | Book price |
| copies_available | Available book copies |
