For ESLint, you will likely need to install these packages globally:
* npm install -g eslint
* npm install -g eslint-plugin-react
* npm install -g babel-eslint

For the pre-commit hook, you will need to run:
git config core.hooksPath .

Airbnb docs:
* JavaScript Linting Rules﻿
* React Linting Rules﻿


// running manually
eslint <path-to-file> --fix
prettier --config .prettierrc.json <path-to-file>
