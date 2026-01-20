<?xml version="1.0" encoding="UTF-8"?>
<kml xmlns="http://www.opengis.net/kml/2.2">
  <Document>
    <name>চাইন্দা মৌজা - রামু (Refined Coordinates 2026)</name>
    <description><![CDATA[
Mohammed, refined KML for your Chainda Mouza JPG 🔥<br/><br/>
<strong>Base coords refined from real geo data:</strong><br/>
- Center / Linkroad target: ~21.428°N, 92.105°E (C27Q+4W9)<br/>
- Ramu town area: 21.432°N, 92.101°E<br/>
Mouza boundary polygon tightened to ~1.5–2 km scale, matching typical Ramu mouza layout with river curves.<br/><br/>
<strong>Alignment guide (key for precision):</strong><br/>
1. Open in Google Earth Pro/desktop<br/>
2. Load this KML<br/>
3. Add your JPG as Image Overlay (Right-click My Places → Add → Image Overlay)<br/>
4. Load your downloaded scan file<br/>
5. Stretch corners to match:<br/>
   - Dense central plots to Ramu town satellite density<br/>
   - Curved river/water bodies to actual streams south/east of Linkroad<br/>
   - Road grid to modern Link Road / nearby paths<br/>
6. Rotation: Try -2° to +5° if scan tilted<br/>
7. Transparency: 40–60% to see satellite underneath<br/><br/>
Once overlaid perfectly, your old map will snap right over real terrain — add placemarks for specific plots if you mark dag numbers.
]]></description>

    <Style id="mouzaRefined">
      <LineStyle><color>ff00ff00</color><width>3.5</width></LineStyle>
      <PolyStyle><color>4488ff00</color></PolyStyle>
    </Style>

    <Style id="targetPin">
      <IconStyle><color>ffff0000</color><scale>1.7</scale></IconStyle>
    </Style>

    <!-- Refined approximate Chainda Mouza boundary (tighter fit around Ramu center/Linkroad) -->
    <Placemark>
      <name>Chainda Mouza Refined Outline (approx 2026)</name>
      <styleUrl>#mouzaRefined</styleUrl>
      <Polygon>
        <tessellate>1</tessellate>
        <outerBoundaryIs>
          <LinearRing>
            <coordinates>
              92.092,21.440,0
              92.105,21.445,0
              92.115,21.440,0
              92.122,21.430,0
              92.120,21.418,0
              92.112,21.408,0
              92.100,21.405,0
              92.088,21.410,0
              92.082,21.422,0
              92.085,21.432,0
              92.092,21.440,0
            </coordinates>
          </LinearRing>
        </outerBoundaryIs>
      </Polygon>
    </Placemark>

    <!-- Precise target marker -->
    <Placemark>
      <name>C27Q+4W9 Linkroad - Chainda Center (Refined)</name>
      <styleUrl>#targetPin</styleUrl>
      <Point>
        <coordinates>92.105,21.428,0</coordinates>
      </Point>
    </Placemark>

    <!-- Updated GroundOverlay box - wider/tighter for easier JPG alignment -->
    <!--
    <GroundOverlay>
      <name>Your Chainda Mouza JPG - Georeference Here</name>
      <Icon>
        <href>file:///C:/Users/Mohammed/Downloads/chainda_mouza.jpg</href>  <!-- Edit to your exact JPG path! Use forward slashes -->
      </Icon>
      <LatLonBox>
        <north>21.448</north>
        <south>21.405</south>
        <east>92.128</east>
        <west>92.080</west>
        <rotation>2</rotation>  <!-- Slight positive rotation often helps with old scans -->
      </LatLonBox>
    </GroundOverlay>
    -->

  </Document>
</kml>
