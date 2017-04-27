Prettier for pre-commit
========================

Tslint package for pre-commit>=0.12.0.

For pre-commit: see https://github.com/pre-commit/pre-commit

For Prettier: see https://github.com/prettier/prettier


### Using Prettier with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/awebdeveloper/pre-commit-prettier
        sha: ''  # Use the sha or tag you want to point at
        hooks:
        -   id: prettier
            additional_dependencies: ['prettier@1.1.0']

        
   
