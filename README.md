# EasyView README

EasyView is a general visualizer for performance tools. It supports widely used [pprof format](https://github.com/google/pprof/blob/master/proto/profile.proto).
EasyView is available as an extension of vscode at [vscode market](https://marketplace.visualstudio.com/items?itemName=xuhpclib-easyview.easyview). EasyView enjoys the following unique features.

1. **Easy deployment**. EasyView, tightly integrated in vscode, only needs 1-click installation in vscode marketplace. All the analysis and visualization work is done on the local machine, with no server or other software installation needed. 
2. **Easy visualization**. EasyView can visualize profiles in top-down, bottom-up, and flat views presented in the form of flamegraphs and tree tables. EasyView supports multiple metrics and associates both flamegraphs and tree tables with source code in vscode.  
3. **Easy exploration**. EasyView supports smooth exploration of large profiles. Compared to the other profile visualizer, EasyView can handle profiles whose sizes are orders of magnitudes larger than existing tools can handle, accelerate profile analysis by 50X faster, and yield high frames per second (FPS) for user interaction.


## Usage

### Install EasyView

Open Extensions in vscode and search for EasyView. With one click on the Install icon, EasyView is installed on the local machine.

### Use EasyView

Before using EasyView, you need to first collect profiles in either PProf format or DrCCTProf format. 
Once the profile is generated, there are three ways to open it.


#### 1. Open EasyView with vscode Explorer View

(1) Right-click the profile file.

(2) Click "show EasyView".

#### 2. Make EasyView as the default view by changing the file extension suffix

(1) Add an extension suffix (***.ezview***) to the unzipped profile file.

(2) Click the file to open it with the EasyView by default.


## A demo for using EasyView

Click the following video and watch a short demo on YouTube.

[![YouTube](./YouTube.png)](https://youtu.be/NKS3pIe3-qQ)
