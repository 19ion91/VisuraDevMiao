<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'it'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DfZ000000NwbB',
				'VisuraMessaging',
				'https://tinextagroup--visuradev.sandbox.my.site.com/ESWVisuraMessaging1777976662755',
				{
					scrt2URL: 'https://tinextagroup--visuradev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://tinextagroup--visuradev.sandbox.my.site.com/ESWVisuraMessaging1777976662755/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
