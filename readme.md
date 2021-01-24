Self-implemented indexes of a mock RDBMS implementation
using B-Trees to improve query performance. Without the index, the RDBMS query is served via page scan and with
an index created the RDBMS query is served via index seek leading to lesser numbers of data page loads from the
hard disk and higher performance.
