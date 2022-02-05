<h1>Hi,Serverless way(Interesting..... Go further)</h1>
<hr/>
<h3>The above method will save the HTML form data in excel file(You can remove) and sends the form data to mail</h3>

<h4>https://docs.google.com/spreadsheets/d/1Bn4m6iA_Xch1zzhNvo_6CoQWqOAgwwkOWJKC-phHx2Q/copy</h4>
<br/>
<p>Open the above link in a new tab</p>
<br/>
<ol>
<li>Then Click on the make a copy</li>
<li>Click on the Extensions button on top and move to <strong>APPS SCRIPT</strong></li>
<li>Paste the Code From the GoogleAppScript.js to that file(Change to your mail in the code)</li>
<li>Click on Deployment</li>
<li>and then We get script copy that and paste in the // form action=".Link should be here."//s</li>

</ol>

<h4>Using the template in index.html in this repo, create your own html file with the basic form. (save the file)

⚠️ If you're already trying to use your own form by this step rather than the example one in this repo:

Each of your form elements must have a name attribute equal to that of your column name in the Google sheet
The form's class must be gform, i.e. <form class="gform">
</h4>