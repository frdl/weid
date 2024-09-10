<a name="service"></a>

### Service
You can obtain an OID as WEID and manage your own arc, e.g. by:
* Free OID by [ViaThinkSoft](https://oidplus.viathinksoft.com/oidplus/?goto=oidplus%3Acom.viathinksoft.freeoid)
* Private [WEID](https://registry.frdl.de/?goto=com.frdlweb.freeweid) by Frdlweb
* Public [OID](https://registry.frdl.de/?goto=oidplus%3Acom.viathinksoft.freeoid) by Frdlweb


<a name="code"></a>

### Code
* JavaScript (supports Spec Change 12): [WeidOidConverter.js](https://github.com/frdl/weid/blob/gh-pages/WeidOidConverter.js)
* PHP (supports Spec Change 12): [WeidOidConverter.php](https://github.com/frdl/weid/blob/gh-pages/WeidOidConverter.php)
* Delphi (supports Spec Change 11): [WEID_Delphi.pas](https://github.com/danielmarschall/oidplus_dos/blob/master/WEID_Delphi.pas)
* Turbo Pascal (supports Spec Change 11): [WEID.pas](https://github.com/danielmarschall/oidplus_dos/blob/master/WEID.PAS) and [VTSFUNCS.pas (Dependency)](https://github.com/danielmarschall/oidplus_dos/blob/master/VTSFUNCS.PAS)


<a name="software"></a>

### Software
We recommend the software [OIDplus](https://oidplus.com/) if you like to run your own (OID/)WEID-Registry.

<a name="convert"></a>

### Online OID/WEID Converter
You can use our online converter to test the conversion between OID/WEID:

<h4>Convert OID to WEID</h4>
<p><b>Input:</b> <input type="text" value="2.999" name="oid" id="oid" oninput="oidInputChanged();" style="width:500px"></p>
<div id="weid2a"></div>
<div id="oid2a"></div>
<br>
<h4>Convert WEID to OID</h4>
<p><b>Input:</b> <input type="text" value="weid:EXAMPLE-?" name="weid" id="weid" oninput="weidInputChanged();" style="width:500px"></p>
<div id="weid2b"></div>
<div id="oid2b"></div>
<br><br>	

<!--
<a name="test"></a>
<h3>Online OID/WEID-Converter (Beta)</h3>
<p>You can use our online converter to test the conversion between OID/WEID:</p>
<frdlweb-oid2weid></frdlweb-oid2weid>
<br /><strong frdl-if-js-remove="2000">Loading...</strong>
<br /><br />
-->

<script>
oidInputChanged();
weidInputChanged();
</script>
<script>
