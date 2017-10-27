<html>
<head>
 <script type="text/javascript" src="//cdnjs.cloudflare.com/ajax/libs/jquery/1.9.0/jquery.js"></script>
<script type="text/javascript" src="https://www.google.com/jsapi"></script>
<script type="text/javascript" src="http://mgskjaeveland.github.io/sgvizler/v/0.6/sgvizler.js"></script>
  </head>  

<body>
<h1>Having trouble with picking a study?</h1>
<p>Search no further! Studypicker is the right tool for you! Just tick in some boxes and we will show you what you need! <br> This site will help you find your study, based on your preferences. You can filter by location (by city or province), field of study and whether the study is with a selection or not.<br> Go try it out! </p>

<img src="http://opelikaobserver.com/wp-content/uploads/2017/05/college-graduation.jpg" alt="Graduation" style="width:1000px;height:300px;">

<a href="https://www.w3schools.com">Link</a>

<h3>Please fill out the form </h3>

<form>
  <pre>
<strong> Selection </strong>
<input type="radio" name="Selection" value="Has no selection" checked> Without selection  <input type="radio" name="Selection" value="Has selection"> With selection 
<strong> Field of study </strong>
<input type="radio" name="field of study" value="Technical" checked> Technical  <input type="radio" name="field of study" value="Medicine"> Medicine
<input type="radio" name="field of study" value="Business"> Business   <input type="radio" name="field of study" value="Communication" > Communication 
<input type="radio" name="field of study" value="IT" > IT         <input type="radio" name="field of study" value="Law" > Law
<input type="radio" name="field of study" value="Social" > Social     <input type="radio" name="field of study" value="Theology" > Theology
<strong> Province </strong>
<input type="checkbox" name="Province1" value="North Holland"> North Holland   <input type="checkbox" name="Province2" value="South Holland"> South Holland     <input type="checkbox" name="Province3" value="Groningen"> Groningen
<input type="checkbox" name="Province4" value="Friesland"> Friesland       <input type="checkbox" name="Province5" value="Drenthe"> Drenthe           <input type="checkbox" name="Province6" value="Overijsel"> Overijsel
<input type="checkbox" name="Province7" value="Flevoland"> Flevoland       <input type="checkbox" name="Province8" value="Gelderland"> Gelderland        <input type="checkbox" name="Province9" value="Utrecht"> Utrecht
<input type="checkbox" name="Province10" value="Zeeland"> Zeeland         <input type="checkbox" name="Province11" value="North Brabant"> North Brabant     <input type="checkbox" name="Province12" value="Limburg"> Limburg
<strong> City </strong>
<input type="checkbox" name="City1" value="Amsterdam"> Amsterdam       <input type="checkbox" name="City2" value="Delft"> Delft             <input type="checkbox" name="City3" value="Eindhoven"> Eindhoven
<input type="checkbox" name="City4" value="Rotterdam"> Rotterdam       <input type="checkbox" name="City5" value="Groningen"> Groningen         <input type="checkbox" name="City6" value="The Hague"> The Hague
<input type="checkbox" name="City7" value="Leiden"> Leiden          <input type="checkbox" name="City8" value="Maastricht"> Maastricht        <input type="checkbox" name="City9" value="Tilburg"> Tilburg
<input type="checkbox" name="City10" value="Twente"> Twente          <input type="checkbox" name="City11" value="Utrecht"> Utrecht           <input type="checkbox" name="City" value="Wageningen"> Wageningen

  </pre>
</form>

<button type="button" onclick="alert('Results')">Show Results</button>

<div id="example"
     data-sgvizler-endpoint="http://sws.ifi.uio.no/sparql/npd"
     data-sgvizler-query="SELECT ?class (count(?instance) AS ?noOfInstances)
                          WHERE{ ?instance a ?class }
                          GROUP BY ?class
                          ORDER BY ?class"
     data-sgvizler-chart="google.visualization.PieChart"
     style="width:800px; height:400px;"></div>


<div id="logo"><a href="http://dev.data2000.no/sgvizler/"><img src="http://beta.data2000.no/sgvizler/misc/image/mr.sgvizler.png" alt="mr.sgvizler.png"></a><br>Mr. Sgvizler
         
      </div>
      <h3><code>sgvizler.visualization.Map</code>: Plot of most of the muncipalities of Rogaland, Norway
      </h3>
      <p></p>
      <div id="sgvzl_example_query" data-sgvizler-endpoint="http://dbpedia.org/sparql" data-sgvizler-query="SELECT ?lat ?long ?name ?text ?url ?image WHERE { ?url a dbpo:AdministrativeRegion ; dct:subject <http://dbpedia.org/resource/Category:Municipalities_of_Rogaland&gt; ; rdfs:label ?name; geo:lat ?lat; geo:long ?long . OPTIONAL{ ?url rdfs:comment ?text } OPTIONAL{ ?url dbpo:thumbnail ?image } FILTER(lang(?text)=&#34;en&#34;) FILTER(lang(?name)=&#34;en&#34;) }" data-sgvizler-chart="sgvizler.visualization.Map" data-sgvizler-loglevel="2" style="width:800px; height:600px;"></div>
      <p>The element which draws the above chart:</p><pre id="sgvzl_example_pre">&lt;div id="sgvzl_example_query" 
   data-sgvizler-endpoint="http://dbpedia.org/sparql" 
   data-sgvizler-query="SELECT ?lat ?long ?name ?text ?url ?image WHERE { ?url a dbpo:AdministrativeRegion ; dct:subject &amp;lt;http://dbpedia.org/resource/Category:Municipalities_of_Rogaland&gt; ; rdfs:label ?name; geo:lat ?lat; geo:long ?long . OPTIONAL{ ?url rdfs:comment ?text } OPTIONAL{ ?url dbpo:thumbnail ?image } FILTER(lang(?text)=&amp;quot;en&amp;quot;) FILTER(lang(?name)=&amp;quot;en&amp;quot;) }" 
   data-sgvizler-chart="sgvizler.visualization.Map" 
   data-sgvizler-loglevel="2" 
   style="width:800px; height:600px;"/&gt;</pre><h3>The results of the query in <code>gTable</code></h3>
      <div id="sgvzl_example_table" data-sgvizler-endpoint="http://dbpedia.org/sparql" data-sgvizler-query="SELECT ?lat ?long ?name ?text ?url ?image WHERE { ?url a dbpo:AdministrativeRegion ; dct:subject <http://dbpedia.org/resource/Category:Municipalities_of_Rogaland&gt; ; rdfs:label ?name; geo:lat ?lat; geo:long ?long . OPTIONAL{ ?url rdfs:comment ?text } OPTIONAL{ ?url dbpo:thumbnail ?image } FILTER(lang(?text)=&#34;en&#34;) FILTER(lang(?name)=&#34;en&#34;) }" data-sgvizler-chart="google.visualization.Table" data-sgvizler-loglevel="2" style="width:800px; height:200px;"></div>
      <div id="footer">
         <!--Please leave a link to the Sgvizler homepage.-->
         <p>
            	Sgvizler visualizes the result of SPARQL SELECT queries. For more
            	information, see the <a href="http://dev.data2000.no/sgvizler/">Sgvizler</a>
            	homepage. (c) 2011--2013 Martin G. Skjæveland.
            
         </p>
      </div>
</body>
</html>
