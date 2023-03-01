# MyRemoteDesk-Complete-Workspace-Integrated-Platform




## TECH STACK:

Python <br/>
Django <br/>
Electron JS <br/>
Node JS <br/>
MySQL <br/>
HTML,CSS,JS,BOOTSTRAP5

## HOW TO RUN PROJECT:

# WEB APP:
<pre>
<code>
pip install -r requirements.txt
cd MyRemoteDeskWebApp
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

Check on localhost:8000

Change domain credentials in <a rel="license" href="https://github.com/narender-rk10/MyRemoteDesk-Complete-Workspace-Integrated-Platform/blob/master/MyRemoteDeskWebApp/MyRemoteDesk/settings.py">settings.py</a> for email service.
</code>
</pre>

# DESKTOP APP:
<pre>
<code>
cd MyRemoteDeskDesktopApp
npm install
npm start
</code>
</pre>

# VIDEO APP:
<pre>
<code>
cd MyRemoteDeskVideoApp
npm install
npm start

Check on localhost:3000
</code>
</pre>

## PROPOSED SYSTEM
# A) Employee Management System
1) Login, Register, Forgot Password, Change Password, OTP Verification [Both sides Organization & Employee]
2) Organization can add, view, update, delete employee
3) Organization and Employee have separate dashboards
4) Organization can create notices and notify to employees.
5) On Every activity of Organization & Employees, email will be notified.

# B) Employee Monitoring System
1) App/Website Track Usage
2) Screen Shot Monitoring
3) Power Monitoring
4) Check Productivity of Employee
5) Detailed analysis of Employee work productivity with help of Statistics.


# C) Project Management System
1) Organization can create project, boards
2) Organization can assign & un-assign the employee from the project
3) Organization can create task and assign task to the employees.
4) Organization can use dashboard to track the progress of the project
5) Organization can check the gantt chart of the project.
6) On every event of project, email will notified to the employee.
7) Employee can check the project, boards, tasks and can mark as complete task


# D) Attendance & Leave Management System 
1) Employee whenever login & logout from the system, attendance log is sent to the organization.
2) Logs contain entry login time, logout time, location of employee, ip address, etc
3) Organization can check the attendance logs of every employee with date filter.
4) Employee can apply for leaves for any specific reason.
5) Organization can approve or reject the leave the employee leave request.


# E) Group Video Conferencing System:
 
1) Organization can create video meeting for specific project group.
2) Employee can join meeting link from the dashboard.
3) Employee and Organization can turn on/off video or audio.
4) Employee and Organization can share both screens
5) Employee and Organization can both chat in meeting.
6) Employee and Organization can also record meeting and download in meeting only.



