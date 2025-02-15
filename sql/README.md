## Stored Procedure

```bash
# for pg

create or replace procedure(p_name varchar, p_age int)
language plpgsql
as $$
declare 
    variable
begin
    procedure body - all logics

    raise notice 'any message we want show';
end;
$$

# consider an example where we have two tables
products, sales
# for every iphone sale, modify db accordingly



# for oracle
create or replace procedure(p_name varchar, p_age int)
as
    variable
begin
    procedure body - all logics
end;


# for mssql
create or alter procedure(@p_name varchar, @p_age int)
as
    declare @variable1, @variable1
begin
    procedure body - all logics
end;


# for mysql

delimiter $$ # any thing which we want to use as end.
drop procedure if exists procedure-name;
create procedure(p_name varchar, p_age int)
begin
    declare variable1,
    declare variable1;
    procedure body - all logics

    select 'any message we want show'
end $$

```