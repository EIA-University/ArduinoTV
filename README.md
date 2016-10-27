# ArduinoTV

<module fritzingVersion="0.9.3b.04.19.5c895d327c44a3114e5fcc9d8260daf0cbb52806">
 <boundingRects>
  <boundingRect name="Vista de Esquemático" rect="414 63.0001 220.388 207.491"/>
  <boundingRect name="Vista de PCB" rect="0 0 0 0"/>
  <boundingRect name="Vista de Protoboard (placa de Prototipos)" rect="0 0 0 0"/>
 </boundingRects>
 <instances>
  <instance modelIndex="5803" path="C:/Users/Pablo Pérez/Documents/Fritzing/fritzing.0.9.3b.64.pc/fritzing-parts/core/arduino_Uno_Rev3(fix).fzp" moduleIdRef="arduino_Uno_Rev3(fix)">
   <title>Componente1</title>
   <views>
    <breadboardView layer="breadboardbreadboard">
     <geometry x="-386.065" z="1.50002" y="18"/>
     <connectors>
      <connector connectorId="connector68" layer="breadboardbreadboard">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
      <connector connectorId="connector57" layer="breadboardbreadboard">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
      <connector connectorId="connector67" layer="breadboardbreadboard">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
     </connectors>
    </breadboardView>
    <pcbView layer="copper0">
     <geometry x="50.1699" z="5.50001" y="9"/>
     <titleGeometry x="293.41" xOffset="243.24" yOffset="-7" z="12.5001" textColor="#000000" visible="true" y="2" fontSize="5">
      <displayKey key=""/>
     </titleGeometry>
     <connectors>
      <connector connectorId="connector68" layer="copper0">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
      <connector connectorId="connector57" layer="copper0">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
      <connector connectorId="connector67" layer="copper0">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
     </connectors>
    </pcbView>
    <schematicView layer="schematic">
     <geometry x="414" z="2.50001" y="63.0001"/>
     <titleGeometry x="549" xOffset="135" yOffset="-7" z="6.50007" textColor="#000000" visible="true" y="56.0001" fontSize="5">
      <displayKey key=""/>
      <displayKey key="part number"/>
     </titleGeometry>
     <connectors>
      <connector connectorId="connector68" layer="schematic">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
      <connector connectorId="connector57" layer="schematic">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
      <connector connectorId="connector67" layer="schematic">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
     </connectors>
    </schematicView>
   </views>
  </instance>
  <instance modelIndex="5806" path="C:/Users/Pablo Pérez/Documents/Fritzing/fritzing.0.9.3b.64.pc/fritzing-parts/core/resistor.fzp" moduleIdRef="ResistorModuleID">
   <property name="tolerance" value="±5%"/>
   <property name="resistance" value="470"/>
   <property name="pin spacing" value="400 mil"/>
   <title>R1</title>
   <views>
    <schematicView layer="schematic">
     <geometry x="593.563" z="2.50002" y="113.13">
      <transform m11="-1" m13="0" m21="0" m12="0" m22="-1" m31="36.875" m23="0" m33="1" m32="7.74"/>
     </geometry>
     <titleGeometry x="627.297" xOffset="33.7336" yOffset="-19.591" z="6.50002" textColor="#000000" visible="true" y="93.5392" fontSize="5">
      <displayKey key=""/>
      <displayKey key="part number"/>
      <displayKey key="resistance"/>
      <displayKey key="power"/>
     </titleGeometry>
     <connectors>
      <connector connectorId="connector1" layer="schematic">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
      <connector connectorId="connector0" layer="schematic">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
     </connectors>
    </schematicView>
    <breadboardView layer="breadboard">
     <geometry x="349.684" z="2.5" y="49.4595"/>
     <connectors>
      <connector connectorId="connector1" layer="breadboard">
       <geometry x="36.0063" y="4.5405"/>
       <leg>
        <point x="0" y="0"/>
        <bezier/>
        <point x="1.3095" y="0"/>
        <bezier/>
       </leg>
       <connects/>
      </connector>
      <connector connectorId="connector0" layer="breadboard">
       <geometry x="2.619" y="4.5405"/>
       <leg>
        <point x="0" y="0"/>
        <bezier/>
        <point x="-1.3095" y="0"/>
        <bezier/>
       </leg>
       <connects/>
      </connector>
     </connectors>
    </breadboardView>
    <pcbView layer="copper0">
     <geometry x="455.625" z="5.50002" y="-12.87">
      <transform m11="0" m13="0" m21="-1" m12="1" m22="0" m31="25.245" m23="0" m33="1" m32="-17.505"/>
     </geometry>
     <titleGeometry x="498.375" xOffset="42.75" yOffset="-7" z="12.5" textColor="#000000" visible="true" y="-19.87" fontSize="5">
      <displayKey key=""/>
     </titleGeometry>
     <connectors>
      <connector connectorId="connector1" layer="copper0">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
      <connector connectorId="connector0" layer="copper0">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
     </connectors>
    </pcbView>
   </views>
  </instance>
  <instance modelIndex="5809" path="C:/Users/Pablo Pérez/Documents/Fritzing/fritzing.0.9.3b.64.pc/fritzing-parts/core/resistor.fzp" moduleIdRef="ResistorModuleID">
   <property name="tolerance" value="±5%"/>
   <property name="resistance" value="1k"/>
   <property name="pin spacing" value="400 mil"/>
   <title>R2</title>
   <views>
    <schematicView layer="schematic">
     <geometry x="593.562" z="2.50003" y="158.13"/>
     <titleGeometry x="630.437" xOffset="36.875" yOffset="-14" z="6.50003" textColor="#000000" visible="true" y="144.13" fontSize="5">
      <displayKey key=""/>
      <displayKey key="part number"/>
      <displayKey key="resistance"/>
      <displayKey key="power"/>
     </titleGeometry>
     <connectors>
      <connector connectorId="connector1" layer="schematic">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
      <connector connectorId="connector0" layer="schematic">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
     </connectors>
    </schematicView>
    <breadboardView layer="breadboard">
     <geometry x="313.684" z="2.50001" y="58.4595"/>
     <connectors>
      <connector connectorId="connector1" layer="breadboard">
       <geometry x="36.0063" y="4.5405"/>
       <leg>
        <point x="0" y="0"/>
        <bezier/>
        <point x="1.3095" y="0"/>
        <bezier/>
       </leg>
       <connects/>
      </connector>
      <connector connectorId="connector0" layer="breadboard">
       <geometry x="2.619" y="4.5405"/>
       <leg>
        <point x="0" y="0"/>
        <bezier/>
        <point x="-1.3095" y="0"/>
        <bezier/>
       </leg>
       <connects/>
      </connector>
     </connectors>
    </breadboardView>
    <pcbView layer="copper0">
     <geometry x="455.625" z="5.50003" y="23.13">
      <transform m11="0" m13="0" m21="-1" m12="1" m22="0" m31="25.245" m23="0" m33="1" m32="-17.505"/>
     </geometry>
     <titleGeometry x="498.375" xOffset="42.75" yOffset="-7" z="12.5" textColor="#000000" visible="true" y="16.13" fontSize="5">
      <displayKey key=""/>
     </titleGeometry>
     <connectors>
      <connector connectorId="connector1" layer="copper0">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
      <connector connectorId="connector0" layer="copper0">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
     </connectors>
    </pcbView>
   </views>
  </instance>
  <instance modelIndex="85411518" path="C:/Users/Pablo Pérez/Documents/Fritzing/fritzing.0.9.3b.64.pc/fritzing-parts/core/sparkfun-connectors-rca--lock.fzp" moduleIdRef="SparkFun-Connectors-RCA--LOCK">
   <title>JP1</title>
   <views>
    <breadboardView layer="breadboard">
     <geometry x="325.659" z="2.50004" y="328.5"/>
     <connectors>
      <connector connectorId="connector2" layer="breadboard">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
      <connector connectorId="connector0" layer="breadboard">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
     </connectors>
    </breadboardView>
    <schematicView layer="schematic">
     <geometry x="600.064" z="2.50004" y="236.167">
      <transform m11="0" m13="0" m21="-1" m12="1" m22="0" m31="34.3237" m23="0" m33="1" m32="-11.4362"/>
     </geometry>
     <titleGeometry x="645.824" xOffset="45.76" yOffset="-7" z="6.50006" textColor="#000000" visible="true" y="229.167" fontSize="5">
      <displayKey key=""/>
      <displayKey key="part number"/>
     </titleGeometry>
     <connectors>
      <connector connectorId="connector2" layer="schematic">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
      <connector connectorId="connector0" layer="schematic">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
     </connectors>
    </schematicView>
    <pcbView layer="copper0">
     <geometry x="375.955" z="5.50006" y="39.6007"/>
     <titleGeometry x="411.631" xOffset="35.6755" yOffset="-7" z="12.5001" textColor="#000000" visible="true" y="32.6007" fontSize="5">
      <displayKey key=""/>
     </titleGeometry>
     <connectors>
      <connector connectorId="connector2" layer="copper0">
       <geometry x="0" y="0"/>
       <connects/>
      </connector>
     </connectors>
    </pcbView>
   </views>
  </instance>
 </instances>
</module>
