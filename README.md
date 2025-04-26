# cs661-assignment-1--isocontour-and-volume-visualization-solved
**TO GET THIS SOLUTION VISIT:** [CS661 Assignment 1 -Isocontour and Volume Visualization Solved](https://www.ankitcodinghub.com/product/assignment-1-cs661-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;132068&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS661 Assignment 1 -Isocontour and Volume Visualization  Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
&nbsp;

1. 2D Isocontour Extraction: [60 Points]

Notes:

• For this part of the assignment, you must write the contour extraction algorithm on your own from scratch and you are not allowed to use VTK’s isocontour filter to do this. You can use VTK to read and write the data in VTK’s polydata file format.

• Your program should work for any isovalue provided by the user. Hence, submit a Python script (not a Jupyter Notebook), and your script should take the isovalue as an input parameter and write the extracted contour out as a *.vtp (VTKPolyData) file. Make sure your output file can be read in ParaView. The possible range of isovalues for the given data set is between (-1438, 630)

Dataset for this task:

The dataset that you will use in this assignment is a 2D slice taken from a 3D Scalar field of a Hurricane Simulation Data. The variable is Pressure. If you want to know more about the original data, please refer to this link: http://vis.computer.org/vis2004contest/index.html

2. VTK Volume Rendering and Transfer Function: [40 Points]

In this second half of the assignment, you will write a Python script to implement the volume rendering algorithm from the VTK library. VTK has already implemented the ray-casting algorithm that we have studied in our class. In this assignment, you will use the vtkSmartVolumeMapper() to render 3D scalar data and set a specific color and opacity transfer function. You will also use VTK’s Phong Shading feature to produce advanced lighting effects to make your volume rendering more realistic. The ambient, diffuse, and specular parameters for Phong model are given below. Here are the steps that you should follow for this task:

• Load the 3D data provided with the assignment.

• Create instances of vtkColorTransferFunction and vtkPiecewiseFunction (this will work as Opacity transfer function) and set them up with the values provided below in the tables.

• Use vtkSmartVolumeMapper() class to perform the volume rendering

• Use vtkOutlineFilter to add an outline to the volume rendered data

• By default, advanced shading feature, i.e., Phong shading will be off. Create an input parameter and take input from user if the user wants to use Phong shading. If yes, then your program should turn on Phong shading while rendering.

• Create a 1000×1000 sized render window to show the rendering result.

Color Transfer Function Specification:

Data Value Red Green Blue

-4931.54 0 1 1

-2508.95 0 0 1

-1873.9 0 0 0.5

-1027.16 1 0 0

-298.031 1 0.4 0

2594.97 1 1 0

Opacity Transfer Function Specification:

Data Value Opacity Value

-4931.54 1.0

101.815 0.002

2594.97 0.0

Phong Shading Parameters that you should use:

Ambient coefficient: 0.5

Diffuse coefficient: 0.5

Specular coefficient: 0.5

Again, you should write a Python script (not a Notebook), and your script will take the input parameter as to whether the user wants to use Phong shading or not. Update the above README.txt file to add instructions about how to run your volume rendering script.

If you have done everything as suggested, you should see images like the following for volume rendering:

Without Phong shading, front, and back view

With Phong Shading, front, and back view

Dataset for this task:

The dataset that you will use in this assignment is a 3D Scalar field Volume Data of a Hurricane Simulation. Loading this data in VTK will be same as loading the 2D data. The variable in the Data is Pressure. If you want to know more about the original data, please refer to this link: http://vis.computer.org/vis2004contest/index.html.

How to submit?
