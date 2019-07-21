[FrontendMasters] Creative Coding with Canvas & WebGL

1. Introduction

CHeck the docs (canvas-sketch from the repo) for details on print sizes and dimensionality , etc.


2. Print Art with Canvas

for creating new canvas file use the following line below:
canvas-sketch sketch1Example.js --new --open

2 and 3Vid 
Just check out lot of other feature in canvas api from Mozilla Developer Network(MDN)
Especially Canvas2DRendering for drawing shapes and lots other


4 Vid setting={
dimensions: 'A4' or [35,15], this array is x=35 cm and y = 15cm
orientation: 'portrait', or 'landscape',
units: 'cm',
pixelsPerInch: 300
};

this helps in giving out a print sizes and specific pexilsPerInch


All the Code till Vid 11 Can be understood slowly take your time and learn it
Till 4pm 20 July
Start from Vid 11


At vid 14 Canvas Q&A
random.setSeed(random.getRandomSeed());
const settings = {
 suffix: random.getSeed(),
dimensions: [2048, 2048]
}


This causes the file being stored to be put into the with its associated random.getRandomSeed() number Attached at the end




3. Physical World Canvas

4. Three Dimensional Thinking

5. Making a GIF

in Vid 2 

for exporting the GIF from our threejs sceen

const settings= {
dimensions: [ 512, 512 ],
fps: 24,
duration: 7
animate = true,
 context: 'webgl',
attributes: { antialias: true }

};

forgetting to fps and durations and then saving for gif will emmit lot of png file that make lot files 

and also the png that van put to giftooll that make the gif


6. Shaders

7. Conclusion

