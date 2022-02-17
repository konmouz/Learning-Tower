# Learning tower v1
Learning tower for kids made of an IKEA step stool, aluminium extrusions and 3d printing

<p align="center">
  <img src="./output/images/model-rotation.gif" width="400">
</p>

## Preparation

### Ordering components - BoM

I have included an example online source for every part but based on your location you need to do some research and find relevant suppliers. Aluminium extrusions are widely spread and there are plenty of online shops that ship the extrusions pre-cut at your desired length. There are many ways to connect the extrusions, I chose the corner connectors because they are cheap, discreet, easy to source, easy to install.

| Name | Quantity | Photo |
|-|-|-|
| [IKEA Bekvaem step stool](https://www.ikea.com/gb/en/p/bekvaem-step-stool-aspen-10225589/) | 1 | <img src="./output/images/Bekvaem.png" width="250"> |
| [Aluminium extrusion - 20x20 x L **430** mm](https://www.framingtech.com/20-x-20-20x203m) | 4 | <img src="./output/images/2020.jpg" width="250"> |
| [Aluminium extrusion - 20x20 x L **397** mm](https://www.framingtech.com/20-x-20-20x203m) | 2 | <img src="./output/images/2020.jpg" width="250"> |
| [Aluminium extrusion - 20x20 x L **363** mm](https://www.framingtech.com/20-x-20-20x203m) | 1 | <img src="./output/images/2020.jpg" width="250"> |
| [Aluminium extrusion - 20x20 x L **242** mm](https://www.framingtech.com/20-x-20-20x203m) | 2 | <img src="./output/images/2020.jpg" width="250"> |
| [Aluminium extrusion - 20x20 x L **202** mm](https://www.framingtech.com/20-x-20-20x203m) | 2 | <img src="./output/images/2020.jpg" width="250"> |
| [Inside corner connector 2020](https://www.amazon.com/uxcell-Interior-Connector-Aluminum-Extrusion/dp/B07VP59DY5/ref=psdc_16412271_t2_B071LPFZM2) | 14 | <img src="./output/images/corner-connector.jpg" width="250"> |
| [countersunk wood screw - 5x60cm (or longer)](https://www.amazon.com/Phillips-Drilling-Stainless-Drywall-Screws/dp/B07M7S6N4V/ref=sr_1_4?crid=2J7ESKXZ3AXOZ&keywords=wood%2Bscrew%2B5x60&qid=1644572210&sprefix=wood%2Bscrew%2B5x6%2Caps%2C168&sr=8-4&th=1) | 4 | <img src="./output/images/screw.jpg" width="250"> |


### 3D printing

You need to print (or order [online](https://www.hubs.com/)) the following parts:

| Name | Quantity | Photo |
|-|-|-|
| [End Cap - 3D printed](./output/STL/End-Cap.stl) | 4 | <img src="./output/images/end-cap.png" width="250"> |
| [Adapter F-L - 3D printed](./output/STL/Adapter-F-L.stl) | 1 | <img src="./output/images/F-L.png" width="250"> |
| [Adapter B-L - 3D printed](./output/STL/Adapter-B-L.stl) | 1 | <img src="./output/images/B-L.png" width="250"> |
| [Adapter F-R - 3D printed](./output/STL/Adapter-F-R.stl) | 1 | <img src="./output/images/F-R.png" width="250"> |
| [Adapter B-R - 3D printed](./output/STL/Adapter-B-R.stl) | 1 | <img src="./output/images/B-R.png" width="250"> |
| [Assembly Jig - 3D printed](./output/STL/Assembly-Jig.stl) | 1 | <img src="./output/images/assembly-jig.png" width="250"> |

Printing settings

- Infill: 70%
- Wall thickness/ Perimeters: 4
- Top and bottom layers: 6
- Material: PLA is ok but you could use more advanced materials like PETG
- Support: Support is not required apart from the Assembly Jig

Notes

- For safety reasons, I cranked the printing values up to make sure I get parts that can withstand stress
- It's a good idea to print a sample Adapter and test how strong it is. The Adapters support the whole structure so not having reliable parts defeats the purpose of the project.


### Smoothing edges
Aluminium extrusion's edges are usually rough and potentially dangerous so I strongly recommend smoothing all edges with a file or sandpaper.

<p align="center">
  <img src="./output/images/LT001.jpg" width="400">
</p>

###  Aluminium extrusions by length (L)
Lay down all the extrusions by length, this will make assembly way easier

<p align="center">
  <img src="./output/images/LT002.jpg" width="400">
</p>

### Tools
| Name | Photo |
|-|-|
| Phillips screwdriver | <img src="./output/images/screwdriver.jpg" width="250"> |
| Allen key 2.5mm | <img src="./output/images/allen-set.jpg" width="250"> |
| Allen key 4mm | <img src="./output/images/allen-set.jpg" width="250"> |
| Tape measure | <img src="./output/images/tape-measure.jpg" width="250"> |
| Pencil | <img src="./output/images/pencil.jpg" width="250"> |

## Assembly

#### 1. Assemble the step stool following IKEA's instructions

#### 2. Remove the 4 screws of the step stool that are located near the top
<p align="center">
  <img src="./output/images/LT007.jpg" width="400">
</p>

#### 3. Use the screws you removed to secure the `Adapters` in place, make sure the `Adapters` are installed in the correct location
- Every adapter has a letter combination marking (F for front, B for back, R for right, L for Left)
- Do not fully tighten the screws
<p align="center">
  <img src="./output/images/F-L-2.png" width="400">
</p>
<p align="center">
  <img src="./output/images/LT008.jpg" width="400">
</p>
<p align="center">
  <img src="./output/images/LT009.jpg" width="400">
</p>
<p align="center">
  <img src="./output/images/LT010.jpg" width="400">
</p>
<p align="center">
  <img src="./output/images/orthographic01.jpg" width="200">
</p>

#### 4. Insert an `L 430mm` extrusion to one of the `Adapters` at the back, make sure it is fully inserted
<p align="center">
  <img src="./output/images/LT011.jpg" width="400">
</p>
<p align="center">
  <img src="./output/images/orthographic02.jpg" width="200">
</p>

#### 5. Insert another `L 430mm` extrusion to the opposite `Adapter` at the back, make sure it is fully inserted
<p align="center">
  <img src="./output/images/LT012.jpg" width="400">
</p>
<p align="center">
  <img src="./output/images/orthographic03.jpg" width="200">
</p>

#### 6. Insert two corner connectors to the extrusions you just installed
- The corner connectors should point towards the front side
<p align="center">
  <img src="./output/images/LT013.jpg" width="400">
</p>

#### 7. Insert an `L 363mm` extrusion using two corner connectors
- Push the extrusion all the way downwards but don't tighten the connector yet
<p align="center">
  <img src="./output/images/LT014.jpg" width="400">
</p>
<p align="center">
  <img src="./output/images/orthographic04.jpg" width="200">
</p>

#### 8. Insert an `End Cap` to one end of an `L 397mm` extrusion and press it all the way in
- You might need to hammer it lightly
<p align="center">
  <img src="./output/images/LT003.jpg" width="400">
</p>

#### 9. On the other end of the same extrusion, insert 4 corner connector as in the picture below and then insert an `End Cap` to lock that end
- Pay close attention to the direction and location of each corner connector
<p align="center">
  <img src="./output/images/LT005.jpg" width="400">
</p>

#### 10. Repeat the previous two steps with the other `L 397mm` extrusion, this time insert only 2 corner connector as in the picture below
<p align="center">
  <img src="./output/images/LT006.jpg" width="400">
</p>

#### 11. Insert the `L 397mm` extrusion with the 4 corner connectors
- Pay close attention to the direction of each corner connector
<p align="center">
  <img src="./output/images/LT015.jpg" width="400">
</p>
<p align="center">
  <img src="./output/images/orthographic05.jpg" width="200">
</p>

#### 12. Use the `Assembly Jig` to align the extrusions and tighten the corner connector
- Spend some time to fasten the connector gradually, this will give you a better alignment
<p align="center">
  <img src="./output/images/LT016.jpg" width="400">
</p>

#### 13. Repeat the previous step for the opposite corner

#### 14. Using the tape measure, put a pencil mark at around 20cm from the top extrusion, do this on both sides
<p align="center">
  <img src="./output/images/LT017.jpg" width="400">
</p>

#### 15. Lift the `L 363mm` extrusion and align it with the pencil mark, use the `Jig` to align the extrusions and tighten the corner connector
<p align="center">
  <img src="./output/images/LT018.jpg" width="400">
</p>
<p align="center">
  <img src="./output/images/orthographic06.jpg" width="200">
</p>

#### 16. Insert the two remaining `L 430mm` extrusions to the Adapters at the front
<p align="center">
  <img src="./output/images/LT019.jpg" width="400">
</p>
<p align="center">
  <img src="./output/images/orthographic07.jpg" width="200">
</p>
<p align="center">
  <img src="./output/images/orthographic08.jpg" width="200">
</p>

#### 17. Insert an `L 202mm` extrusion on one of the stool sides. You need to use the corner connector you inserted earlier on the `L 430mm` extrusion, plus a new one on the other side. Do not tighten the connectors yet.
<p align="center">
  <img src="./output/images/LT020.jpg" width="400">
</p>
<p align="center">
  <img src="./output/images/orthographic09.jpg" width="200">
</p>

#### 18. Repeat the previous step on the opposite side with the remaining `L 202mm` extrusion
<p align="center">
  <img src="./output/images/orthographic10.jpg" width="200">
</p>

#### 19. Insert an `L 242mm` extrusion on one of the stool sides. You need to use the corner connector you inserted earlier on the `L 397mm` extrusion, plus a new one on the other side. Do not tighten the connectors yet.
- Pay attention to the orientation of the corner connectors
<p align="center">
  <img src="./output/images/LT021.jpg" width="400">
</p>
<p align="center">
  <img src="./output/images/orthographic11.jpg" width="200">
</p>

#### 20. Repeat the previous step on the opposite side with the remaining `L 242mm` extrusion
<p align="center">
  <img src="./output/images/orthographic12.jpg" width="200">
</p>

#### 21. Use the `Assembly Jig` to align the `L 242mm` to the `L 397mm` extrusion and tighten the corner connector
<p align="center">
  <img src="./output/images/LT022.jpg" width="400">
</p>

#### 22. Using the tape measure, put a pencil mark on the `L 430mm` extrusion at around 20cm from the top of the `L 242mm` extrusion, do this on both sides
<p align="center">
  <img src="./output/images/LT023.jpg" width="400">
</p>

#### 23. Use the `Assembly Jig` to align the `L 202mm` to the `L 430mm` extrusion and tighten both corner connectors, do this on both sides
<p align="center">
  <img src="./output/images/LT024.jpg" width="400">
</p>
<p align="center">
  <img src="./output/images/orthographic13.jpg" width="200">
</p>
<p align="center">
  <img src="./output/images/orthographic14.jpg" width="200">
</p>

#### 24. Now go back and tighten the remaining corner connector of the `L 430mm` and `L 242mm` extrusions, do this on both sides
<p align="center">
  <img src="./output/images/LT025.jpg" width="400">
</p>
<p align="center">
  <img src="./output/images/LT026.jpg" width="400">
</p>

#### 25. Insert the last extrusion, `L 397mm` (with 2 corner connectors), to the `L 242mm` extrusions. Tighten both corner connectors.
<p align="center">
  <img src="./output/images/LT027.jpg" width="400">
</p>
<p align="center">
  <img src="./output/images/orthographic15.jpg" width="200">
</p>

#### 26. Insert the 4 wood screws to the the bottom of the 4 `Adapters`, so that the screw secure the `L 430mm` extrusions. Do not overtighten these screws.
- Important note: using wood screws on extrusions is a bit unusual. The center hole on the extrusion is meant to be tapped so it can accept a standard bolt, something like an M6 in this case. This would however require some more advanced tooling, like an M6 tap (feel free to go down that path if you fancy), so I decided to stick to a screw that is easy to install. A 5mm (diameter) wood screw fits nicely on my extrusion profile, and its length provides enough grip for the threads. However, the diameter of the extrusion's center hole varies slightly from manufacturer to manufacturer, so I highly recommend a testing the screws before assembly and making an effort to find a screw that fastens securely.
<p align="center">
  <img src="./output/images/LT028.jpg" width="400">
</p>

#### 27. Tighten the 4 screws that secure the `Adapters` to the step stool
<p align="center">
  <img src="./output/images/LT029.jpg" width="400">
</p>

#### 28. Enjoy your build!
<p align="center">
  <img src="./output/images/LT030.jpg" width="400">
</p>
