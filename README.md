# PasswordStrength

## About 
- A field for entering a password has been added, and 3 sections have been added below the field to show the password strength;
- Password strength is changed in real-time;
- Password strength is calculated as follows:
  - Only letters/digits/symbols - the password is easy;
  - Combination of letters-symbols/letters-digits/digits-symbols - the password is medium;
  - Has letters, symbols and numbers - the password is strong;
- The color of the sections will depend on the strength of the password:
  - If the field is empty, all sections are ```gray```;
  - If the field has less than 8 characters, all sections are ```red```;
  - If the password is easy - the first section is ```red``` the rest are ```gray```;
  - If the password is medium - the first two sections are ```yellow``` the last one is ```gray```;
  - If the password is strong, all sections are ```green```;

# Run
- ```npm install```
- ```npm start```



