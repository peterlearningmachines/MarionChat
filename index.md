<html>
	<body>
	<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
			embeddedservice_bootstrap.init(
				'00DOg000001wSWS',
				'Marion_chat',
				'https://marion--comuat.sandbox.my.site.com/ESWMarionchat1765244400117',
				{
					scrt2URL: 'https://marion--comuat.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://marion--comuat.sandbox.my.site.com/ESWMarionchat1765244400117/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
