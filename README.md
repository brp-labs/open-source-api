<h2>Open Science Framework (OSF)</h2>
Scientific articles and research papers from the Open Science Framework platform are rendered here.

See the live site at Azure: [https://polite-pond-0c2949703.4.azurestaticapps.net](https://polite-pond-0c2949703.4.azurestaticapps.net)

<h3>Workflow</h3>

The workflow of this application is as follows: Code is written in <b>C#</b> within a <b>.NET</b> environment using <b>Blazor WebAssembly</b> in <b>Visual Studio</b>, and the code is stored in <b>GitHub</b>. It is then deployed to <b>Azure Static Web Apps</b>. The <b>CI/CD</b> pipeline is automated with <b>GitHub Actions</b> A wonderful tool!

<h3>Proxy</h3>

I have created a small piece of middleware in <b>PHP</b> that acts as a proxy for the API. This is to prevent CORS issues during development when the application is running on a local host without server-side rendering.<h3>Open Science Framework</h3> 

[https://osf.io](https://osf.io)



Der skal indlæses 25 poster ad gangen, hver gang der klikkes på "Indlæs poster". Når appen starter er page = 1. Og når der er indlæst 25 poster - med eller uden søgeord - så er currentRange lige med 1-25.Ved næster klik på tasten er page = 2 og hvis der igen kan indlæses 25 poster, så er currentRange 26-50. Hvis der ved klik på tasten "Indlæs poster" står et NYT søgeord i indputfeltet (et tomt indputfelt er et lovligt søgeord, dvs. intet søgeord), så sættes page=1 og der startes forfra, og det samme gør CurrentRange.