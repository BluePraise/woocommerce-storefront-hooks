# woocommerce-storefront-hooks
A list of hooks for WooCommerce Storefront 
So I don't have to google each time

    ## Sidebar 
    `add_action( 'storefront_sidebar', 'storefront_get_sidebar', 10 );`

    `remove_action( 'woocommerce_before_main_content', 'storefront_before_content', 10 );`
    `remove_action( 'woocommerce_after_main_content', 'storefront_after_content', 10 );`

    `remove_action( 'homepage', 'storefront_product_categories', 20 );`
    `remove_action( 'homepage', 'storefront_recent_products', 30 );`
    `remove_action( 'homepage', 'storefront_featured_products', 40 );`
    `remove_action( 'homepage', 'storefront_popular_products', 50 );`
    `remove_action( 'homepage', 'storefront_on_sale_products', 60 );`
    `remove_action( 'homepage', 'storefront_homepage_content', 10 );`
    `remove_action( 'homepage', 'storefront_best_selling_products', 70 );`
    
    `remove_action( 'woocommerce_after_shop_loop', 'storefront_sorting_wrapper', 9 );`
    `remove_action( 'woocommerce_after_shop_loop', 'storefront_sorting_wrapper_close', 31 );`

    `remove_action( 'woocommerce_before_shop_loop', 'storefront_sorting_wrapper', 9 );`
    `remove_action( 'woocommerce_before_shop_loop', 'storefront_woocommerce_pagination', 30 );`
    `remove_action( 'woocommerce_before_shop_loop', 'storefront_sorting_wrapper_close', 31 );`
