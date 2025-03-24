# A Drupal via DDEV template on Codespaces

This is a [Drupal via DDEV](https://github.com/drud/ddev) template configured for ephemeral development environments on Github Codespaces.

## Next Steps

1. Clone this repository
2. From the terminal move to the folder of the training, for example cd pspc-training
3. Go to Code > Codespaces > Create new codespace based on main
4. Once the codespace is setup, move to the project folder by running `cd project`
5. Start the containers by running `ddev start`
6. Get dependencies by running `ddev composer install`
7. Install the website by running the command `ddev drush si --existing-config`
8. Login to your website by runnin `ddev drush uli` and visiting that URL