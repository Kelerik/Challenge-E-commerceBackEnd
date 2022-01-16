## Table of contents

- [Description](#description)
- [Installation Instructions](#installation-instructions)
- [Usage Instructions](#usage-instructions)

# Description

This application runs the back-end for an e-commerce store. You can manage your store's categories, products, as well as a number of tags to associate with each product.

# Installation Instructions

[Instructional video provided here!](https://drive.google.com/file/d/1t0YizjaOIZsraQ8QR5FkETT_9odwzLYk/view)

You must have Node.js installed on your system. Visit their [website](https://nodejs.org/en/download/) to download and install.

You must also have MySQL installed on your system. Visit their [website](https://dev.mysql.com/downloads/mysql/) to download and install.

Clone the repository code. In the terminal, navigate to the application's directory, then run the following command once:

```
npm install
```

After that, log into the MySQL shell, initialize the database, then exit the shell.

```
mysql -u root -p
source db/schema.sql
exit
```

Seed the database with some starting data.

```
npm run seed
```

# Usage Instructions

Once you have set up the app following the instructions above, you can run it by entering the following:

```
npm start
```

The application will execute in your terminal. You can test routes by navigating to the appropriate URLs in your browser, or using the [Insomnia](https://insomnia.rest/download) app.
