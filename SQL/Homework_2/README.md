-- Таблица employees

-- Создать таблицу employees
-- id. serial,  primary key,
-- employee_name. Varchar(50), not null

create table employees (
id serial primary key,
employee_name varchar (50) not null 
);

-- Наполнить таблицу employee 70 строками.

insert into employees (employee_name)
values ('Polina'),
       ('Kirill'),
       ('Sofia'),
       ('Olga'),
       ('Anastasia'),
       ('Dmitry'),
       ('Mark'),
       ('Nikolay'),
       ('Vicktoria'),
       ('Timofey'),
       ('Maksim'),
       ('Elizaveta'),
       ('Ekaterina'),
       ('Nikita'),
       ('Anna'),
       ('Valeria'),
       ('Sofa'),
       ('Gleb'),
       ('Roman'),
       ('Yaroslav'),
       ('Tatsiana'),
       ('Julia'),
       ('Kristina'),
       ('Matuei'),
       ('Ilya'),
       ('Serafima'),
       ('Marya'),
       ('Mila'),
       ('Alina'),
       ('Konstantin'),
       ('Artemiy'),
       ('Mikhail'),
       ('Melissa'),
       ('Juri'),
       ('Eva'),
       ('Artem'),
       ('Veronika'),
       ('Yuliana'),
       ('Vladislav'),
       ('Kira'),
       ('Varvara'),
       ('Georgiy'),
       ('Makar'),
       ('Stanislav'),
       ('Arina'),
       ('Fatima'),
       ('Semen'),
       ('Stepan'),
       ('David'),
       ('Andrey'),
       ('Igor'),
       ('Amira'),
       ('Aleksandra'),
       ('Antonina'),
       ('Ksenia'),
       ('Ivan'),
       ('Nika'),
       ('Vasilisa'),
       ('Egor'),
       ('Sergey'),
       ('Adelya'),
       ('Emilia'),
       ('Aleksey'),
       ('Svyatoslav'),
       ('Daniil'),
       ('Maya'),
       ('Vladimir'),
       ('Petr'),
       ('Tamara'),
       ('Margarita');
       
select * from employees;

-- Таблица salary


-- Создать таблицу salary
-- id. Serial  primary key,
-- monthly_salary. Int, not null

create table salary (
id serial primary key,
monthly_salary int not null
);


-- Наполнить таблицу salary 16 строками:
-- 1000

insert into salary (id, monthly_salary)
values (default, 1000);

-- 1100

insert into salary (id, monthly_salary)
values (default, 1100);

-- 1200

insert into salary (id, monthly_salary)
values (default, 1200);

-- 1300

insert into salary (id, monthly_salary)
values (default, 1300);

-- 1400

insert into salary (id, monthly_salary)
values (default, 1400);

-- 1500

insert into salary (id, monthly_salary)
values (default, 1500);

-- 1600

insert into salary (id, monthly_salary)
values (default, 1600);

-- 1700

insert into salary (id, monthly_salary)
values (default, 1700);

-- 1800

insert into salary (id, monthly_salary)
values (default, 1800);

-- 1900

insert into salary (id, monthly_salary)
values (default, 1900);

-- 2000

insert into salary (id, monthly_salary)
values (default, 2000);

-- 2100

insert into salary (id, monthly_salary)
values (default, 2100);

-- 2200

insert into salary (id, monthly_salary)
values (default, 2200);

-- 2300

insert into salary (id, monthly_salary)
values (default, 2300);

-- 2400

insert into salary (id, monthly_salary)
values (default, 2400);

-- 2500

insert into salary (id, monthly_salary)
values (default, 2500);

select * from salary;

-- Таблица employee_salary

-- Создать таблицу employee_salary
-- id. Serial  primary key,
-- employee_id. Int, not null, unique
-- salary_id. Int, not null

create table employee_salary (
id serial primary key,
employee_id int not null unique,
salary_id int not null 
);

-- Наполнить таблицу employee_salary 40 строками:
-- в 10 строк из 40 вставить несуществующие employee_id

insert into employee_salary (id, employee_id, salary_id)
values (default, 1, 20);

insert into employee_salary (id, employee_id, salary_id)
values (default, 2, 27);

insert into employee_salary (id, employee_id, salary_id)
values (default, 3, 16);

insert into employee_salary (id, employee_id, salary_id)
values (default, 4, 26);

