# In the app.py file under the Employees and edit_employee route handlers, this code was interpreted/copied from w3schools website for LEFT JOIN and aliases
# "SELECT e.employee_id, e.first_name, e.last_name, e.email, d.dept_name, r.title, e.active, e.hire_date 
#  FROM Employees e 
#  LEFT JOIN Departments d ON e.dept_id = d.dept_id 
#  LEFT JOIN Roles r ON e.role_id = r.role_id;"
# Date: 6/5/2023
# Adapted/copied from:
# Source URL:https://www.w3schools.com/sql/sql_join_left.asp  and  https://www.w3schools.com/sql/sql_alias.asp



# In the app.py file under the departments and edit_departments route handlers, this code was interpreted/copied from w3schools website for LEFT JOIN and aliases
# "SELECT d.dept_id, d.dept_name, e.first_name, e.last_name 
# FROM Departments d 
# LEFT JOIN Employees e 
# ON d.manager_employee_id = e.employee_id;"
# Date: 6/5/2023
# Adapted/copied from:
# Source URL:https://www.w3schools.com/sql/sql_join_left.asp  and  https://www.w3schools.com/sql/sql_alias.asp
