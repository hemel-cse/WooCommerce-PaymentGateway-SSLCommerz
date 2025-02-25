# SSLCommerz for WooCommerce

> WooCommerce plugin for SSLCommerz payment gateway with IPN Support.

## Getting Started

### Prerequisites

1. Wordpress 5.1.*
2. WooCommerce 3.6.*
3. cURL php extension.

### Installation

1. Download zip file or Clone the repository.
2. Unzip if downloaded zip file.
3. Move the whole directory to ```/wp-content/plugins/```
4. Activate the plugin through the 'Plugins' menu in admin panel.

### Configuration

1. Open Admin Panel.
2. Navigate to ```Woocommerce > Settings > Payments``` tab.

![Payments Menu](images/config1.png)

3. Click on SSLCommerz to edit the settings. If you do not see SSLCommerz in the list at the top of the screen make sure you have activated the plugin in the WordPress Plugin Manager.
4. Enable the Payment Method, give a proper title and description to show on the checkout page,  fill up stroe id and store passowrd fields carefully, select success and fail/cancel page.
5. Find the IPN URL. It will look like ```[your site]/index.php?sslcommerzipn```. Copy this URL, it will be needed in the next step.
6. Login to your SSLCommerz merchant panel. Navigate to ```My Stores > IPN Settings``` from menu. Find ```IPN at HTTP Listner``` section at the bottom of the page.
7. Paste the URL obtained from step 5. Check the box labeled ```Enable HTTP Listner```. Click ```Save```.
8. Setup is complete. Check if everything is working properly.


## FAQ

### What is WooCommerce?
> WooCommerce is an open-source e-commerce plugin for WordPress. 

### What is SSLCommerz?
> SSLCOMMERZ is the first payment gateway in Bangladesh opening doors for merchants to receive payments on the internet via their online stores.
### What is a Payment Gateway?
> Payment Gateway is a service that allows merchant to accept secure credit card transactions online. It essentially connects a merchant website to a transaction processor like bank to take payment from a customer for an order.


## Contributors
> Prabal Mallick,
> C.M. Sayedur Rahman,
> Rakibul Islam
