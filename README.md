<h2>Open Source API</h2>
<b>Author:</b> Brian Ravn Pedersen, Data Engineer and Software Developer<br/>
<b>Created:</b> 2025-01-27<br/>
<b>Technologies used:</b> C#, .NET, PHP, Blazor WebAssembly, GitHub, Azure<br/>
<b>GitHub Repository:</b> https://github.com/brp-labs/open-source-api<br/>

<hr/>

<h3>Open Science Framework (OSF)</h3>

Scientific articles and research papers from the Open Science Framework platform are rendered here.

See the live site at Azure: [https://polite-pond-0c2949703.4.azurestaticapps.net](https://polite-pond-0c2949703.4.azurestaticapps.net)

<h3>Workflow</h3>

The workflow of this application is as follows: Code is written in <b>C#</b> within a <b>.NET</b> environment using <b>Blazor WebAssembly</b> in <b>Visual Studio</b>, and the code is stored in <b>GitHub</b>. It is then deployed to <b>Azure Static Web Apps</b>. The <b>CI/CD</b> pipeline is automated with <b>GitHub Actions</b> - a wonderful tool!

<h3>Proxy</h3>

I have created a small piece of middleware in <b>PHP</b> that acts as a proxy for the API. This is to prevent CORS issues during development when the application is running on a local host without server-side rendering.<h3>Open Science Framework</h3> 

[https://osf.io](https://osf.io)

<h3>Example of use</h3>
Search for recent articles and research papers about Generative AI.<br>


