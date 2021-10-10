# Where

create table Students(name varchar(20), Lastname varchar(20), rolenumber integer, History integer, Math integer, Science integer);
insert into Students VALUES("Arjun","Totre", 10,85,86,90,100);
insert into Students VALUES("Desmond","Wong", 76,89,86,10,5);
insert into Students VALUES("Devin","Yip", 98,60,86,70,100);
insert into Students VALUES("Rhys","Thomas", 1,96,89,90,100);
select*from Students where Math = 86;
