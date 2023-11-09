# Environment variables

* `ASPNETCORE_ENVIRONMENT`: 'Development', 'Actions', 'Production'
* `SECRETS_MANAGER_ACCESS_TOKEN`: Must be initialized in a permanent way by adding the environment variable at the initalization of a shell. Afterwards, a restart of the IDE must be done so the changes occur.
* `TEST_LOGIN_EMAIL_SECRET`: Secret Id containing an email which can be used to log in on Auth0.
* `TEST_LOGIN_PASSWORD_SECRET`: Secret Id containing a password which can be used to log in on Auth0.

# Dependencies

Docker Engine or Docker Desktop must be installed in your machine so the dependency resolver script can prepare all the required dependencies as containers within your machine.

Once you've installed Docker Engine or Docker Desktop, all the dependencies can be prepared by running the `dev.sh` script embedded within the `compose` submodule.