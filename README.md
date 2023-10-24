# UsefullLinks
<h3>SQL Server Authentication Modes</h3>
<p> https://docs.microsoft.com/en-us/sql/connect/ado-net/sql/azure-active-directory-authentication?view=sql-server-ver15#using-active-directory-service-principal-authentication </p>


<h3> Configuration Variables and Order of precedence </h3>
<p>https://learn.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-6.0</p>

Below is Higest to Lowest
1) Command-line arguments using the Command-line configuration provider.
2) Non-prefixed environment variables using the Non-prefixed environment variables configuration provider.
3) User secrets when the app runs in the Development environment.
4) appsettings.{Environment}.json using the JSON configuration provider. For example, appsettings.Production.json and appsettings.Development.json.
5) appsettings.json using the JSON configuration provider.
6) A fallback to the host configuration described in the next section.

<h3> ASCII </h3>
https://www.ascii-code.com/ </br>


<h3>Connect to App Service via CLI </h3>
az webapp create-remote-connection --subscription <b>subscriptionId</b> --resource-group <b>rgName</b> -n <b>webAppName</b> &
</br>
ssh root@127.0.0.1 -p <b>port</b>
</br>
https://learn.microsoft.com/en-us/azure/app-service/configure-linux-open-ssh-session?pivots=container-linux

<h3>Connect to mysql </h3>
mysql -h <b>hostName</b> -u <b>userName</b> -p

<h3>Quick look at files in webapp</h3>
http://<b>yoursitename</b>.scm.azurewebsites.net </br>
 
