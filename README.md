<h1>csvtax</h1>
<p>
Drupal 7 module to convert a CSV file into a hierarchical taxonomy.
</p>
<p>
Each line of the csv file should contain two comma separated terms- the first is the name of the parent followed by the name of the child term.
<br />
For example, a csv file that is based on the name of cities divided by states should look like this:
</p>
<pre>
Israel,Jerusalem<br />
USA,Washington<br />
Israel,TelAviv<br />
England,London<br />
USA,Seatle
</pre>

<h2>Installation instructions</h2>

1. Install the module.
2. Go to the configuration page. A link should appear near the module's name in the modules page following the installation.
3. Add the taxonoy name and upload the csv file.
4. Push the button and let the module take care of building the taxonomy.
