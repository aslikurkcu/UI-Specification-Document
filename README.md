# User Interface
## Left Side of the Page
- Button
  - New User Button : When the button is pressed, a new field opens on the right to add users.
- Checkbox 
   - [x] Hide Disabled User : Hides disabled users.
  
- Users Table

| ID | User Name | Email | Enabled|
| :--- | :------- | :---- | :---- |
| 1 | AdminUser | admin@piworks.net | true |
| 2 | Test User | testuser@piworks.net | true |

Headers in the table should also have filter and sort icons.

## Right Side of the Page
- Button
  - Save User : After the new user field is filled, it becomes active and when it is pressed saves the new user information.
### New User Field
- A header 
```
New User
``` 
- User Information 
  - Text Fields
    - Username: Here should be an empty text field
    - Display Name: Here should be an empty text field
    - Phone: Here should be an empty text field
    - Email: Here should be an empty text field
  
  - Dropdown List
    - Select user roles...
      - Guest
      - Admin
      - SuperAdmin
      
  - Checkbox
    - Enabled:  
    - [ ] -- if the user is enabled click it
