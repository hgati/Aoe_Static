# Nginx fastcgi_cache for Magento 1.x

#### DON'T USE VARNISH(HARD TO MANAGE) FOR FULL PAGE CACHE ANYMORE !
#### Nginx All-In-One Solution is HERE !

- Nginx 1.13.9

    - http/2
    - tls (https) with Let's Encrypt
    - fastcgi_cache for Magento Full Page Cache

- Magento 1.7.0.2

    - the full page cache
        - product list pages
        - product view pages
        - home page and miscellaneous cms pages

    - the dynamic parts a punching hole based on Aoe_Static extension
        - the menu in the top left corner
        - the cart in the right sidebar
        - and the recently viewed products
        - and so on...

