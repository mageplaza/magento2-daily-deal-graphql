# Magento 2 Daily Deal GraphQL/PWA

Mageplaza Daily Deal Extension supports getting and pushing data on the website with GraphQl, this support for PWA Studio.

## How to install

Run the following command in Magento 2 root folder:

```
composer require mageplaza/module-daily-deal-graphql
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

**Note:**
Mageplaza Daily Deal GraphQL requires installing [Mageplaza Daily Deal](https://www.mageplaza.com/magento-2-daily-deal-extension/) in your Magento installation.

## 2. How to use

To perform GraphQL queries in Magento, please do the following requirements:

- Use Magento 2.3.x or higher. Set your site to [developer mode](https://www.mageplaza.com/devdocs/enable-disable-developer-mode-magento-2.html).
- Set GraphQL endpoint as `http://<magento2-server>/graphql` in url box, click **Set endpoint**. 
(e.g. `http://dev.site.com/graphql`)
- To view the queries that the **Mageplaza Shop By Brand GraphQL** extension supports, you can look in `Docs > Query` in the right corner

## 3. Devdocs

- [Shop By Brand API & examples](https://documenter.getpostman.com/view/10589000/SzRxXr7J)
- [Shop By Brand GraphQL & examples](https://documenter.getpostman.com/view/10589000/SzRxXrBj)


## 4. Contribute to this module

Feel free to **Fork** and contribute to this module and create a pull request so we will merge your changes main branch.

## 5. Get Support

- Feel free to [contact us](https://www.mageplaza.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star** ![star](https://i.imgur.com/S8e0ctO.png)
