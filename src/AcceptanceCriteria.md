# Acceptance Criteria

## Functional Requirements

1. Account Creation
    - Users should be able to create an account with an unique username and password
    - Test: The user submits a username and password that are both under 30 characters long on account creation page. The system should then create the account  with a success message and redirect the user back to the login page.
    - Error: An error message should be displayed on the screen if the user input an username that is already taken or if the username/password is over 30 characters.
2. Valid Login
    - Users should be able to login to their account with the correct username and password.
    - Test: The user enters a valid username and password on the login page. The system should then direct them to the home page.
    - Error: An error message should be displayed on the screen if the user input the incorrect username or password.
3. Planet Creation
    - Users should be able to create a unique planet entry with an optional image.
    - Test: The user should input valid planet data for the planet creation page with the name of the planet being less than 30 characters. The system should give the option to add an image for the planet that is not required. Also, the system should then direct the user back to the home page with a refreshed list of planets/moons.
    - Error: An error message should be displayed on the screen if the user input invalid data for the planet, a planet name that is already taken, or a planet name that is more than 30 characters.
4. Planet Deletion
    - Users should be able to delete planets using their identifier.
    - Test: After deletion of the planet, the user should be directed to the home page with a refreshed list that doesn’t include the deleted planet.
5. Moon Creation
    - Users should be able to create a unique moon entry with an optional image for a specific planet.
    - Test: The user should input valid moon data for the moon creation page with the name of the moon being less than 30 characters. The system should give the option to add an image for the moon that is not required. Also, the system should then direct the user back to the home page with a refreshed list of planets/moons.
    - Error: An error message should be displayed on the screen if the user input invalid data for the moon, a moon name that is already taken, or a moon name that is more than 30 characters.
6. Moon Deletion
    - Users should be able to delete moons using their identifier.
    - Test: After deletion of the moon, the user should be directed to the home page with a refreshed list that doesn’t include deleted moon.
7. Resource Access
    - Users should only be able to access a list of planets/moons that they have personally added to their account’s home page.
    - Test: The system should prevent a user from seeing or modifying planets/moons on another user’s account.

## Non-Functional Requirements

1. Password Security
    - Valid passwords inputted by users should not be seen on the screen in plaintext
    - Test: Verify passwords are not displayed on the interface when a user login or create an account.
2. Resource Controls
    - Only users with an account created should be able to manage planets/moons in the system.
    - Test: The system should prevent a user without an account from accessing the home page, planet/moon creation page, and planet/moon deletion page.
3. Clear Error Messages
    - Error messages should display clear and correct statements about the reasoning for the error.
    - Test: Verify error messages are valid for each scenario (ex. Username and password are invalid).
4. Success Message
    - A success message should appear on the interface after creating a new account.
    - Test: Verify a success message appears after submitting valid credentials on the account creation page.