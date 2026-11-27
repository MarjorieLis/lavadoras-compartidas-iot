<?xml version="1.0" encoding="UTF-8"?><project name="Sistema IoT de lavadoras compartidas." company="Universidad Internacional del Ecuador (UIDE)" webLink="http://" view-date="2026-11-09" view-index="0" gantt-divider-location="446" resource-divider-location="300" version="3.3.3323" locale="es_ES">
    <description><![CDATA[Planificación del desarrollo de un sistema IoT para gestionar el uso de lavadoras compartidas en viviendas estudiantiles de Loja. Incluye un dispositivo ESP32, una plataforma web, pagos de prueba, comunicación MQTT y registro de ciclos de lavado.]]></description>
    <view zooming-state="default:7" id="gantt-chart">
        <field id="tpd15" name="Notas" width="20" order="-1"/>
        <field id="tpd3" name="Nombre" width="244" order="0"/>
        <field id="tpd4" name="Fecha de inicio" width="92" order="1"/>
        <field id="tpd5" name="Fecha de fin" width="94" order="2"/>
        <option id="filter.completedTasks" value="false"/>
        <option id="filter.dueTodayTasks" value="false"/>
        <option id="filter.overdueTasks" value="false"/>
        <option id="filter.inProgressTodayTasks" value="false"/>
        <option id="color.recent"><![CDATA[#cc0033]]></option>
    </view>
    <view id="resource-table">
        <field id="0" name="Nombre" width="210" order="0"/>
        <field id="1" name="Función" width="86" order="1"/>
    </view>
    <!-- -->
    <calendars base-id="Ninguna">
        <day-types>
            <day-type id="0"/>
            <day-type id="1"/>
            <default-week id="1" name="default" sun="1" mon="0" tue="0" wed="0" thu="0" fri="0" sat="1"/>
            <only-show-weekends value="false"/>
            <overriden-day-types/>
            <days/>
        </day-types>
        <date year="2026" month="11" date="19" type="HOLIDAY"><![CDATA[Independencia de Loja]]></date>
        <date year="2026" month="11" date="20" type="HOLIDAY"><![CDATA[Suspensión de jornada - Festival de Artes Vivas]]></date>
        <date year="2026" month="12" date="7" type="HOLIDAY"><![CDATA[Fundación de Loja (trasladado)]]></date>
        <date year="2026" month="12" date="25" type="HOLIDAY"><![CDATA[Navidad]]></date>
        <date year="2027" month="1" date="1" type="HOLIDAY"><![CDATA[Año Nuevo]]></date>
        <date year="2027" month="2" date="8" type="HOLIDAY"><![CDATA[	Carnaval]]></date>
        <date year="2027" month="2" date="10" type="HOLIDAY"><![CDATA[	Carnaval]]></date>
    </calendars>
    <tasks empty-milestones="true">
        <taskproperties>
            <taskproperty id="tpd0" name="type" type="default" valuetype="icon"/>
            <taskproperty id="tpd1" name="priority" type="default" valuetype="icon"/>
            <taskproperty id="tpd2" name="info" type="default" valuetype="icon"/>
            <taskproperty id="tpd3" name="name" type="default" valuetype="text"/>
            <taskproperty id="tpd4" name="begindate" type="default" valuetype="date"/>
            <taskproperty id="tpd5" name="enddate" type="default" valuetype="date"/>
            <taskproperty id="tpd6" name="duration" type="default" valuetype="int"/>
            <taskproperty id="tpd7" name="completion" type="default" valuetype="int"/>
            <taskproperty id="tpd8" name="coordinator" type="default" valuetype="text"/>
            <taskproperty id="tpd9" name="predecessorsr" type="default" valuetype="text"/>
        </taskproperties>
        <task id="0" uid="3dbc6c75d68248b2bb303fdfd0a28619" name="1.1.1 Acta de constitución" color="#cc0033" meeting="false" start="2026-11-09" duration="4" complete="0" expand="true">
            <depend id="1" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="1" uid="cc6d786a3d014dc98265caa3c6f3b508" name="1.1.2 Business Case validado" color="#cc0033" meeting="false" start="2026-11-13" duration="4" complete="0" expand="true">
            <depend id="2" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="2" uid="85213f10732b401194883ffb7930d412" name="1.2.1 Requisitos y criterios" color="#cc0033" meeting="false" start="2026-11-23" duration="6" complete="0" expand="true">
            <depend id="3" type="2" difference="0" hardness="Strong"/>
            <depend id="4" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="3" uid="03e8ba4487dc48cbb73c1dc1aa094819" name="1.2.2 Arquitectura y ADR" color="#cc0033" meeting="false" start="2026-12-01" duration="6" complete="0" expand="true">
            <depend id="5" type="2" difference="0" hardness="Strong"/>
            <depend id="9" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="4" uid="1e014425b5c0458f8e63ce67d4fbd161" name="1.2.3 Plan de pruebas y seguridad" meeting="false" start="2026-12-01" duration="5" complete="0" expand="true">
            <depend id="15" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="5" uid="0481ffc43c474cc3b528545ed2456a3e" name="1.3.1 Simulación ESP32 en Wokwi" meeting="false" start="2026-12-10" duration="8" complete="0" expand="true">
            <depend id="6" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="6" uid="4cbc5e7dfdc64c6b908daa062eb9e872" name="1.3.2 Nodo de medición" meeting="false" start="2026-12-22" duration="8" complete="0" expand="true">
            <depend id="7" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="7" uid="14ba2c7e1cdc48d6b0b212e91e464ebc" name="1.3.3 Control de autorización" meeting="false" start="2027-01-05" duration="7" complete="0" expand="true">
            <depend id="8" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="8" uid="1f1eebf66def448c8ee7c63ab8c6158b" name="1.3.4 Pruebas de cortes y reconexión" meeting="false" start="2027-01-14" duration="6" complete="0" expand="true">
            <depend id="14" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="9" uid="ea0c893d43a94ae385b83990a59ded10" name="1.4.1 Broker Mosquitto configurado" color="#cc0033" meeting="false" start="2026-12-10" duration="5" complete="0" expand="true">
            <depend id="10" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="10" uid="fc2a47270f874349bae67f02881b28d3" name="1.4.2 API y base de datos" color="#cc0033" meeting="false" start="2026-12-17" duration="9" complete="0" expand="true">
            <depend id="11" type="2" difference="0" hardness="Strong"/>
            <depend id="12" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="11" uid="7b4d79bc27a84866ae1c38b95f13d04b" name="1.4.3 Portal web y pago de prueba" color="#cc0033" meeting="false" start="2026-12-31" duration="9" complete="0" expand="true">
            <depend id="13" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="12" uid="8e646ddc916f4c7a9dd22d39790673a2" name="1.4.4 Panel de estado e historial" meeting="false" start="2026-12-31" duration="7" complete="0" expand="true">
            <depend id="13" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="13" uid="f283b90dd1ea46d9a3bdedc5a1d16a3b" name="1.4.5 Conciliación de pagos y ciclos" color="#cc0033" meeting="false" start="2027-01-14" duration="7" complete="0" expand="true">
            <depend id="14" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="14" uid="fe2da398a60e4b84a853d04f94f1afc9" name="1.5.1 Integración extremo a extremo" color="#cc0033" meeting="false" start="2027-01-25" duration="7" complete="0" expand="true">
            <depend id="15" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="15" uid="4edfbe047ac04f1cbe84aa8446779a5e" name="1.5.2 Pruebas de integración y fallas" color="#cc0033" meeting="false" start="2027-02-03" duration="6" complete="0" expand="true">
            <depend id="16" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="16" uid="e582a6b9e0f64f65a9a6902b131ecbde" name="1.5.3 Manual y dossier de cierre" color="#cc0033" meeting="false" start="2027-02-15" duration="5" complete="0" expand="true">
            <depend id="17" type="2" difference="0" hardness="Strong"/>
        </task>
        <task id="17" uid="d26f3a18c0c34128982caea6ee645839" name="H1 Proyecto listo para demostración" meeting="true" start="2027-02-22" duration="0" complete="0" expand="true"/>
        <task id="18" uid="d98d510c93734603bde53b64ce373011" name="H2 Cierre académico del proyecto" meeting="true" start="2027-03-04" duration="0" complete="0" expand="true"/>
    </tasks>
    <resources/>
    <allocations/>
    <vacations/>
    <previous/>
    <roles roleset-name="Default"/>
    <roles roleset-name="SoftwareDevelopment"/>
</project>
