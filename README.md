# Microservices Project


<mxfile host="app.diagrams.net" modified="2023-03-16T11:38:01.473Z" agent="5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/111.0.0.0 Safari/537.36" etag="AODnAF2k-piNWdJKipuG" version="21.0.2" type="github">
  <diagram name="Page-1" id="JiT-n5hTNIKeEeXN8N33">
    <mxGraphModel dx="1060" dy="616" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-2" value="" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="270" y="10" width="550" height="510" as="geometry" />
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-3" value="NOTIFICATION&lt;br&gt;SERVICE" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="700" y="140" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-4" value="INVENTORY&lt;br&gt;SERVICE" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="700" y="300" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-5" value="ORDER&lt;br&gt;SERVICE" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="450" y="240" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-6" value="PRODUCT&lt;br&gt;SERVICE" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="370" y="120" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-7" value="API-GATEWAY" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="210" y="240" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-8" value="AUTH&lt;br&gt;SERVER" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="210" y="370" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-9" value="" style="endArrow=classic;html=1;rounded=0;exitX=0.5;exitY=0;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="-hNmh7Jd-VyB_i2p71Io-7" target="-hNmh7Jd-VyB_i2p71Io-6">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="390" y="310" as="sourcePoint" />
            <mxPoint x="440" y="260" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-11" value="" style="endArrow=classic;html=1;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="-hNmh7Jd-VyB_i2p71Io-7" target="-hNmh7Jd-VyB_i2p71Io-5">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="390" y="310" as="sourcePoint" />
            <mxPoint x="440" y="260" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-12" value="" style="endArrow=classic;html=1;rounded=0;entryX=0;entryY=0.75;entryDx=0;entryDy=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="-hNmh7Jd-VyB_i2p71Io-5" target="-hNmh7Jd-VyB_i2p71Io-3">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="390" y="310" as="sourcePoint" />
            <mxPoint x="440" y="260" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-13" value="" style="endArrow=classic;html=1;rounded=0;" edge="1" parent="1" target="-hNmh7Jd-VyB_i2p71Io-4">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="570" y="270" as="sourcePoint" />
            <mxPoint x="660" y="225" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-14" value="MySQL" style="shape=cylinder3;whiteSpace=wrap;html=1;boundedLbl=1;backgroundOutline=1;size=15;" vertex="1" parent="1">
          <mxGeometry x="460" y="350" width="60" height="80" as="geometry" />
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-15" value="" style="endArrow=classic;startArrow=classic;html=1;rounded=0;entryX=0.356;entryY=0.983;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1" source="-hNmh7Jd-VyB_i2p71Io-14" target="-hNmh7Jd-VyB_i2p71Io-5">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="390" y="310" as="sourcePoint" />
            <mxPoint x="440" y="260" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-16" value="MySQL" style="shape=cylinder3;whiteSpace=wrap;html=1;boundedLbl=1;backgroundOutline=1;size=15;" vertex="1" parent="1">
          <mxGeometry x="730" y="420" width="60" height="80" as="geometry" />
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-17" value="&lt;font style=&quot;font-size: 10px;&quot;&gt;MONGODB&lt;/font&gt;" style="shape=cylinder3;whiteSpace=wrap;html=1;boundedLbl=1;backgroundOutline=1;size=15;" vertex="1" parent="1">
          <mxGeometry x="390" y="20" width="60" height="80" as="geometry" />
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-18" value="" style="endArrow=classic;startArrow=classic;html=1;rounded=0;" edge="1" parent="1" source="-hNmh7Jd-VyB_i2p71Io-16" target="-hNmh7Jd-VyB_i2p71Io-4">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="720" y="401" as="sourcePoint" />
            <mxPoint x="722" y="350" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-19" value="" style="endArrow=classic;startArrow=classic;html=1;rounded=0;entryX=0.356;entryY=0.983;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="419" y="131" as="sourcePoint" />
            <mxPoint x="421" y="80" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-20" value="" style="endArrow=classic;startArrow=classic;html=1;rounded=0;entryX=0.356;entryY=0.983;entryDx=0;entryDy=0;entryPerimeter=0;exitX=0.421;exitY=-0.017;exitDx=0;exitDy=0;exitPerimeter=0;" edge="1" parent="1" source="-hNmh7Jd-VyB_i2p71Io-8">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="260" y="341" as="sourcePoint" />
            <mxPoint x="262" y="290" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-21" value="ASYNC&lt;br&gt;COMMUNICATION" style="text;html=1;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;rotation=-35;" vertex="1" parent="1">
          <mxGeometry x="580" y="170" width="100" height="30" as="geometry" />
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-22" value="SYNC&lt;br&gt;COMMUNICATION" style="text;html=1;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;rotation=20;" vertex="1" parent="1">
          <mxGeometry x="580" y="300" width="119.1" height="30" as="geometry" />
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-23" value="Actor" style="shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;outlineConnect=0;" vertex="1" parent="1">
          <mxGeometry x="20" y="240" width="30" height="60" as="geometry" />
        </mxCell>
        <mxCell id="-hNmh7Jd-VyB_i2p71Io-24" value="" style="endArrow=classic;startArrow=classic;html=1;rounded=0;exitX=0.5;exitY=0.5;exitDx=0;exitDy=0;exitPerimeter=0;" edge="1" parent="1" source="-hNmh7Jd-VyB_i2p71Io-23" target="-hNmh7Jd-VyB_i2p71Io-7">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="390" y="300" as="sourcePoint" />
            <mxPoint x="440" y="250" as="targetPoint" />
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