insert into employee_salary (id, employee_id, salary_id)
values (default, 5, 30);

insert into employee_salary (id, employee_id, salary_id)
values (default, 6, 8);

insert into employee_salary (id, employee_id, salary_id)
values (default, 7, 17);

insert into employee_salary (id, employee_id, salary_id)
values (default, 8, 13);

insert into employee_salary (id, employee_id, salary_id)
values (default, 9, 25);

insert into employee_salary (id, employee_id, salary_id)
values (default, 10, 1);

insert into employee_salary (id, employee_id, salary_id)
values (default, 11, 24);

insert into employee_salary (id, employee_id, salary_id)
values (default, 12, 19);

insert into employee_salary (id, employee_id, salary_id)
values (default, 13, 4);

insert into employee_salary (id, employee_id, salary_id)
values (default, 14, 7);

insert into employee_salary (id, employee_id, salary_id)
values (default, 15, 11);

insert into employee_salary (id, employee_id, salary_id)
values (default, 16, 5);

insert into employee_salary (id, employee_id, salary_id)
values (default, 17, 14);

insert into employee_salary (id, employee_id, salary_id)
values (default, 18, 22);

insert into employee_salary (id, employee_id, salary_id)
values (default, 19, 28);

insert into employee_salary (id, employee_id, salary_id)
values (default, 20, 12);

insert into employee_salary (id, employee_id, salary_id)
values (default, 21, 2);

insert into employee_salary (id, employee_id, salary_id)
values (default, 22, 9);

insert into employee_salary (id, employee_id, salary_id)
values (default, 23, 6);

insert into employee_salary (id, employee_id, salary_id)
values (default, 24, 29);

insert into employee_salary (id, employee_id, salary_id)
values (default, 25, 18);

insert into employee_salary (id, employee_id, salary_id)
values (default, 26, 3);

insert into employee_salary (id, employee_id, salary_id)
values (default, 27, 15);

insert into employee_salary (id, employee_id, salary_id)
values (default, 28, 21);

insert into employee_salary (id, employee_id, salary_id)
values (default, 29, 10);

insert into employee_salary (id, employee_id, salary_id)
values (default, 30, 23);

insert into employee_salary (id, employee_id, salary_id)
values (default, 41, 50);

insert into employee_salary (id, employee_id, salary_id)
values (default, 42, 47);

insert into employee_salary (id, employee_id, salary_id)
values (default, 43, 46);

insert into employee_salary (id, employee_id, salary_id)
values (default, 44, 49);

insert into employee_salary (id, employee_id, salary_id)
values (default, 45, 44);

insert into employee_salary (id, employee_id, salary_id)
values (default, 46, 41);

insert into employee_salary (id, employee_id, salary_id)
values (default, 47, 45);

insert into employee_salary (id, employee_id, salary_id)
values (default, 48, 42);

insert into employee_salary (id, employee_id, salary_id)
values (default, 49, 43);

insert into employee_salary (id, employee_id, salary_id)
values (default, 50, 48);

select * from employee_salary;

-- Таблица roles

-- Создать таблицу roles
-- id. Serial  primary key,
-- role_name. int, not null, unique

create table roles (
id serial primary key,
role_name int not null unique
);

-- Поменять тип столба role_name с int на varchar(30)

alter table roles
alter column role_name type varchar(30)
using role_name::varchar(30);

-- Наполнить таблицу roles 20 строками:

insert into roles (id, role_name)
values (default, 'Junior Python developer');

insert into roles (id, role_name)
values (default, 'Middle Python developer');

insert into roles (id, role_name)
values (default, 'Senior Python developer');

insert into roles (id, role_name)
values (default, 'Junior Java developer');

insert into roles (id, role_name)
values (default, 'Middle Java developer');

insert into roles (id, role_name)
values (default, 'Senior Java developer');

insert into roles (id, role_name)
values (default, 'Junior JavaScript developer');

insert into roles (id, role_name)
values (default, 'Middle JavaScript developer');

insert into roles (id, role_name)
values (default, 'Senior JavaScript developer');

insert into roles (id, role_name)
values (default, 'Junior Manual QA engineer');

insert into roles (id, role_name)
values (default, 'Middle Manual QA engineer');

insert into roles (id, role_name)
values (default, 'Senior Manual QA engineer');

