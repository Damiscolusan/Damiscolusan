
SELECT emp_no, avg(salary) as Average_salary FROM employees.salaries
where emp_no= "11300"
group by emp_no;
