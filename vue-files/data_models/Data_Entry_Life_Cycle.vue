<!-- Tufts VUE 3.3.0 concept-map (Data_Entry_Life_Cycle.vue) 2018-03-14 -->
<!-- Tufts VUE: http://vue.tufts.edu/ -->
<!-- Do Not Remove: VUE mapping @version(1.1) jar:file:/D:/ArbeitsProgramme/VUE/VUE.jar!/tufts/vue/resources/lw_mapping_1_1.xml -->
<!-- Do Not Remove: Saved date Wed Mar 14 17:11:01 CET 2018 by Admin on platform Windows 8 6.2 in JVM 1.7.0_21-b11 -->
<!-- Do Not Remove: Saving version @(#)VUE: built October 8 2015 at 1658 by tomadm on Linux 2.6.32-504.23.4.el6.x86_64 i386 JVM 1.7.0_21-b11(bits=32) -->
<?xml version="1.0" encoding="US-ASCII"?>
<LW-MAP xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:noNamespaceSchemaLocation="none" ID="0"
    label="Data_Entry_Life_Cycle.vue" created="1419753572415" x="0.0"
    y="0.0" width="1.4E-45" height="1.4E-45" strokeWidth="0.0" autoSized="false">
    <resource referenceCreated="1521043861183" size="31746"
        spec="D:\Git_Box\vue-files\Data_Entry_Life_Cycle.vue" type="1" xsi:type="URLResource">
        <title>Data_Entry_Life_Cycle.vue</title>
        <property key="File" value="D:\Git_Box\vue-files\Data_Entry_Life_Cycle.vue"/>
    </resource>
    <fillColor>#FFFFFF</fillColor>
    <strokeColor>#404040</strokeColor>
    <textColor>#000000</textColor>
    <font>SansSerif-plain-14</font>
    <URIString>http://vue.tufts.edu/rdf/resource/8fefdf19c0a8b21f006bc4d7fa1a415a</URIString>
    <child ID="59" label="entry status:&#xa;CURRENT DRAFT" layerID="1"
        created="1420250884062" x="526.9913" y="2375.9048" width="184.0"
        height="58.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#30D643</fillColor>
        <strokeColor>#776D6D</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-21</font>
        <URIString>http://vue.tufts.edu/rdf/resource/ada1c954c0a8b2190115222f4a4a1d30</URIString>
        <shape xsi:type="rectangle"/>
    </child>
    <child ID="62" label="entry status:&#xa;CURRENT PUBLISHED"
        layerID="1" created="1420250884062" x="1438.3706" y="2375.9048"
        width="233.0" height="58.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#30D643</fillColor>
        <strokeColor>#776D6D</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-21</font>
        <URIString>http://vue.tufts.edu/rdf/resource/ada1c954c0a8b2190115222f637110d3</URIString>
        <shape xsi:type="rectangle"/>
    </child>
    <child ID="106"
        label="MDB_BASIC_STATUS_TRANSITION: &#xa;create new MDB entry"
        layerID="1" created="1420254421905" x="22.776794" y="2381.9048"
        width="283.0" height="46.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FF0000</fillColor>
        <strokeColor>#776D6D</strokeColor>
        <textColor>#FFFFFF</textColor>
        <font>Arial-plain-16</font>
        <URIString>http://vue.tufts.edu/rdf/resource/aded8887c0a8b22600f0b6ad0933877e</URIString>
        <shape xsi:type="rectangle"/>
    </child>
    <child ID="110"
        label="mdbcore: &#xa;'has subsequent&#xa;entry status'"
        layerID="1" created="1420254626903" x="710.4912" y="2382.4048"
        width="728.37933" height="45.0" strokeWidth="1.0"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/aded8897c0a8b22600f0b6ad404dcd7f</URIString>
        <point1 x="710.9913" y="2404.9048"/>
        <point2 x="1438.3706" y="2404.9048"/>
        <ID1 xsi:type="node">59</ID1>
        <ID2 xsi:type="node">62</ID2>
    </child>
    <child ID="112"
        label="mdbcore: &#xa;'transition results in &#xa;subsequent entry status'"
        layerID="1" created="1420254668571" x="305.2768" y="2382.4048"
        width="222.21448" height="45.0" strokeWidth="1.0"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/aded8897c0a8b22600f0b6adc66bb731</URIString>
        <point1 x="305.7768" y="2404.9048"/>
        <point2 x="526.9913" y="2404.9048"/>
        <ID1 xsi:type="node">106</ID1>
        <ID2 xsi:type="node">59</ID2>
    </child>
    <child ID="135"
        label="MDB_BASIC_STATUS_TRANSITION: &#xa;move draft to recycle bin"
        layerID="1" created="1420257065511" x="203.49194" y="2544.5737"
        width="283.0" height="46.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FF0000</fillColor>
        <strokeColor>#776D6D</strokeColor>
        <textColor>#FFFFFF</textColor>
        <font>Arial-plain-16</font>
        <URIString>http://vue.tufts.edu/rdf/resource/aded8897c0a8b22600f0b6ad6d455f46</URIString>
        <shape xsi:type="rectangle"/>
    </child>
    <child ID="149" label="MDB_BASIC_STATUS_TRANSITION: &#xa;publish"
        layerID="1" created="1420257275183" x="986.87573" y="2450.1523"
        width="283.0" height="46.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FF0000</fillColor>
        <strokeColor>#776D6D</strokeColor>
        <textColor>#FFFFFF</textColor>
        <font>Arial-plain-16</font>
        <URIString>http://vue.tufts.edu/rdf/resource/adf2f64ec0a8b22600f0b6adf770c53d</URIString>
        <shape xsi:type="rectangle"/>
    </child>
    <child ID="150"
        label="mdbcore: &#xa;'has transition &#xa;to subsequent&#xa;entry status'"
        layerID="1" created="1420257275183" x="710.4913" y="2413.1426"
        width="276.88446" height="60.0" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/adf2f64ec0a8b22600f0b6ad8e15da99</URIString>
        <point1 x="710.9913" y="2417.244"/>
        <point2 x="986.87573" y="2454.2346"/>
        <ID1 xsi:type="node">59</ID1>
        <ID2 xsi:type="node">149</ID2>
        <ctrlPoint0 x="959.2856" y="2450.546" xsi:type="point"/>
    </child>
    <child ID="151"
        label="mdbcore: &#xa;'transition results in &#xa;subsequent entry status'"
        layerID="1" created="1420257275183" x="1269.3757" y="2433.4048"
        width="214.98694" height="50.964844" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/adf2f64ec0a8b22600f0b6ad3875eaee</URIString>
        <point1 x="1269.8757" y="2471.913"/>
        <point2 x="1483.8627" y="2433.9048"/>
        <ID1 xsi:type="node">149</ID1>
        <ID2 xsi:type="node">62</ID2>
        <ctrlPoint0 x="1393.4485" y="2470.8306" xsi:type="point"/>
    </child>
    <child ID="170" label="Data Entry Life Cycle" layerID="1"
        created="1420294198719" x="-355.22012" y="1936.2238"
        width="2065.5095" height="49.0" strokeWidth="1.0"
        autoSized="false" xsi:type="node">
        <fillColor>#A6A6A6</fillColor>
        <strokeColor>#A6A6A6</strokeColor>
        <textColor>#000000</textColor>
        <font>Trajan Pro-plain-36</font>
        <URIString>http://vue.tufts.edu/rdf/resource/b04a62e8c0a8b226010e269430021cc8</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="350"
        label="mdbcore: &#xa;'has transition &#xa;to subsequent&#xa;entry status'"
        layerID="1" created="1420939905990" x="370.8372" y="2433.4048"
        width="188.91306" height="111.668945" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/d6a8bd55c0a8b22c0027449d24b2b029</URIString>
        <point1 x="559.25024" y="2433.9048"/>
        <point2 x="371.3372" y="2544.5737"/>
        <ID1 xsi:type="node">59</ID1>
        <ID2 xsi:type="node">135</ID2>
        <ctrlPoint0 x="421.5191" y="2500.7634" xsi:type="point"/>
    </child>
    <child ID="383" label="entry status:&#xa;DRAFT IN RECYCLE BIN"
        layerID="1" created="1421367442476" x="493.99127" y="2684.504"
        width="250.0" height="58.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#30D643</fillColor>
        <strokeColor>#776D6D</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-21</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f0388233c0a8b2330081d1eded83dc13</URIString>
        <shape xsi:type="rectangle"/>
    </child>
    <child ID="384"
        label="mdbcore: &#xa;'has subsequent&#xa;entry status'"
        layerID="1" created="1421367638068" x="513.3538" y="2433.4048"
        width="94.0" height="251.59912" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f0388233c0a8b2330081d1ed5b1cfaba</URIString>
        <point1 x="602.6459" y="2433.9048"/>
        <point2 x="597.67633" y="2684.504"/>
        <ID1 xsi:type="node">59</ID1>
        <ID2 xsi:type="node">383</ID2>
        <ctrlPoint0 x="520.5466" y="2579.5652" xsi:type="point"/>
    </child>
    <child ID="385"
        label="mdbcore: &#xa;'transition results in &#xa;subsequent entry status'"
        layerID="1" created="1421367664765" x="324.45978" y="2590.0737"
        width="170.0315" height="111.04639" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f0388233c0a8b2330081d1ed61fad9be</URIString>
        <point1 x="349.43805" y="2590.5737"/>
        <point2 x="493.99127" y="2700.62"/>
        <ID1 xsi:type="node">135</ID1>
        <ID2 xsi:type="node">383</ID2>
        <ctrlPoint0 x="368.2049" y="2687.6555" xsi:type="point"/>
    </child>
    <child ID="386"
        label="MDB_BASIC_STATUS_TRANSITION:&#xa;delete draft"
        layerID="1" created="1421367673068" x="681.8345" y="2815.915"
        width="279.0" height="46.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FF0000</fillColor>
        <strokeColor>#776D6D</strokeColor>
        <textColor>#FFFFFF</textColor>
        <font>Arial-plain-16</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f0388233c0a8b2330081d1edd88f7376</URIString>
        <shape xsi:type="rectangle"/>
    </child>
    <child ID="387"
        label="mdbcore: &#xa;'has transition &#xa;to subsequent&#xa;entry status'"
        layerID="1" created="1421367700261" x="665.2811" y="2742.004"
        width="119.44409" height="74.41113" strokeWidth="1.0"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f0388234c0a8b2330081d1ed078c0a50</URIString>
        <point1 x="665.7811" y="2742.504"/>
        <point2 x="784.2252" y="2815.915"/>
        <ID1 xsi:type="node">383</ID1>
        <ID2 xsi:type="node">386</ID2>
    </child>
    <child ID="391"
        label="MDB_BASIC_STATUS_TRANSITION:&#xa;recycle draft as new current draft"
        layerID="1" created="1421367994222" x="742.3922" y="2546.366"
        width="279.0" height="46.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FF0000</fillColor>
        <strokeColor>#776D6D</strokeColor>
        <textColor>#FFFFFF</textColor>
        <font>Arial-plain-16</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f0388234c0a8b2330081d1ed4f8bd598</URIString>
        <shape xsi:type="rectangle"/>
    </child>
    <child ID="392"
        label="mdbcore: &#xa;'has transition &#xa;to subsequent&#xa;entry status'"
        layerID="1" created="1421367994222" x="743.4913" y="2591.8652"
        width="148.08649" height="108.56616" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f0388234c0a8b2330081d1ed8ee4e204</URIString>
        <point1 x="743.9913" y="2699.9314"/>
        <point2 x="882.6769" y="2592.3652"/>
        <ID1 xsi:type="node">383</ID1>
        <ID2 xsi:type="node">391</ID2>
        <ctrlPoint0 x="885.82135" y="2684.5315" xsi:type="point"/>
    </child>
    <child ID="393"
        label="mdbcore: &#xa;'transition results in &#xa;subsequent entry status'"
        layerID="1" created="1421368004253" x="687.50824" y="2433.4048"
        width="177.44232" height="113.46118" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f0388234c0a8b2330081d1edb9bb7cfd</URIString>
        <point1 x="862.8716" y="2546.366"/>
        <point2 x="688.00824" y="2433.9048"/>
        <ID1 xsi:type="node">391</ID1>
        <ID2 xsi:type="node">59</ID2>
        <ctrlPoint0 x="813.4613" y="2486.6184" xsi:type="point"/>
    </child>
    <child ID="401"
        label="mdbcore: &#xa;'has subsequent&#xa;entry status'"
        layerID="1" created="1421368877956" x="625.656" y="2433.4048"
        width="94.0" height="251.59912" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f0388236c0a8b2330081d1ed7f0da70b</URIString>
        <point1 x="638.1564" y="2684.504"/>
        <point2 x="634.17584" y="2433.9048"/>
        <ID1 xsi:type="node">383</ID1>
        <ID2 xsi:type="node">59</ID2>
        <ctrlPoint0 x="709.1458" y="2577.0852" xsi:type="point"/>
    </child>
    <child ID="463"
        label="MDB_BASIC_STATUS_TRANSITION:&#xa;save current draft"
        layerID="1" created="1421394105984" x="204.78427" y="2222.9023"
        width="279.0" height="46.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FF0000</fillColor>
        <strokeColor>#776D6D</strokeColor>
        <textColor>#FFFFFF</textColor>
        <font>Arial-plain-16</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f1d07e51c0a8b23301cdace44b1b78a5</URIString>
        <shape xsi:type="rectangle"/>
    </child>
    <child ID="464"
        label="mdbcore: &#xa;'has transition &#xa;to subsequent&#xa;entry status'"
        layerID="1" created="1421394105984" x="358.5489" y="2268.4023"
        width="168.94238" height="110.83496" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f1d07e51c0a8b23301cdace41676e8f2</URIString>
        <point1 x="526.9913" y="2378.7373"/>
        <point2 x="359.0489" y="2268.9023"/>
        <ID1 xsi:type="node">59</ID1>
        <ID2 xsi:type="node">463</ID2>
        <ctrlPoint0 x="407.7922" y="2344.8337" xsi:type="point"/>
    </child>
    <child ID="465" label="entry status:&#xa;SAVED DRAFT VERSION"
        layerID="1" created="1421394105984" x="498.9763" y="2062.98"
        width="252.0" height="58.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#30D643</fillColor>
        <strokeColor>#776D6D</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-21</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f1d07e52c0a8b23301cdace43472bcb6</URIString>
        <shape xsi:type="rectangle"/>
    </child>
    <child ID="466"
        label="mdbcore: &#xa;'has subsequent&#xa;entry status'"
        layerID="1" created="1421394105984" x="510.8922" y="2120.48"
        width="94.0" height="255.9248" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f1d07e52c0a8b23301cdace4ca1660da</URIString>
        <point1 x="599.98175" y="2375.9048"/>
        <point2 x="603.8544" y="2120.98"/>
        <ID1 xsi:type="node">59</ID1>
        <ID2 xsi:type="node">465</ID2>
        <ctrlPoint0 x="513.86633" y="2244.5312" xsi:type="point"/>
    </child>
    <child ID="467"
        label="mdbcore: &#xa;'transition results in &#xa;subsequent entry status'"
        layerID="1" created="1421394105984" x="344.96326" y="2120.48"
        width="169.05627" height="102.92236" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f1d07e52c0a8b23301cdace419bd87ee</URIString>
        <point1 x="356.83902" y="2222.9023"/>
        <point2 x="513.51953" y="2120.98"/>
        <ID1 xsi:type="node">463</ID1>
        <ID2 xsi:type="node">465</ID2>
        <ctrlPoint0 x="395.74725" y="2151.623" xsi:type="point"/>
    </child>
    <child ID="468"
        label="mdbcore: &#xa;'has subsequent&#xa;entry status'"
        layerID="1" created="1421394131238" x="620.19946" y="2120.48"
        width="94.0" height="255.9248" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f1d07e52c0a8b23301cdace4d163ba6d</URIString>
        <point1 x="638.73114" y="2120.98"/>
        <point2 x="633.5094" y="2375.9048"/>
        <ID1 xsi:type="node">465</ID1>
        <ID2 xsi:type="node">59</ID2>
        <ctrlPoint0 x="698.27875" y="2246.5278" xsi:type="point"/>
    </child>
    <child ID="473"
        label="MDB_BASIC_STATUS_TRANSITION:&#xa;saved draft as new current draft"
        layerID="1" created="1421394606365" x="770.9733" y="2222.9023"
        width="279.0" height="46.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FF0000</fillColor>
        <strokeColor>#776D6D</strokeColor>
        <textColor>#FFFFFF</textColor>
        <font>Arial-plain-16</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f1d07e53c0a8b23301cdace4326ea82b</URIString>
        <shape xsi:type="rectangle"/>
    </child>
    <child ID="474"
        label="mdbcore: &#xa;'has transition &#xa;to subsequent&#xa;entry status'"
        layerID="1" created="1421394606365" x="747.175" y="2120.48"
        width="140.15039" height="102.92236" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f1d07e53c0a8b23301cdace456da1a08</URIString>
        <point1 x="747.675" y="2120.98"/>
        <point2 x="886.8254" y="2222.9023"/>
        <ID1 xsi:type="node">465</ID1>
        <ID2 xsi:type="node">473</ID2>
        <ctrlPoint0 x="793.0613" y="2131.707" xsi:type="point"/>
    </child>
    <child ID="475"
        label="mdbcore: &#xa;'transition results in &#xa;subsequent entry status'"
        layerID="1" created="1421394606365" x="700.66266" y="2268.4023"
        width="185.8371" height="108.00244" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/f1d07e53c0a8b23301cdace47918751a</URIString>
        <point1 x="885.99976" y="2268.9023"/>
        <point2 x="701.16266" y="2375.9048"/>
        <ID1 xsi:type="node">473</ID1>
        <ID2 xsi:type="node">59</ID2>
        <ctrlPoint0 x="814.82635" y="2335.7905" xsi:type="point"/>
    </child>
    <child ID="1286" label="entry status:&#xa;DELETED DRAFT" layerID="1"
        created="1425855931107" x="526.81464" y="2913.6892"
        width="181.0" height="58.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#30D643</fillColor>
        <strokeColor>#776D6D</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-21</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fba7c479c0a8b217000f40b6b2f9307e</URIString>
        <shape xsi:type="rectangle"/>
    </child>
    <child ID="1290"
        label="mdbcore: &#xa;'has subsequent&#xa;entry status'"
        layerID="1" created="1426211289186" x="570.74036" y="2742.004"
        width="94.0" height="172.1836" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/10d4ef83c0a8b22b00495234d48d9e9f</URIString>
        <point1 x="618.6531" y="2742.504"/>
        <point2 x="617.3612" y="2913.6875"/>
        <ID1 xsi:type="node">383</ID1>
        <ID2 xsi:type="node">1286</ID2>
        <ctrlPoint0 x="617.47363" y="2843.6426" xsi:type="point"/>
    </child>
    <child ID="1294"
        label="mdbcore: &#xa;'transition results in &#xa;subsequent entry status'"
        layerID="1" created="1426772397897" x="699.786" y="2861.415"
        width="141.0" height="64.34546" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/3243ff80c0a8b22c016d93aba238325e</URIString>
        <point1 x="808.8482" y="2861.915"/>
        <point2 x="707.81464" y="2925.2605"/>
        <ID1 xsi:type="node">386</ID1>
        <ID2 xsi:type="node">1286</ID2>
        <ctrlPoint0 x="782.24054" y="2910.9272" xsi:type="point"/>
    </child>
    <child ID="1323"
        label="MDB_BASIC_STATUS_TRANSITION: &#xa;delete draft"
        layerID="1" created="1519306276060" x="-312.1549" y="2381.9048"
        width="283.0" height="46.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FF0000</fillColor>
        <strokeColor>#776D6D</strokeColor>
        <textColor>#FFFFFF</textColor>
        <font>Arial-plain-16</font>
        <URIString>http://vue.tufts.edu/rdf/resource/bdb92be8c0a8b2570088755b2f3e0258</URIString>
        <shape xsi:type="rectangle"/>
    </child>
    <child ID="1324"
        label="mdbcore: &#xa;'has transition &#xa;to subsequent&#xa;entry status'"
        layerID="1" created="1519306276060" x="-164.56082" y="2081.5215"
        width="664.0371" height="300.8833" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/bdb92be8c0a8b2570088755b6fa65eee</URIString>
        <point1 x="498.9763" y="2084.706"/>
        <point2 x="-164.06082" y="2381.9048"/>
        <ID1 xsi:type="node">465</ID1>
        <ID2 xsi:type="node">1323</ID2>
        <ctrlPoint0 x="-69.44618" y="2051.891" xsi:type="point"/>
    </child>
    <child ID="1325"
        label="mdbcore: &#xa;'transition results in &#xa;subsequent entry status'"
        layerID="1" created="1519306276060" x="-172.5684" y="2427.4048"
        width="699.88306" height="514.6936" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/bdb92be8c0a8b2570088755be08d1990</URIString>
        <point1 x="-171.55446" y="2427.9048"/>
        <point2 x="526.81464" y="2941.5984"/>
        <ID1 xsi:type="node">1323</ID1>
        <ID2 xsi:type="node">1286</ID2>
        <ctrlPoint0 x="-191.30676" y="2932.943" xsi:type="point"/>
    </child>
    <child ID="1328"
        label="MDB_BASIC_STATUS_TRANSITION:&#xa;create new version"
        layerID="1" created="1519306337977" x="963.6295" y="2320.0728"
        width="279.0" height="46.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FF0000</fillColor>
        <strokeColor>#776D6D</strokeColor>
        <textColor>#FFFFFF</textColor>
        <font>Arial-plain-16</font>
        <URIString>http://vue.tufts.edu/rdf/resource/bdb92be9c0a8b2570088755b43231e13</URIString>
        <shape xsi:type="rectangle"/>
    </child>
    <child ID="1329"
        label="mdbcore: &#xa;'has transition &#xa;to subsequent&#xa;entry status'"
        layerID="1" created="1519306337977" x="1242.1295" y="2309.4873"
        width="226.24792" height="66.91748" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/bdb92be9c0a8b2570088755ba713e754</URIString>
        <point1 x="1467.8774" y="2375.9048"/>
        <point2 x="1242.6295" y="2331.4343"/>
        <ID1 xsi:type="node">62</ID1>
        <ID2 xsi:type="node">1328</ID2>
        <ctrlPoint0 x="1316.0919" y="2325.3054" xsi:type="point"/>
    </child>
    <child ID="1330"
        label="mdbcore: &#xa;'transition results in &#xa;subsequent entry status'"
        layerID="1" created="1519306337977" x="710.4913" y="2339.7446"
        width="253.63824" height="50.257812" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/bdb92be9c0a8b2570088755b594ed252</URIString>
        <point1 x="963.6295" y="2351.5254"/>
        <point2 x="710.9913" y="2389.5024"/>
        <ID1 xsi:type="node">1328</ID1>
        <ID2 xsi:type="node">59</ID2>
        <ctrlPoint0 x="923.197" y="2353.9753" xsi:type="point"/>
    </child>
    <child ID="1331" label="entry status:&#xa;EARLIER PUBLISHED"
        layerID="1" created="1519306398151" x="1443.3706" y="2538.0134"
        width="223.0" height="58.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#30D643</fillColor>
        <strokeColor>#776D6D</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-21</font>
        <URIString>http://vue.tufts.edu/rdf/resource/bdb92be9c0a8b2570088755bd83c2b60</URIString>
        <shape xsi:type="rectangle"/>
    </child>
    <child ID="1332"
        label="mdbcore: &#xa;'transition results in &#xa;subsequent entry status'"
        layerID="1" created="1519306402142" x="1190.5796" y="2495.6523"
        width="253.29102" height="58.759277" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#0000FF</strokeColor>
        <textColor>#0000FF</textColor>
        <font>Arial-bold-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/bdb92be9c0a8b2570088755b1431d6ea</URIString>
        <point1 x="1191.0796" y="2496.1523"/>
        <point2 x="1443.3706" y="2553.9116"/>
        <ID1 xsi:type="node">149</ID1>
        <ID2 xsi:type="node">1331</ID2>
        <ctrlPoint0 x="1303.8501" y="2537.517" xsi:type="point"/>
    </child>
    <layer ID="1" label="Layer 1" created="1419753572415" x="0.0"
        y="0.0" width="1.4E-45" height="1.4E-45" strokeWidth="0.0" autoSized="false">
        <URIString>http://vue.tufts.edu/rdf/resource/8fefdf2dc0a8b21f006bc4d76f7476a8</URIString>
    </layer>
    <userZoom>1.0</userZoom>
    <userOrigin x="-369.72012" y="1921.7238"/>
    <presentationBackground>#202020</presentationBackground>
    <PathwayList currentPathway="0" revealerIndex="-1">
        <pathway ID="0" label="Unbenannter Pfad" created="1419753572415"
            x="0.0" y="0.0" width="1.4E-45" height="1.4E-45"
            strokeWidth="0.0" autoSized="false" currentIndex="0" open="true">
            <strokeColor>#B3CC33CC</strokeColor>
            <textColor>#000000</textColor>
            <font>SansSerif-plain-14</font>
            <URIString>http://vue.tufts.edu/rdf/resource/8fefdf2dc0a8b21f006bc4d71c1b455c</URIString>
            <masterSlide ID="2" created="1419753572495" x="0.0" y="0.0"
                width="800.0" height="600.0" locked="true"
                strokeWidth="0.0" autoSized="false">
                <fillColor>#000000</fillColor>
                <strokeColor>#404040</strokeColor>
                <textColor>#000000</textColor>
                <font>SansSerif-plain-14</font>
                <URIString>http://vue.tufts.edu/rdf/resource/8fefdf2dc0a8b21f006bc4d7b9cb8b04</URIString>
                <titleStyle ID="3" label="Header"
                    created="1419753572625" x="335.5" y="172.5"
                    width="129.0" height="55.0" strokeWidth="0.0"
                    autoSized="true" isStyle="true" xsi:type="node">
                    <strokeColor>#404040</strokeColor>
                    <textColor>#FFFFFF</textColor>
                    <font>Gill Sans-plain-36</font>
                    <URIString>http://vue.tufts.edu/rdf/resource/8fefdf2dc0a8b21f006bc4d7dc0abdff</URIString>
                    <shape xsi:type="rectangle"/>
                </titleStyle>
                <textStyle ID="4" label="Slide Text"
                    created="1419753572625" x="346.5" y="281.5"
                    width="107.0" height="37.0" strokeWidth="0.0"
                    autoSized="true" isStyle="true" xsi:type="node">
                    <strokeColor>#404040</strokeColor>
                    <textColor>#FFFFFF</textColor>
                    <font>Gill Sans-plain-22</font>
                    <URIString>http://vue.tufts.edu/rdf/resource/8fefdf2dc0a8b21f006bc4d77ea53348</URIString>
                    <shape xsi:type="rectangle"/>
                </textStyle>
                <linkStyle ID="5" label="Links" created="1419753572625"
                    x="373.5" y="384.0" width="53.0" height="32.0"
                    strokeWidth="0.0" autoSized="true" isStyle="true" xsi:type="node">
                    <strokeColor>#404040</strokeColor>
                    <textColor>#B3BFE3</textColor>
                    <font>Gill Sans-plain-18</font>
                    <URIString>http://vue.tufts.edu/rdf/resource/8fefdf2dc0a8b21f006bc4d7a00d3285</URIString>
                    <shape xsi:type="rectangle"/>
                </linkStyle>
            </masterSlide>
        </pathway>
    </PathwayList>
    <date>2014-12-28</date>
    <modelVersion>6</modelVersion>
    <saveLocation>D:\Git_Box\vue-files</saveLocation>
    <saveFile>D:\Git_Box\vue-files\Data_Entry_Life_Cycle.vue</saveFile>
</LW-MAP>
