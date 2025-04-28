# csc4140-assignment-i-solved
**TO GET THIS SOLUTION VISIT:** [CSC4140 Assignment I Solved](https://www.ankitcodinghub.com/product/csc4140-assignment-i-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116877&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC4140 Assignment I Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
1 Learn to use VirtualBox

1.1 Install Virtual Box

For Linux, visit Linux Installation Guide, and then install it by following instructions.

For Windows, Download Windows Download Link, and then install it by following instructions.

For Mac OS, Download Mac OS Download Link, and then install it by following instructions.

1.2 Download Virtual Disk

Download virtual disk Graphics-CUHKSZ.rar, 4.39G, password:4140. Unzip the .rar file, you will get a Graphics-CUHKSZ.vdi.

1.3 Configure Your Virtual Box

Open your virtual box, click “New”, set type as “Linux”, choose “Ubuntu-64 bit”, set the memory size as large as possible, and choose your VDI file as the virtual hard disk. Then create

it!

For your system, the Password is CUHKSZ. You can create user as you like.

1.4 Submission Checklist

Use latex to write the report. I promise it will helps you go further for your research and you can use either Overleaf online or Texmaker offline. The template for the report is attached.

2. CMake file

3. source code files “*.cpp”

4. header files “*.hpp” if any.

5. and report “UrStudentID_HW_X.pdf”

Pack them as a “UrStudentID_HW_X.zip” file and submit through BB. Attention, do not submitted any unneeded files for folders like /build, /.vscode.

1.5 Some useful pre-requests tutorial

Tutorial about how to use CMake

Tutorial about how to use C++

Tutorial about how to use OpenCV C++

Tutorial about how to use Eigen, Eigen Matrix. Eigen is a popular linear algebra library

Note: Do not ask questions before ask the above link and google. The TAs resources is scarcity for this new course and can only help you cover the content of this course.

1.6 header files you need this time

#include&lt;cmath&gt;

#include&lt;eigen3/Eigen/Core&gt;

#include&lt;eigen3/Eigen/Dense&gt;

#include&lt;Eigen/SVD&gt;

#include&lt;iostream&gt;

2 Basics operations of vectors and matrix

2.1 Basic vector operations (10 points)

print out the results and put it (crops) into your .pdf report.

1. Define two float vectors v[1, 1.5, 2, 3] and w[0, 1, 2, 4]

2. vector add

3. vector inner product

4. vector cross product

2.2 Basic matrix operations (20 points)

print out the results (in a good “rectangular” shape) and put it (crops) into your .pdf report.

1. Define two 4×4 matrix i[1,…, 16] and j[4, 3, 2, 1; …; 16,15,14,13]

2. matrix add i+j

3. matrix multiply i*j

4. matrix multiply vector i*v

2.3 SVD decomposition of “lenna” (40 points)

Given an 512×512 image “lenna.png”. Your task is

1. convert it to gray scale using Opencv and normalize the range from [0, 255] to [0, 1.0].

2. You got a 512×512 matrix now. Decomposite it to S, V, and D matrix using Eigen. img=U*S*V’

3. Save the feature map of the first singular value U(:,:)*S(:,1)*V(:,1)’ as an image then put it into your .pdf report;

4. Save the feature map of the first ten singular value U(:,:)*S(:,1:10)*V(:,1:10)’ as an image then put it into your .pdf report;

5. Save the feature map of the first fifty singular value U(:,:)*S(:,1:50)*V(:,1:50)’ as an image then put it into your .pdf report;

6. Explain the results you have seen in your .pdf report.

2.4 Basic transformation operations (30 points)

print out the results and put it (crops) into your .pdf report. Given a Point [1,2,3], rotate it

(45·,30·,60·) around the Point [4,5,6]. Where is the new Point?
