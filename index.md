<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DcZ000000xcMD',
				'Web_Chat_v2',
				'https://pflms--scvoicenew.sandbox.my.site.com/ESWWebChatv21737707144466',
				{
					scrt2URL: 'https://pflms--scvoicenew.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://pflms--scvoicenew.sandbox.my.site.com/ESWWebChatv21737707144466/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
