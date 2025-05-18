# Pod2.LUIT.ServerlessArchitecture
Serverless Architecture in XML 

<mxfile version="21.6.8" etag="L9s9K-k9_iI-KxN-vPjW" type="device">
  <io>
    <config>
      <export>
        <format id="svg">
          <add-shadow value="false"/>
          <page-size id="a4"/>
        </format>
      </export>
    </config>
  </io>
  <diagram id="u5e9K_cCOKhp5r86j6-i" name="Page-1">
    <mxGraphModel etag="mnr7j-q88-jhzvYvKz4S" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="850" pageHeight="1100" math="0" shadow="0">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>
        <mxCell id="2" value="User/Client" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="40" y="160" width="80" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="3" value="Route 53" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#60a917;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="160" y="160" width="80" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="4" value="CloudFront" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#008ec2;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="280" y="160" width="80" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="5" value="S3 (Static Website)" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#f59e0b;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="400" y="160" width="120" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="6" value="API Gateway" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#e67d00;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="280" y="240" width="80" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="7" value="Lambda (User Interaction)" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#b45f06;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="400" y="240" width="120" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="8" value="DynamoDB (User Data)" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#4a148c;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="560" y="240" width="120" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="9" value="CodeCommit" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#1a5235;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="160" y="360" width="80" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="10" value="CodeBuild" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#1a5235;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="280" y="360" width="80" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="11" value="CodePipeline" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#1a5235;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="400" y="360" width="80" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="12" value="Approval Process" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#1a5235;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="520" y="360" width="100" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="13" value="IAM Role/Policies" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#8e24aa;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="160" y="440" width="100" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="14" value="S3 Bucket Policies" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#8e24aa;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="280" y="440" width="100" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="15" value="CloudWatch Logs" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#43a047;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="400" y="440" width="100" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="16" value="1. User requests website" style="text;html=1;align=left;verticalAlign=top;whiteSpace=wrap;overflow=hidden;" vertex="1" parent="1">
          <mxGeometry x="160" y="120" width="140" height="30" as="geometry"/>
        </mxCell>
        <mxCell id="17" value="2. Route 53 resolves to CloudFront" style="text;html=1;align=left;verticalAlign=top;whiteSpace=wrap;overflow=hidden;" vertex="1" parent="1">
          <mxGeometry x="280" y="120" width="180" height="30" as="geometry"/>
        </mxCell>
        <mxCell id="18" value="3. CloudFront delivers static content" style="text;html=1;align=left;verticalAlign=top;whiteSpace=wrap;overflow=hidden;" vertex="1" parent="1">
          <mxGeometry x="400" y="120" width="180" height="30" as="geometry"/>
        </mxCell>
        <mxCell id="19" value="4. User interaction via API" style="text;html=1;align=left;verticalAlign=top;whiteSpace=wrap;overflow=hidden;" vertex="1" parent="1">
          <mxGeometry x="280" y="200" width="140" height="30" as="geometry"/>
        </mxCell>
        <mxCell id="20" value="5. Lambda processes interaction" style="text;html=1;align=left;verticalAlign=top;whiteSpace=wrap;overflow=hidden;" vertex="1" parent="1">
          <mxGeometry x="400" y="200" width="160" height="30" as="geometry"/>
        </mxCell>
        <mxCell id="21" value="6. Data stored in DynamoDB" style="text;html=1;align=left;verticalAlign=top;whiteSpace=wrap;overflow=hidden;" vertex="1" parent="1">
          <mxGeometry x="560" y="200" width="140" height="30" as="geometry"/>
        </mxCell>
        <mxCell id="22" value="7. Code Commit" style="text;html=1;align=left;verticalAlign=top;whiteSpace=wrap;overflow=hidden;" vertex="1" parent="1">
          <mxGeometry x="160" y="320" width="140" height="30" as="geometry"/>
        </mxCell>
        <mxCell id="23" value="8. Code Build" style="text;html=1;align=left;verticalAlign=top;whiteSpace=wrap;overflow=hidden;" vertex="1" parent="1">
          <mxGeometry x="280" y="320" width="140" height="30" as="geometry"/>
        </mxCell>
        <mxCell id="24" value="9. Code Pipeline" style="text;html=1;align=left;verticalAlign=top;whiteSpace=wrap;overflow=hidden;" vertex="1" parent="1">
          <mxGeometry x="400" y="320" width="140" height="30" as="geometry"/>
        </mxCell>
        <mxCell id="25" value="10. Approval Process" style="text;html=1;align=left;verticalAlign=top;whiteSpace=wrap;overflow=hidden;" vertex="1" parent="1">
          <mxGeometry x="520" y="320" width="140" height="30" as="geometry"/>
        </mxCell>
        <mxCell id="26" value="11. IAM Roles" style="text;html=1;align=left;verticalAlign=top;whiteSpace=wrap;overflow=hidden;" vertex="1" parent="1">
          <mxGeometry x="160" y="400" width="140" height="30" as="geometry"/>
        </mxCell>
        <mxCell id="27" value="12. S3 Policies" style="text;html=1;align=left;verticalAlign=top;whiteSpace=wrap;overflow=hidden;" vertex="1" parent="1">
          <mxGeometry x="280" y="400" width="140" height="30" as="geometry"/>
        </mxCell>
        <mxCell id="28" value="13. CloudWatch Logs" style="text;html=1;align=left;verticalAlign=top;whiteSpace=wrap;overflow=hidden;" vertex="1" parent="1">
          <mxGeometry x="400" y="400" width="140" height="30" as="geometry"/>
        </mxCell>
        <mxCell id="29" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="2" target="3">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="30" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="3" target="4">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="31" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="4" target="5">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="32" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="4" target="6">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="33" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="6" target="7">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="34" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="7" target="8">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="35" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="9" target="10">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="36" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="10" target="11">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="37" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="11" target="12">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="38" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;exitX=0;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="11" target="5">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="39" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="9" target="13">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="40" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="14" target="5">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="41" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="10" target="15">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
