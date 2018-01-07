# Lightweight CSS Grid
This is a simple lightweight css grid stylesheet to apply for a responsive and bootstrap-like ruleset. To apply these properties you need to structure as such: container -> row -> columns. There can be a total of 8 for column space in a row.

Couple rules to live by:
- Add as many rows in containers as you wish
- 1,2, or 4 columns in a row

## Classes

### .container
This is the holy container of all rows and columns. Best use is to have an outer container with multiple children rows.

### .grid-row
Welcome to the first child. This is a row (horizontal) and is your container for any columns.

### .grid-item-{2,4,8}
Column heaven. Unlike bootstrap, we use 1,2, and 4 size columns with a max of 8 column spaces per row.
