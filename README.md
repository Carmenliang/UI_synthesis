# UI_synthesis
A platform for synthesizing realistic, high-resolution, and editable ultrasound images based on generative adversarial network. (Ovary datasets)

## System requirements
 - Windows OS
 (We provide a CPU version, and therfore the computational time will be longer than using GPU.)

## Software download
  [https://1drv.ms/u/s!AjRq4iQQNnRfgig1lXzDHnMrIOhs?e=YRBXcc](https://1drv.ms/u/s!AjRq4iQQNnRfgig1lXzDHnMrIOhs?e=YRBXcc)

## Usage
![image](https://user-images.githubusercontent.com/37099112/121143436-a2039180-c86f-11eb-9012-d58009c3cb43.png)

- Open Image: load a grey-scale label map from file.
- Save Label: save the label map.
- Save Result: save the synthesized image.
- Clear: clear the label map and synthesized image.
- Transfer: start to synthesize using the label map.
- Drawing Pen: set color and brush size of the drawing pen to modify the label map.


### Synthesis using demo image
1.	Download the file in [https://1drv.ms/u/s!AjRq4iQQNnRfgig1lXzDHnMrIOhs?e=YRBXcc](https://1drv.ms/u/s!AjRq4iQQNnRfgig1lXzDHnMrIOhs?e=YRBXcc).
2.	Double-click 'start.exe'.
3.	Click 'Open Image' to load a label image. Demo images are in the folder './demo_img'.
	After the loading, the platform will transfer the label image to a ultrasound image automatically.
4.	Set color and brush size of the drawing pen to edit the label image. Wait a few seconds after editing, and the synthesized ultrasound image will update automatically , or you can click 'Transfer' to start to synthesize immediately.