insert into roles (id, role_name)
values (default, 'Project Manager');

insert into roles (id, role_name)
values (default, 'Designer');

insert into roles (id, role_name)
values (default, 'HR');

insert into roles (id, role_name)
values (default, 'CEO');

insert into roles (id, role_name)
values (default, 'Sales manager');

insert into roles (id, role_name)
values (default, 'Junior Automation QA engineer');

insert into roles (id, role_name)
values (default, 'Middle Automation QA engineer');

insert into roles (id, role_name)
values (default, 'Senior Automation QA engineer');


select * from roles;
     
-- Таблица roles_employee

-- Создать таблицу roles_employee
-- id. Serial  primary key,
-- employee_id. Int, not null, unique (внешний ключ для таблицы employees, поле id)
-- role_id. Int, not null (внешний ключ для таблицы roles, поле id)

create table roles_employee (
id serial primary key,
employee_id int not null unique, 
role_id int not null,
foreign key (employee_id)
references employees (id),
foreign key (role_id)
references roles (id)
);

-- Наполнить таблицу roles_employee 40 строками:

insert into roles_employee (id, employee_id, role_id)
values (default, 1, 20);

insert into roles_employee (id, employee_id, role_id)
values (default, 3, 19);

insert into roles_employee (id, employee_id, role_id)
values (default, 5, 18);

insert into roles_employee (id, employee_id, role_id)
values (default, 7, 17);

insert into roles_employee (id, employee_id, role_id)
values (default, 9, 16);

insert into roles_employee (id, employee_id, role_id)
values (default, 11, 15);

insert into roles_employee (id, employee_id, role_id)
values (default, 13, 14);

insert into roles_employee (id, employee_id, role_id)
values (default, 15, 13);

insert into roles_employee (id, employee_id, role_id)
values (default, 17, 12);

insert into roles_employee (id, employee_id, role_id)
values (default, 19, 11);

insert into roles_employee (id, employee_id, role_id)
values (default, 21, 10);

insert into roles_employee (id, employee_id, role_id)
values (default, 23, 9);

insert into roles_employee (id, employee_id, role_id)
values (default, 25, 8);

insert into roles_employee (id, employee_id, role_id)
values (default, 27, 7);

insert into roles_employee (id, employee_id, role_id)
values (default, 29, 6);

insert into roles_employee (id, employee_id, role_id)
values (default, 31, 5);

insert into roles_employee (id, employee_id, role_id)
values (default, 33, 4);

insert into roles_employee (id, employee_id, role_id)
values (default, 35, 3);

insert into roles_employee (id, employee_id, role_id)
values (default, 37, 2);

insert into roles_employee (id, employee_id, role_id)
values (default, 39, 1);

insert into roles_employee (id, employee_id, role_id)
values (default, 41, 20);

insert into roles_employee (id, employee_id, role_id)
values (default, 43, 19);

insert into roles_employee (id, employee_id, role_id)
values (default, 45, 18);

insert into roles_employee (id, employee_id, role_id)
values (default, 47, 17);

insert into roles_employee (id, employee_id, role_id)
values (default, 49, 16);

insert into roles_employee (id, employee_id, role_id)
values (default, 51, 15);

insert into roles_employee (id, employee_id, role_id)
values (default, 53, 14);

insert into roles_employee (id, employee_id, role_id)
values (default, 55, 13);

insert into roles_employee (id, employee_id, role_id)
values (default, 57, 12);

insert into roles_employee (id, employee_id, role_id)
values (default, 59, 11);

insert into roles_employee (id, employee_id, role_id)
values (default, 61, 10);

insert into roles_employee (id, employee_id, role_id)
values (default, 63, 9);

insert into roles_employee (id, employee_id, role_id)
values (default, 65, 8);

insert into roles_employee (id, employee_id, role_id)
values (default, 67, 7);

insert into roles_employee (id, employee_id, role_id)
values (default, 69, 6);

insert into roles_employee (id, employee_id, role_id)
values (default, 4, 5);

insert into roles_employee (id, employee_id, role_id)
values (default, 8, 4);

insert into roles_employee (id, employee_id, role_id)
values (default, 16, 3);

insert into roles_employee (id, employee_id, role_id)
values (default, 26, 2);

insert into roles_employee (id, employee_id, role_id)
values (default, 36, 1);


select * from roles_employee;
