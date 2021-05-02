[1]: ./img/70x70x40.png
[2]: ./img/70x210x40.png

# __Boxes-LC__  

The boxes are designed for the assortment system.

The Boxes are designed to be cut with an lasercutter.

${hight}<span style="color:red">✘</span> ->  nothing or only some parts  
${hight}<span style="color:green">✔</span> -> design done  
${hight}<span style="color:green">✔✔</span> -> design and documentation done  
${hight}<span style="color:green">✔✔✔</span> -> design, documentation and dxf export done

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

### __Width x Depth:__

1) 70x70(<span style="color:green">20✔✔</span>, <span style="color:green">40✔✔</span>, <span style="color:green">60✔✔</span>)

2) 70x140(<span style="color:green">20✔✔</span>, <span style="color:green">40✔✔</span>, <span style="color:green">60✔✔</span>)

3) 70x210(<span style="color:green">20✔✔</span>, <span style="color:green">40✔</span>, <span style="color:red">60✘</span>)

4) 70x280(<span style="color:red">20✘</span>, <span style="color:green">40✔</span>, <span style="color:red">60✘</span>)


---


5) 140x140(<span style="color:red">20✘</span>, <span style="color:green">40✔</span>, <span style="color:red">60✘</span>)

6) 140x210(<span style="color:red">20✘</span>, <span style="color:green">40✔</span>, <span style="color:red">60✘</span>)

7) 140x280(<span style="color:red">20✘</span>, <span style="color:green">40✔</span>, <span style="color:red">60✘</span>)


---


8) 210x210(<span style="color:red">20✘</span>, <span style="color:green">40✔</span>, <span style="color:red">60✘</span>)

9) 210x280(<span style="color:red">20✘</span>, <span style="color:red">40✘</span>, <span style="color:red">60✘</span>)



---


10) 280x280(<span style="color:red">20✘</span>, <span style="color:red">40✘</span>, <span style="color:red">60✘</span>)

##  __Reel__

These boxes have a cylinder in the middle for the reel to be secured on


### __Width x Depth:__

1) 140x140(<span style="color:red">40✘</span>, <span style="color:red">60✘</span>)

2) 210x210(<span style="color:red">40✘</span>, <span style="color:red">60✘</span>)

3) 280x280(<span style="color:red">40✘</span>, <span style="color:red">60✘</span>)

4) 350x350(<span style="color:red">40✘</span>, <span style="color:red">60✘</span>)

5) 420x420(<span style="color:red">40✘</span>, <span style="color:red">60✘</span>)

##  __Battery__

These boxes are specially designed to hold battery's.

### __AA:__

1) 70x70\[~2\](<span style="color:red">20✘</span>)
2) 70x140\[~5\](<span style="color:red">20✘</span>)

### __AAA:__

1) 

### __9V-Block:__

1)  


---

[home](https://github.com/tobiasfalk/Assortment_System_Main_Page/blob/master/README.md)