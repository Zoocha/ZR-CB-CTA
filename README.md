# ZR Call To Action Installation Guide

To install the ZR Call To Action, follow the steps below:

1. Ensure the below has been added to the `composer.json` **installer-paths**:
    ```sh
    "web/recipes/custom/{$name}": ["type:drupal-recipe"]
    ```
2. Run `composer require zr/zr-call-to-action`
3. Run the following command (within `/web` directory):

    ```sh
    ddev drush recipe recipes/custom/zr-cb-cta
    ```

