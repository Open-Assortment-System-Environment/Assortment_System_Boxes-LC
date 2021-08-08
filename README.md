[0]: https://github.com/tobiasfalk/Assortment_System_Main_Page/blob/master/README.md
[1]: ./img/70x70x40.png
[2]: ./img/70x210x40.png

# __Boxes-LC__  

## __Progrs Marking__
The boxes and box parts are designed for the assortment system.    
The Boxes and box parts are designed to be cut with an lasercutter.

${hight}<span style="color:red">✘</span> ->  nothing or only some parts  
${hight}**<span style="color:blue">≈</span>** -> Partly done(work in progres)
${hight}<span style="color:green">✔</span> -> design done  
${hight}<span style="color:green">✔✔</span> -> design and documentation done  
${hight}<span style="color:green">✔✔✔</span> -> design, documentation and dxf export done

## __Labeling__
The labels meant to use are either 64mmx19mm or 63.5mmx38.1mm
### __Links:__
#### __64mmx19mm:__  
a) https://www.amazon.de/Dymo-1933085-Hochleistungs-industrieetiketten-LabelWriter-Etikettendrucker-450-Etiketten/dp/B01M0TKI1U/ref=sr_1_2?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=labelwriter+hochleistungs-etiketten+19mm+x+64mm&qid=1620141590&sr=8-2  
b) https://www.dymo.com/de_DE/lw-durable-labels-19-mm-x-64-mm.html  
#### __63.5mmx38.1mm:__  
a) https://www.amazon.de/Herma-4904-Laser-Glossy-Papier-bedruckbar-selbstklebend/dp/B000KJRDI8/ref=sr_1_3?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=Rechteckige+Etiketten%2C+63%2C5+x+38%2C1+mm&qid=1620134258&sr=8-3  
b) https://www.amazon.de/Universal-Adress-Etiketten-Briefumschl%C3%A4ge-Adressetiketten-abgerundete/dp/B07QWF9TVL/ref=sr_1_12?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=Rechteckige+Etiketten%2C+63%2C5+x+38%2C1+mm&qid=1620134258&sr=8-12  
c) https://www.avery-zweckform.com/blanko-etiketten/rechteckig-64x38-mm

With the 63.5mmx38.1mm, the labels are folded around the edge of the top part and the front(wallA) part. After that an cut out needs to be made where the indent for the stacked box is. On the lable it self is a line that indecats the it needs to be folded.

## __Naming__
### __Filename__
%{peace}\_%{width}x%{depth}x%{hight}  
peace:  

1) box      -> is the hole assembly of the box

2) top ->is the top peace, this hold's the description what is in the box

3) bottom -> is the flor of the box

4) wallA -> is the front wall in with the top peace is connected

5) wallB -> is the back peace

6) wallC -> is the side peace

### __Id__
box\_%{box\_type}\_%{type}\_%{peace}\_%{width}x%{depth}x%{hight}  

box\_type:

1) [standard](##Standard) -> are normal boxes

2) [reel](##Reel) -> are designed to hold reels with parts

3) [battery-AA](###AA) -> are designed to hold AA batter's

4) [battery-AAA](###AAA) -> are designed to hold AAA batter's

3) [battery-9v-block](###9V-Block) -> are designed to hold AA batter's  

type:

1) p -> are the peaces(may not have one of the dimensions(%{width},%{depth},%{hight}))

2) a -> are the assembled boxes(doesn't have %{peace})

## __Hights:__

1) 20

2) 40

3) 60

## __Standard__

![Image][1]  
standard 70x70x40  
![Image][2]  
standard 70x210x40  

### __Parts__

#### __Bottom__

1) 70x70(<span style="color:green">✔✔✔</span>)

2) 70x140(<span style="color:green">✔✔✔</span>)

3) 70x210(<span style="color:green">✔✔✔</span>)

4) 70x280(<span style="color:green">✔✔✔</span>)

---

5) 140x140(<span style="color:green">✔✔✔</span>)

6) 140x210(<span style="color:green">✔✔✔</span>)

7) 140x280(<span style="color:green">✔✔✔</span>)

---

8) 210x210(<span style="color:green">✔✔✔</span>)

9) 210x280(<span style="color:red">✘</span>)

10) 280x280(<span style="color:red">✘</span>)

#### Top

1) A(<span style="color:green">✔✔✔</span>)

#### WallA

1) 70x20(<span style="color:green">✔✔✔</span>)

2) 70x40(<span style="color:green">✔✔✔</span>)

3) 70x60(<span style="color:green">✔✔✔</span>)

---

4) 140x20(<span style="color:green">✔✔✔</span>)

5) 140x40(<span style="color:green">✔✔✔</span>)

6) 140x60(<span style="color:green">✔✔✔</span>)

---

7) 210x20(<span style="color:green">✔✔✔</span>)

8) 210x40(<span style="color:green">✔✔✔</span>)

9) 210x60(<span style="color:green">✔✔✔</span>)

---

7) 280x20(<span style="color:red">✘</span>)

8) 280x40(<span style="color:red">✘</span>)

9) 280x60(<span style="color:red">✘</span>)

#### WallB

1) 70x20(<span style="color:green">✔✔</span>)

2) 70x40(<span style="color:green">✔✔</span>)

3) 70x60(<span style="color:green">✔✔</span>)

---

4) 140x20(<span style="color:green">✔✔</span>)

5) 140x40(<span style="color:green">✔✔</span>)

6) 140x60(<span style="color:green">✔✔</span>)

---

7) 210x20(<span style="color:green">✔✔</span>)

8) 210x40(<span style="color:green">✔✔</span>)

