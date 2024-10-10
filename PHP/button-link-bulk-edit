function replace_demo_request_button_link( $content ) {
    if ( is_page() && strpos( $_SERVER['REQUEST_URI'], '/uk/' ) !== false ) {
        $old_link = 'https://sea-flux.com/demo-request/';
        $new_link = 'https://sea-flux.com/uk/demo-request/';
        $content = str_replace( $old_link, $new_link, $content );
    } elseif ( strpos( $_SERVER['REQUEST_URI'], '/au/' ) !== false ) {
		$old_link = 'https://sea-flux.com/demo-request/';
        $new_link = 'https://sea-flux.com/au/demo-request/';
        $content = str_replace( $old_link, $new_link, $content );
	}
    return $content;
}
add_filter('the_content', 'replace_demo_request_button_link');
