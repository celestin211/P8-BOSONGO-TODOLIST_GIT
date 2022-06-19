#OPENCLASSROOMS TodoList#

' Description of need '

'Bug Fixes '

' A task must be attached to a user '

Currently, when a task is created, it is not attached to a user. You are asked to bring the
necessary corrections so that automatically, when the task is saved, the authenticated user is attached to
the newly created task.

When editing the task, the author cannot be changed.

For tasks already created, they must be attached to an “anonymous” user.
Choose a role for a user

When creating a user, it must be possible to choose a role for it. The roles listed are
following:

  - user role (ROLE_USER);
  - administrator role (ROLE_ADMIN).

When modifying a user, it is also possible to change the role of a user.

' Implementing new features '

' Permission '

Only users with the administrator role (ROLE_ADMIN) should be able to access the management pages of
users.

Tasks can only be deleted by users who created the task in question.

Tasks attached to the “anonymous” user can only be deleted by users with the
administrator role (ROLE_ADMIN).

' Implementing automated tests '

You are required to implement the automated tests (unit and functional tests) necessary to ensure that
the operation of the application is well in line with the requests.

These tests must be implemented with PHPUnit; you can also use Behat for the functional part.

You will provide test data in order to be able to prove operation in the cases explained in this document.

' Facility '

1. Clone the repo:
```
    git clone https://github.com/celestin211/PJ8_TODO
```

2. Edit the .env with your information.

3. Install dependencies:
```
    composer install
```

4. Set up the database:
```
    php bin/console doctrine:database:create
    php bin/console doctrine:migrations:migrate
```
