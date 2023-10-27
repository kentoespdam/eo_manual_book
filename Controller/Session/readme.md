# Session Class

> Handling login, session data, userInfo, reset password, toolbar list and menu event based user roles

## Method List

1. validate()
    > validating session request
    - check if session has login
2. login($in)
    > authenticating login request
3. getMenuEvent()
    > get accesses menu based user role
4. getTreeMenu()
    > get menu list based user role
5. getToolbarMenu()
    > get menu list for toolbar based user role
6. logout()
    > handling logout
7. getUserInfo()
    > getting user information
8. resetPwd($email)
    > resetting user password
