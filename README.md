# ZR Call To Action Installation Guide

To install the ZR Call To Action, follow the steps below:

1. Open your terminal.
2. Navigate to your project directory.
3. Ahead of running `composer require zr/RECIPE_NAME` - ensure the below has been added to the root `composer.json` **installer-paths**
    ```sh
    "web/recipes/custom/{$name}": ["type:drupal-recipe"]
    ```
4. Run the following command to execute the ZR Call To Action installation:

    ```sh
    ddev drush recipe recipes/custom/zr-cb-cta
    ```

This command will execute the ZR Call To Action installation.
