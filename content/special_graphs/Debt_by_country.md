<dl>

<div id='d3viz_1' style='height:400px;width:600px'></div>

<script src='//d3plus.org/js/d3.js' type='text/javascript'></script>
<script src='//d3plus.org/js/d3plus.js' type='text/javascript'></script>
<div id='d3viz_1'></div>

<script type="text/javascript">
            
(function (){

    var viz_data = [{"type": "alpha", "weight": 0.45, "value": 100}, {"type": "beta", "weight": 0.6, "value": 70}, {"type": "gamma", "weight": -0.2, "value": 40}, {"type": "delta", "weight": 0.1, "value": 15}];

    var visualization = d3plus.viz()
        .container('#scatterviz')
        .type('scatter')
        .color('type')
.text('type')
.y('weight')
.x('value')
.id('type')
.size(10)
        .data(viz_data)
        .draw();

})();

</script>
<script type="text/javascript">
        
    (function (){

        

        var viz_data = [{"Country":"Afghanistan","Debt":1.3761116},{"Country":"Albania","Debt":10.39395},{"Country":"Algeria","Debt":86.18226666},{"Country":"Angola","Debt":83.39229096},{"Country":"Antigua and Barbuda","Debt":1.51693516},{"Country":"Argentina","Debt":362.61171443},{"Country":"Armenia","Debt":6.2841096},{"Country":"Aruba","Debt":2.402695},{"Country":"Australia","Debt":582.35866},{"Country":"Austria","Debt":327.08029952},{"Country":"Azerbaijan","Debt":7.95731328},{"Country":"Bahamas","Debt":8.02244904},{"Country":"Bahrain","Debt":39.02561928},{"Country":"Bangladesh","Debt":109.54119328},{"Country":"Barbados","Debt":6.10645718},{"Country":"Belarus","Debt":31.13438031},{"Country":"Belgium","Debt":529.51556784},{"Country":"Belize","Debt":1.84996089},{"Country":"Benin","Debt":6.03913632},{"Country":"Bhutan","Debt":2.9492832},{"Country":"Bolivia","Debt":24.95008257},{"Country":"Bosnia and Herzegovina","Debt":7.3222292},{"Country":"Botswana","Debt":2.51041525},{"Country":"Brazil","Debt":1771.227684},{"Country":"Brunei Darussalam","Debt":0.35084725},{"Country":"Bulgaria","Debt":12.96027564},{"Country":"Burkina Faso","Debt":6.3196413},{"Country":"Burundi","Debt":2.27035566},{"Country":"Cabo Verde","Debt":2.5584218},{"Country":"Cambodia","Debt":7.97822988},{"Country":"Cameroon","Debt":14.94675309},{"Country":"Canada","Debt":1530.6428843},{"Country":"Central African Republic","Debt":0.96534395},{"Country":"Chad","Debt":4.87995264},{"Country":"Chile","Debt":80.31241152},{"Country":"China","Debt":7870.53873},{"Country":"Colombia","Debt":165.4720684},{"Country":"Comoros","Debt":0.2546445},{"Country":"Democratic Republic of the Congo","Debt":6.78799664},{"Country":"Congo","Debt":10.06689618},{"Country":"Costa Rica","Debt":33.9477285},{"Country":"Croatia","Debt":43.32598968},{"Country":"Cyprus","Debt":24.89497434},{"Country":"Czechia","Debt":77.71548931},{"Country":"C\u00f4te d'Ivoire","Debt":23.04141336},{"Country":"Denmark","Debt":117.48550212},{"Country":"Djibouti","Debt":1.50662512},{"Country":"Dominica","Debt":0.43274364},{"Country":"Dominican Republic","Debt":35.56536714},{"Country":"Ecuador","Debt":52.29312511},{"Country":"Egypt","Debt":260.42373003},{"Country":"El Salvador","Debt":18.37896922},{"Country":"Equatorial Guinea","Debt":4.66025952},{"Country":"Eritrea","Debt":9.82833274},{"Country":"Estonia","Debt":2.36200938},{"Country":"Eswatini","Debt":1.91668806},{"Country":"Ethiopia","Debt":52.24110304},{"Country":"Fiji","Debt":2.67376604},{"Country":"Finland","Debt":165.61407932},{"Country":"France","Debt":2739.4264948},{"Country":"Gabon","Debt":9.77175738},{"Country":"Gambia","Debt":1.36962729},{"Country":"Georgia","Debt":7.7540463},{"Country":"Germany","Debt":2256.7954392},{"Country":"Ghana","Debt":42.31381678},{"Country":"Greece","Debt":382.70030552},{"Country":"Grenada","Debt":0.71387184},{"Country":"Guatemala","Debt":20.38532265},{"Country":"Guinea","Debt":5.80342425},{"Country":"Guinea-Bissau","Debt":0.84463884},{"Country":"Guyana","Debt":2.1914111},{"Country":"Haiti","Debt":3.4792847},{"Country":"Honduras","Debt":10.05859404},{"Country":"Hong Kong","Debt":0.0},{"Country":"Hungary","Debt":112.43652804},{"Country":"Iceland","Debt":8.13216352},{"Country":"India","Debt":2051.77964},{"Country":"Indonesia","Debt":322.4345208},{"Country":"Iran","Debt":145.56853205},{"Country":"Iraq","Debt":113.18713736},{"Country":"Ireland","Debt":238.16898678},{"Country":"Israel","Debt":224.96926671},{"Country":"Italy","Debt":2703.0575649},{"Country":"Jamaica","Debt":15.20436216},{"Country":"Japan","Debt":12295.6209961},{"Country":"Jordan","Debt":41.96973504},{"Country":"Kazakhstan","Debt":34.31269472},{"Country":"Kenya","Debt":55.08351492},{"Country":"Kiribati","Debt":0.04391695},{"Country":"South Korea","Debt":671.6305847},{"Country":"Kuwait","Debt":24.3534096},{"Country":"Kyrgyzstan","Debt":4.67445726},{"Country":"Laos","Debt":12.92311125},{"Country":"Latvia","Debt":13.09567581},{"Country":"Lebanon","Debt":91.97208048},{"Country":"Lesotho","Debt":1.06669017},{"Country":"Liberia","Debt":1.50304744},{"Country":"Libya","Debt":50.88755736},{"Country":"Lithuania","Debt":18.3287808},{"Country":"Luxembourg","Debt":15.0513891},{"Country":"Macao","Debt":0.0},{"Country":"Madagascar","Debt":5.22310478},{"Country":"Malawi","Debt":4.38813232},{"Country":"Malaysia","Debt":210.31788146},{"Country":"Maldives","Debt":3.53184066},{"Country":"Mali","Debt":6.58537024},{"Country":"Malta","Debt":6.42559372},{"Country":"Marshall Islands","Debt":0.0514206},{"Country":"Mauritania","Debt":4.48944935},{"Country":"Mauritius","Debt":9.9973594},{"Country":"Mexico","Debt":671.7610095},{"Country":"Micronesia","Debt":0.07051413},{"Country":"Moldova","Debt":3.46942451},{"Country":"Montenegro","Debt":3.84145168},{"Country":"Morocco","Debt":79.010985},{"Country":"Mozambique","Debt":19.13245236},{"Country":"Myanmar","Debt":25.73608345},{"Country":"Namibia","Debt":7.20373639},{"Country":"Nauru","Debt":0.06884574},{"Country":"Nepal","Debt":9.56537306},{"Country":"Netherlands","Debt":475.69286135},{"Country":"New Zealand","Debt":59.06980875},{"Country":"Nicaragua","Debt":5.15565948},{"Country":"Niger","Debt":5.40693296},{"Country":"Nigeria","Debt":133.697258},{"Country":"Norway","Debt":156.94183791},{"Country":"Oman","Debt":48.70219194},{"Country":"Pakistan","Debt":214.06072905},{"Country":"Panama","Debt":26.5242024},{"Country":"Papua New Guinea","Debt":8.09292972},{"Country":"Paraguay","Debt":9.47287184},{"Country":"Peru","Debt":63.0770232},{"Country":"Philippines","Debt":139.47692928},{"Country":"Poland","Debt":281.66680125},{"Country":"Portugal","Debt":286.06965634},{"Country":"Puerto Rico","Debt":59.72606718},{"Country":"Qatar","Debt":102.04908476},{"Country":"Republic of North Macedonia","Debt":5.21582972},{"Country":"Romania","Debt":92.76050736},{"Country":"Russian Federation","Debt":222.0391944},{"Country":"Rwanda","Debt":5.10519367},{"Country":"Saint Kitts and Nevis","Debt":0.62944652},{"Country":"Saint Lucia","Debt":1.41170904},{"Country":"Saint Vincent and the Grenadines","Debt":0.61669728},{"Country":"Samoa","Debt":0.44591272},{"Country":"San Marino","Debt":1.2493926},{"Country":"Sao Tome and Principe","Debt":0.353457},{"Country":"Saudi Arabia","Debt":180.71636372},{"Country":"Senegal","Debt":15.6981468},{"Country":"Serbia","Debt":26.70845528},{"Country":"Seychelles","Debt":0.90129768},{"Country":"Sierra Leone","Debt":2.89343256},{"Country":"Singapore","Debt":407.75020011},{"Country":"Slovakia","Debt":51.52135248},{"Country":"Slovenia","Debt":36.05013808},{"Country":"Solomon Islands","Debt":0.21994116},{"Country":"South Africa","Debt":214.6473738},{"Country":"South Sudan","Debt":1.19145612},{"Country":"Spain","Debt":1371.4313268},{"Country":"Sri Lanka","Debt":69.8477036},{"Country":"Sudan","Debt":55.97150224},{"Country":"Suriname","Debt":2.65345418},{"Country":"Sweden","Debt":203.66653675},{"Country":"Switzerland","Debt":279.3910902},{"Country":"Syrian Arab Republic","Debt":null},{"Country":"Taiwan","Debt":203.96930934},{"Country":"Tajikistan","Debt":3.80758476},{"Country":"Tanzania","Debt":22.32123336},{"Country":"Thailand","Debt":214.28039788},{"Country":"Timor-Leste","Debt":null},{"Country":"Togo","Debt":3.9364884},{"Country":"Trinidad and Tobago","Debt":11.16312938},{"Country":"Tunisia","Debt":29.52399996},{"Country":"Turkey","Debt":211.36967173},{"Country":"Turkmenistan","Debt":15.229665},{"Country":"Tuvalu","Debt":0.01068641},{"Country":"Uganda","Debt":13.6079008},{"Country":"Ukraine","Debt":83.66905723},{"Country":"United Arab Emirates","Debt":82.16074952},{"Country":"United Kingdom","Debt":2423.599914},{"Country":"United States of America","Debt":22775.1897834},{"Country":"Uruguay","Debt":42.97120464},{"Country":"Uzbekistan","Debt":11.42695974},{"Country":"Vanuatu","Debt":0.49156386},{"Country":"Venezuela","Debt":163.96341642},{"Country":"Viet Nam","Debt":149.31646263},{"Country":"Yemen","Debt":15.84979974},{"Country":"Zambia","Debt":19.81532115},{"Country":"Zimbabwe","Debt":4.6780023}];

        var viz_d3viz_1 = d3plus.viz()
            .container('#d3viz_1')
            .data(viz_data)
            .type("tree_map")
            .id(['Country'])
            .size('Debt')
            .legend(false)
            .color('Debt')
            
            
            .depth(0)
            .draw();

    })();
    
</script>

<dl>