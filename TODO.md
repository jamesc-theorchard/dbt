- [ ] rip out query_for_existing > replace with get_relation
  - maybe part of the relation object is metadata about when the relation was pulled
    from the db (relation type, when we asked the db about it, columns, ??)
- [ ] add get_relation, list_relations
- fns / macros
  - [x] query_for_existing
  - [ ] get_columns_in_table
  - [x] rename
  - [x] truncate
  - [x] drop
  - [ ] reset_csv_table
  - [ ] load_csv_rows
  - [ ] handle_csv_table
  - [ ] make_date_partitioned_table
  - [x] macro: get_existing_relation_type
  - [ ] macro: create_table_as
  - [ ] macro: create_view_as
  - [ ] macro: create_archive_table
  - (go back through these after BQ pr is merged)
- [ ] deprecation warnings