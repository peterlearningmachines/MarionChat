<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DOg000001wSWS',
				'Customer_Service_MIAW_Chat',
				'https://marion--comuat.sandbox.my.site.com/ESWCustomerServiceMIAW1762916111894',
				{
					scrt2URL: 'https://marion--comuat.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://marion--comuat.sandbox.my.site.com/ESWCustomerServiceMIAW1762916111894/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
