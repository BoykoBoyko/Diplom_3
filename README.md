# UI tests Selenium

Task # 3 of the graduation project from Yandex.Praktikum: **UI Tests**
Stellar Burgers web application: https://stellarburgers.nomoreparties.site/

Using Page Object.

**Registration**
- Successful registration.
- An error for an incorrect password. The minimum password is six characters.

**Log In**
- log in using the "Log in to account" button on the main page,
- log in using the "Personal Account" button,
- log in using the button in the registration form,
- log in using the button in the password recovery form.

**Swutch to your personal account**
- Check the click-through to the "Personal Account".
- Switching from your personal account to the constructor
- Check the transition by clicking on the "Constructor" and on the Stellar Burgers logo.

**Log out of your account**
- Check the exit by clicking the "Exit" button in your personal account.
- Section "Constructor"

**Checking that the transitions to the sections:**
- "Rolls",
- "Sauces",
- "Fillings"

Tests in test/java.
A separate package has been created for Page Object.

The tests are divided by subject

Separate classes have been created for the tests.

Tests run and don't crash.

An Allure report has been made.
