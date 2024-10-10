---


---

<h1 id="deploy-static-web-app-on-azure">DEPLOY STATIC WEB APP ON AZURE</h1>
<h4 id="the-easy-way-to-lear-how-deploy-web-apps">The easy way to lear how deploy web apps</h4>
<p>First, you need to log in on <a href="https://azure.microsoft.com/en-us/free/students">Azure for students</a> and find Azure services.</p>
<h2 id="create-the-resource">Create the Resource</h2>
<p>Select <strong>Create a Resource</strong> and next Static Web App, then click <em>Create New</em>; select a subscription and a Resource Group (or create a new resource group).</p>
<p>Type a name for the static web app and select a plan type.</p>
<p>Now select the source, (for this case GitHub) and select the Organization, Repository and Branch.</p>
<h3 id="buid-details-to-deploy">Buid Details to Deploy</h3>
<p>In the Build Details, need to select the Build Preset, in this case angular, App location that is for default “/”, API location in case that use an external API, and output location (is the path of your build output relative to your apps location)</p>
<h3 id="deploy-static-web-app">Deploy Static Web App</h3>
<p>Finally click on <em>Review + Create</em>, check the details and if is all rigth, click <em>Create</em>, and this will create a file on GitHub at the rute .github/workflows with extension .yml; it’s a job with the setings details describes in azure, for deploy the app on Azure Static Web App.</p>
<h2 id="configure-static-web-app">Configure Static Web App</h2>
<p>In the new window, click on <em>Go to Resource</em> to config the parameters</p>
<p>In the tab <em>Get Started</em> you can check the satus of deploy. Click on <em>Visit you site</em> to go to the <em><strong>Static Web App</strong></em>.</p>

