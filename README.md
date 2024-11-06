Practical Task:   

Framework: YII 
CRUD operation for user table
user table has user_id, user_name, user_email, user_mobile_no, user_type (admin, user, employee), created_at, updated_at, user_status
by default, a user has an inactive status
on sign-up activation link send to user email (in demo task just create a link, do not send actual mail)
also, on sign up send OTP on user's mobile (in the demo task just enter 1234 and validate that)
after activation of the user and validate OTP, now user can log in

user permission
admin user can do all actions like create, update, delete, and block/unblock the user
only registered users can do only update and view their own profile
 on all events (create, update, delete, and all) need to display a success or error message