function exclude_woocommerce_styles() {
//remove generator meta tag
remove_action( 'wp_head', array( $GLOBALS['woocommerce'], 'generator' ) );

//check woo exists
if ( function_exists( 'is_woocommerce' ) ) {
//dequeue scripts and styles
  if ( ! is_woocommerce() && ! is_cart() && ! is_checkout() ) {
    wp_dequeue_style( 'woocommerce_frontend_styles' );
    wp_dequeue_style( 'woocommerce_fancybox_styles' );
    wp_dequeue_style( 'woocommerce_chosen_styles' );
    wp_dequeue_style( 'woocommerce_prettyPhoto_css' );
    wp_dequeue_script( 'wc_price_slider' );
    wp_dequeue_script( 'wc-single-product' );
    wp_dequeue_script( 'wc-add-to-cart' );
    wp_dequeue_script( 'wc-cart-fragments' );
    wp_dequeue_script( 'wc-checkout' );
    wp_dequeue_script( 'wc-add-to-cart-variation' );
    wp_dequeue_script( 'wc-single-product' );
    wp_dequeue_script( 'wc-cart' );
    wp_dequeue_script( 'wc-chosen' );
    wp_dequeue_script( 'woocommerce' );
    wp_dequeue_script( 'prettyPhoto' );
    wp_dequeue_script( 'prettyPhoto-init' );
    wp_dequeue_script( 'jquery-blockui' );
    wp_dequeue_script( 'jquery-placeholder' );
    wp_dequeue_script( 'fancybox' );
    wp_dequeue_script( 'jqueryui' );
    
    /* YESTE WE ADD */
     wp_dequeue_script( 'wc-add-payment-method' );
 wp_dequeue_script( 'wc-lost-password' );
 wp_dequeue_script( 'wc_price_slider' );
 wp_dequeue_script( 'wc-single-product' );
 wp_dequeue_script( 'wc-add-to-cart' );
 wp_dequeue_script( 'wc-cart-fragments' );
 wp_dequeue_script( 'wc-credit-card-form' );
 wp_dequeue_script( 'wc-checkout' );


 wp_dequeue_style( 'woocommerce-smallscreen' );
 wp_dequeue_style( 'woocommerce_fancybox_styles' );
 wp_dequeue_style( 'woocommerce_chosen_styles' );
 wp_dequeue_style( 'woocommerce_prettyPhoto_css' );
 wp_dequeue_style('wc-memberships-frontend');
 wp_dequeue_style('membership-metaboxes');
 wp_dequeue_style('membership-frontendcss');
 wp_dequeue_style('membership-subscriptionformcss');
 wp_dequeue_style('membership-accountformcss');
 wp_dequeue_style('membership-subscriptionformcss');
 wp_dequeue_style('membership-upgradeformcss');
 wp_dequeue_style('membership-renewformcss');
 wp_dequeue_style('membership-fancyboxcss');
 wp_dequeue_style('membership-popupmemcss');
 wp_dequeue_style('membership-accountformcss');
 wp_dequeue_style('membership-upgradeformcss');
 wp_dequeue_style('membership-renew');
    }
  }
}
