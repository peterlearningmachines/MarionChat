<html>
	<body>
	<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en'; // For example, enter 'en' or 'en-US'
			embeddedservice_bootstrap.init(
				'00D2P0000008aoK',
				'Marion_chat',
				'https://marion.my.site.com/ESWMarionchat1765496960297',
				{
					scrt2URL: 'https://marion.my.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://marion.my.site.com/ESWMarionchat1765496960297/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
