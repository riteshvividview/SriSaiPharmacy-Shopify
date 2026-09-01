Website on: https://y0nbf3-a4.myshopify.com/

### Connect Shopify CLI to your store:

shopify theme dev --store [my-store.myshopify.com](https://y0nbf3-a4.myshopify.com/)

### You can check which store you're connected to with:

shopify theme info

### Now pull the existing theme:

shopify theme pull

#### For example, if you want your current live theme, you can also explicitly do:

shopify theme pull --live

#### Or specify a particular theme:

shopify theme pull --theme 123456789

#### You can also specify the store explicitly:

shopify theme pull --store my-store.myshopify.com

#### The CLI supports --store, --theme, --live, --development, --path, and --ignore for theme pull.

shopify theme dev --ignore config/settings_data.json

shopify theme push --ignore config/settings_data.json