9) 210x60(<span style="color:green">✔✔</span>)

---

7) 280x20(<span style="color:red">✘</span>)

8) 280x40(<span style="color:red">✘</span>)

9) 280x60(<span style="color:red">✘</span>)

#### __WallC__

1) 70x20(<span style="color:green">✔✔</span>)

2) 70x40(<span style="color:green">✔✔</span>)

3) 70x60(<span style="color:green">✔✔</span>)

---

4) 140x20(<span style="color:green">✔✔</span>)

5) 140x40(<span style="color:green">✔✔</span>)

6) 140x60(<span style="color:green">✔✔</span>)

---

7) 210x20(<span style="color:green">✔✔</span>)

8) 210x40(<span style="color:green">✔✔</span>)

9) 210x60(<span style="color:green">✔✔</span>)

---

7) 280x20(<span style="color:red">✘</span>)

8) 280x40(<span style="color:red">✘</span>)

9) 280x60(<span style="color:red">✘</span>)

### __Width x Depth:__

1) 70x70x20(<span style="color:green">✔✔</span>)/40(<span style="color:green">✔✔</span>)/60(<span style="color:green">✔✔</span>)
    * 1x: [bottom_70x70](./README.md/#Boxes-LC/##Standard/###Parts/####Bottom)
    * 1x: [top_A](####Top)
    * 1x: [wallA_70x20/40/60](####WallA)
    * 1x: [wallB_70x20/40/60](####WallB)
    * 2x: [wallC_70x20/40/60](####WallC)


2) 70x140x20(<span style="color:green">✔✔</span>)/40(<span style="color:green">✔✔</span>)/60(<span style="color:green">✔✔</span>)
    * 1x: bottom_70x70
    * 1x: top_A
    * 1x: wallA_70x20/40/60
    * 1x: wallB_70x20/40/60
    * 2x: wallC_140x20/40/60

3) 70x210x20(<span style="color:green">✔✔</span>)/40(<span style="color:green">✔✔</span>)/60(**<span style="color:blue">≈</span>**)
    * 1x: bottom_70x70
    * 1x: top_A
    * 1x: wallA_70x20/40/60
    * 1x: wallB_70x20/40/60
    * 2x: wallC_210x20/40/60

4) 70x280x20(**<span style="color:blue">≈</span>**)/40(<span style="color:green">✔✔</span>)/60(**<span style="color:blue">≈</span>**)
    * 1x: bottom_70x70
    * 1x: top_A
    * 1x: wallA_70x20/40/60
    * 1x: wallB_70x20/40/60
    * 2x: wallC_280x20/40/60


---


5) 140x140x20(**<span style="color:blue">≈</span>**)/40(<span style="color:green">✔✔</span>)/60(**<span style="color:blue">≈</span>**)
    * 1x: bottom_140x140
    * 1x: top_A
    * 1x: wallA_140x20/40/60
    * 1x: wallB_140x20/40/60
    * 2x: wallC_140x20/40/60

6) 140x210x20(**<span style="color:blue">≈</span>**)/40(<span style="color:green">✔✔</span>)/60(**<span style="color:blue">≈</span>**)
    * 1x: bottom_140x140
    * 1x: top_A
    * 1x: wallA_140x20/40/60
    * 1x: wallB_140x20/40/60
    * 2x: wallC_210x20/40/60

7) 140x280x20(**<span style="color:blue">≈</span>**)/40(<span style="color:green">✔✔</span>)/60(**<span style="color:blue">≈</span>**)
    * 1x: bottom_140x140
    * 1x: top_A
    * 1x: wallA_140x20/40/60
    * 1x: wallB_140x20/40/60
    * 2x: wallC_280x20/40/60


---


8) 210x210x20(**<span style="color:blue">≈</span>**)/40(<span style="color:green">✔✔</span>)/60(**<span style="color:blue">≈</span>**)
    * 1x: bottom_210x210
    * 1x: top_A
    * 1x: wallA_210x20/40/60
    * 1x: wallB_210x20/40/60
    * 2x: wallC_210x20/40/60

9) 210x280x20(<span style="color:red">✘</span>)/40(<span style="color:red">✘</span>)/60(<span style="color:red">✘</span>)
    * 1x: bottom_210x210
    * 1x: top_A
    * 1x: wallA_210x20/40/60
    * 1x: wallB_210x20/40/60
    * 2x: wallC_280x20/40/60



---


10) 280x280x20(<span style="color:red">✘</span>)/40(<span style="color:red">✘</span>)/60(<span style="color:red">✘</span>)
    * 1x: bottom_280x280
    * 1x: top_A
    * 1x: wallA_280x20/40/60
    * 1x: wallB_280x20/40/60
    * 2x: wallC_280x20/40/60

##  __Reel__

These boxes have a cylinder in the middle for the reel to be secured on


### __Width x Depth:__

1) 140x140x40(<span style="color:red">✘</span>)/60(<span style="color:red">✘</span>)

2) 210x210x40(<span style="color:red">✘</span>)/60(<span style="color:red">✘</span>)

3) 280x280x40(<span style="color:red">✘</span>)/60(<span style="color:red">✘</span>)

4) 350x350x40(<span style="color:red">✘</span>)/60(<span style="color:red">✘</span>)

5) 420x420x40(<span style="color:red">✘</span>)/60(<span style="color:red">✘</span>)

##  __Battery__

These boxes are specially designed to hold battery's.

### __AA:__

1) 70x70x20(<span style="color:red">✘</span>)\[~2\]
2) 70x140x20(<span style="color:red">✘</span>)\[~5\]

### __AAA:__

1)

### __9V-Block:__

1)  


---

[home][0]
