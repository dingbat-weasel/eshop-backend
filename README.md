# eShop Backend

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Link to live demo: [Demo](https://drive.google.com/file/d/1YE8F7MZVHQWdOcJnFSIdy9XwH1EM1w9K/view)

## Table of Contents

- [Description](#description)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Credits](#credits)
- [Questions](#questions)
- [License](#license)

## Description

This project models the back-end routes of an ecommerce website. It handles the fetching of data regarding the categories, products, and tags associated with an example online shop. I learned a lot during this project, I honed my sequelize knowledge and learned to write routes that communicate with an SQL database.

```
.
├── config/
│   └── connection.js
├── db/
│   └── schema.sql
├── models/
│   ├── index.js
│   ├── Category.js
│   ├── Product.js
│   ├── ProductTag.js
│   └── Tag.js
├── routes/
│   ├── index.js
│   └── api/
│       ├── index.js
│       ├── category-routes.js
│       ├── product-routes.js
│       └── tag-routes.js
├── seeds/
│   ├── index.js
│   ├── category-seeds.js
│   ├── product-seeds.js
│   ├── product-tag-seeds.js
│   └── tag-seeds.js
├── screencap/
│   └── eshop-backend-screencap.JPG
├── package.json
├── package-lock.json
├── server.js
├── .gitignore
├── .env
└── README.md
```

## Usage

As the project as solely backend you must clone the repository to your computer and run the application through node.js. I recommend using insomnia to monitor the data. To start, start a mysql server in the console. Run 'source db/schema.sql' to create the database. Exit the server and run 'npm run seed' to populate the DB. Run 'npm run start' or 'npm run watch' to run the server locally and use insomnia to monitor GET/POST/PUT/DELETE requests to the /api/categories, /products, and /tags routes.

![screenshot](./screencap/eshop-backend-screencap.JPG)

## Dependencies

This project utilizes 'dotenv', 'express', 'mysql2', and 'sequelize' modules.

## Credits

This project was built from starter files given to me by the University of Washington Bootcamp

## Questions

For questions/concerns you can reach me on [GitHub](https://github.com/dingbat-weasel) or by Email at isaacrperk@gmail.com.

This README was generated using [WRITEME](https://github.com/dingbat-weasel/WRITEME).

---

## License

MIT License
