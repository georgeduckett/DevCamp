<html lang="en">
   <head>
      <meta charset="utf-8">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <meta name="viewport" content="width=device-width, initial-scale=1">
	  <link rel="stylesheet" href="style.css">
   </head>
   <body id="home">
      <div class="container">
         <div class="jumbotron">
            <h1>Azure Readiness: DevCamp</h1>
            <p>February 2016 release. Source: <a href="http://aka.ms/azure-devcamp">http://aka.ms/azure-devcamp</a></p>
            <p>
               <a href="http://aka.ms/CloudCamp-AzureTrial" class="btn btn-success">Sign up for Microsoft Azure</a>
            </p>
            <div class="hidden">_We strongly recommend that presenters and camp attendees **run the [Installer](https://github.com/Azure-Readiness/DevCamp/releases/latest)** 
            rather than clone this repository. The installer is optimized for end users - it includes all NuGet packages, HTML documentation, etc._</div>
         </div>
         <div class="panel panel-default">
            <div class="panel-heading">
               <h3 class="panel-title">Suggested agenda for a one day Azure Camp with Hands On Labs (HOLs)</h3>
            </div>
            <div class="panel-body">
               <table class="table table-bordered table-hover">
                  <col>
                  <col>
                  <col>
                  <tr>
                     <th>Session</th>
                     <th>Time (min)</th>
                     <th>Activity</th>
                  </tr>
                  <tr>
                     <td rowspan=3>Intro to Azure</td>
                     <td>30</td>
			  <td><a href="Presentation/Keynote/Keynote.pptx">Presentation</a> | <a href="Presentation/Keynote/">Demos</a></td>
                  </tr>
                  <tr>
                     <td>15</td>
                     <td><a href="HOL/creating-azure-account-activating-msdn-benefits/">HOL - Signup</a></td>
                  </tr>
                  <tr>
                  <td>15</td>
                  <td><a href="HOL/working-with-the-new-portal/">HOL - Working with the Management Portal</a></td>
                  </tr>		
                  <tr>
                     <td rowspan=3>App Service</td>
                     <td>30</td>
			  <td><a href="Presentation/App-Service/App Service.pptx">Presentation</a> | <a href="Presentation/App-Service/">Demos</a></td>
                  </tr>
                  <tr>
                     <td rowspan=2>30</td>
                     <td><a href="HOL/get-started-with-websites-and-asp-net/">HOL - Deploy a Web App to Azure</a> <b>or</b></td>
                  </tr>
                  <tr>
                     <td><a href="HOL/build-mobile-app-with-web-client/">HOL - Create an app with a mobile and web client in Azure App Service<a/></td>
                  </tr>
                  <tr>
                     <td rowspan=2>Machine Learning</td>
                     <td>45</td>
                     <td><a href="/Presentation/Machine-Learning/Azure-Machine-Learning.pptx">Presentation</a> | <a href="Presentation/Machine-Learning/">Demos</a></td>
                  </tr>
                  <tr>
                     <td>45</td>
                     <td><a href="HOL/machine-learning/">HOL - Deploy a SPA with AD to Azure</a></td>
                  </tr>
                  <tr>
                     <td rowspan=2>IaaS</td>
                     <td>45</td>
                     <td><a href="Presentation/IaaS/IaaS.pptx">Presentation</a> | <a href="Presentation/IaaS/">Demos</a></td>
                  </tr>
                  <tr>
                     <td>45</td>
                     <td><a href="HOL/create-virtual-machine/">HOL - IaaS</a></td>
                  </tr>
                  <tr>
                     <td rowspan=3>Data overview</td>
                     <td>45</td>
                     <td><a href="Presentation/Data-Platform/Data-Platform.pptx">Presentation</a> | <a href="Presentation/Data-Platform/">Demos</a></td>
                  </tr>
                  <tr>
                     <td rowspan=2>45</td>
                     <td><a href="HOL/build-web-app-using-documentdb/">HOL - DocumentDB</a> <b>or</b></td>
                  </tr>
                  <tr>
                     <td><a href="HOL/sql-database/">HOL - Elastic Scale</a></td>
                  </tr>
               </table>
            </div>
         </div>
         <div class="panel panel-default">
            <div class="panel-heading">
               <h3 class="panel-title">Full presentation list</h3>
            </div>
            <div class="panel-body">
               <table class="table table-bordered table-striped table-hover">
					<tr>
					   <td>Keynote</td>
					   <td><a href="Presentation/Keynote/Keynote.pptx">Presentation<a/> | <a href="Presentation/Keynote/">Demos</a></td>
					   <td>This module introduces the Cloud and the Cadence of Azure.</td>
					</tr>
					<tr>
					   <td>PaaS</td>
					   <td><a href="Presentation/PaaS/Building Cloud Solutions.pptx">Presentation</a> | <a href="Presentation/PaaS/">Demos</a></td>
					   <td>This module provides an overview of how to design and deploy cloud solutions on Azure.</td>
					</tr>
					<tr>
					   <td>App Service</td>
					   <td><a href="Presentation/App-Service/App Service.pptx">Presentation</a> | <a href="Presentation/App-Service"/>Demos</a></td>
					   <td>This module outlines the high-level features of Azure App Service</td>
					</tr>
					<tr>
					   <td>Machine Learning</td>
					   <td><a href="Presentation/Machine-Learning/Azure-Machine-Learning.pptx">Presentation</a> | <a href="Presentation/Machine-Learning/">Demos</a></td>
					   <td>This module outlines the high-level features of Azure Machine Learning</td>
					</tr>
					<tr>
					   <td>Data Platform</td>
					   <td><a href="Presentation/Data-Platform/Data-Platform.pptx">Presentation</a> | <a href="Presentation/Data-Platform/">Demos</a></td>
					   <td>This module outlines the Data offerings on Microsoft Azure</td>
					</tr>
					<tr>
					   <td>Data Storage</td>
					   <td><a href="Presentation/Data-Storage/Data-Storage.pptx">Presentation</a> | <a href="Presentation/Data-Storage/">Demos</a></td>
					   <td>This module gives an overview of HDInsight</td>
					</tr>
					<tr>
					   <td>IaaS</td>
					   <td><a href="Presentation/IaaS/IaaS.pptx">Presentation</a> | <a href="Presentation/IaaS/">Demos</a></td>
					   <td>This module outlines the Virtual Machine and Virtual Network features of Microsoft Azure</td>
					</tr>
					<tr>
					   <td>Media</td>
					   <td><a href="Presentation/Media/Media.pptx">Presentation</a> | <a href="Presentation/Media/">Demos</a></td>
					   <td>This Module outlines the Media Service on Microsoft Azure.</td>
					</tr>
					<tr>
					   <td>Integration / Hybrid Workflows / API Management</td>
					   <td><a href="Presentation/Integration-Hybrid-Workflows/APIManagementIntro.pptx">Presentation</a> | <a href="Presentation/Integration-Hybrid-Workflows/">Demos</a></td>
					   <td>This module outlines the integration offerings on Microsoft Azure</td>
					</tr>
					<tr>
					   <td>Identity / Access Management</td>
					   <td><a href="Presentation/Identity-Access-Management/Identity and o365.pptx">Presentation</a> | <a href="Presentation/Identity-Access-Management/">Demos</a></td>
					   <td>This module outlines the Identity and Access Management offerings on Microsoft Azure</td>
					</tr>
					<tr>
					   <td>Conclusion</td>
					   <td><a href="Presentation/Conclusion/Conclusion.pptx">Presentation</a></td>
					   <td>This short presentation includes calls to action and signup links for camp attendees</td>
					</tr>
				 </table>
			</div>
      </div>
   </body>
</html>
