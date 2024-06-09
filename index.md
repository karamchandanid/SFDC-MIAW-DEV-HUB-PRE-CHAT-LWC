<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D0o0000016oQo',
				'MIAW_Pre_Chat_LWC',
				'https://devhubdk-dev-ed.my.site.com/ESWMIAWPreChatLWC1717930664718',
				{
					scrt2URL: 'https://devhubdk-dev-ed.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://devhubdk-dev-ed.my.site.com/ESWMIAWPreChatLWC1717930664718/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
