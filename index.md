<html> 
  <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00Dg800000Q4pGI',
				'retail_messaging',
				'https://orgfarm-e68435ba5a.my.site.com/ESWretailmessagi1794339087213',
				{
					scrt2URL: 'https://orgfarm-e68435ba5a.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://orgfarm-e68435ba5a.my.site.com/ESWretailmessagi1794339087213/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</html>
