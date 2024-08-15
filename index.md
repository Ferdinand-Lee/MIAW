<html>

  <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DVG000000Lsa5',
				'Customer_Experience_Live_Message',
				'https://hawaiilife--hlgolightn.sandbox.my.site.com/ESWCustomerExperienceLi1721484555077',
				{
					scrt2URL: 'https://hawaiilife--hlgolightn.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://hawaiilife--hlgolightn.sandbox.my.site.com/ESWCustomerExperienceLi1721484555077/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</html>
