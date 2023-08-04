<a name="service"></a>
	<h3>Service</h3>
		You can obtain an OID as WEID and manage your own arc, e.g. by:
		<ul><li>		
			Free OID by <a href="https://oidplus.viathinksoft.com/oidplus/?goto=oidplus%3Acom.viathinksoft.freeoid" title="ViaThinkSoft">ViaThinkSoft</a>		  
   </li><li>		
			&quot;Private&quot; <a href="https://registry.frdl.de/?goto=com.frdlweb.freeweid">WEID</a> by Frdlweb
			</li>	
			<li>		
			&quot;Public&quot; <a href="https://registry.frdl.de/?goto=oidplus%3Acom.viathinksoft.freeoid">OID</a> by Frdlweb
			</li></ul>
   <br><a name="code"></a>
	<h3>Code</h3>
	<ul><li><b>JavaScript</b><br>
			<a href="https://github.com/danielmarschall/oidplus/blob/master/plugins/viathinksoft/objectTypes/oid/WeidOidConverter.js">WeidOidConverter.js</a><br><br></li>	
		<li><b>PHP</b><br>			<a href="https://github.com/danielmarschall/oidplus/blob/master/plugins/viathinksoft/objectTypes/oid/WeidOidConverter.class.php">WeidOidConverter.class.php</a><br><br></li>
		<li><b>Delphi</b><br>
			<a href="https://github.com/danielmarschall/oidplus_dos/blob/master/WEID_Delphi.pas">WEID_Delphi.pas</a><br><br></li>
		<li><b>Turbo Pascal</b><br>
			<a href="https://github.com/danielmarschall/oidplus_dos/blob/master/WEID.PAS">WEID.pas</a><br>
			<a href="https://github.com/danielmarschall/oidplus_dos/blob/master/VTSFUNCS.PAS">VTSFUNCS.pas</a> (Dependency)<br>
			<br><br></li>	
	</ul>	
	<a name="software"></a>
	<h3>Software</h3>
	We recommend the software <a href="https://oidplus.com/">OIDplus</a>  if you like to run your own (OID/)WEID-Registry.
	<br>
	<br>	 
	<br>
	<br>
	<a name="convert"></a>
	<h3>Online OID/WEID Converter</h3>	
	<p>You can use our online converter to test the conversion between OID/WEID:</p>
	<h4>Convert OID to WEID</h4>
	<p><b>Input:</b> <input type="text" value="2.999" name="oid" id="oid" oninput="oidInputChanged();" style="width:500px"></p>
	<div id="weid2a"></div>
	<div id="oid2a"></div>
	<br>
	<h4>Convert WEID to OID</h4>
	<p><b>Input:</b> <input type="text" value="weid:EXAMPLE-?" name="weid" id="weid" oninput="weidInputChanged();" style="width:500px"></p>
	<div id="weid2b"></div>
	<div id="oid2b"></div>
	<br>
	<br><br><br>	
	<a name="test"></a>
	<h3>Online OID/WEID-Converter (Beta)</h3>
	<p>You can use our online converter to test the conversion between OID/WEID:</p>
	<frdlweb-oid2weid></frdlweb-oid2weid>
	<br /><strong frdl-if-js-remove="2000">Loading...</strong>		
<br />
<br />
<script>
		oidInputChanged();
		weidInputChanged();
</script>
<script>
