After the records for your domain name have propagated, you must associate them with your website. Use the following steps to enable the domain names using your web browser.

> [AZURE.NOTE] It can take some time for CNAME records created in the previous steps to propagate through the DNS system. You cannot add the domain name of to your Azure Website until the CNAME has propagated. If you are using an A record, you cannot add the A record domain name to your Azure Website until the **awverify** CNAME record created in the previous step has propagated.
> 
> You can use a service such as <a href="http://www.digwebinterface.com/">http://www.digwebinterface.com/</a> to verify that the CNAME is available.

1. In your browser, open the [Azure Management Portal](https://manage.windowsazure.com).

2. In the **Websites** tab, click the name of your site, select **Dashboard**, and then select **Manage Domains** from the bottom of the page.

	![](./media/custom-dns-web-site/dncmntask-cname-6.png)

6. Use the **DOMAIN NAMES** text boxes to enter the domain names to associate with this website. 

	![](./media/custom-dns-web-site/dncmntask-cname-7.png)

6. Click the check mark in the lower right corner to save the domain name configuration.

	Once configuration has completed, the custom domain name will be listed in the **domain names** section of the **Configure** page of your website.

At this point, you should be able to enter the custom domain name in your browser and see that it successfully takes you to your Azure Website. 