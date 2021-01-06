# Face Mask Detection System 🚀

**Our project is based on real life problem faced by many organizations in this pendemic phase which is improper wearing of face mask which can cause serious damages to there employees and co-workers 🤖**

**To deal with this problem our team `Smart Brains` have came up with the solution "The Face Mask Detection System" which can be implemented in very simple steps and at a very low cost and is very flexible**

### Implementation

**Hardware** we need to work with this project:-
<blockquote>
<ul>
    <li>Raspberry Pi</li>
    <li>Raspberry Pi Camera Module</li>
    <li>Buzzer </li>
    <li>Jumper Wires</li>
    <li>2 LED Bulbs</li>
</ul>
</blockquote>

**Software** we need in Raspberry Pi to continue with our project
<blockquote>
<ul>
    <li>Raspbian Os</li>
    <li>Python 3
        <ul>
            <li>Tensorflow</li>
            <li>Tensorflow Hub</li>
            <li>Keras</li>
            <li>Scikit Learn</li>
            <li>MatPlotLib</li>
            <li>Numpy</li>
            <li>Imutils</li>
            <li>Open Cv</li>
            <li>Scipy</li>
        </ul>
    </li>
</ul>
</blockquote>

**Connections**
<blockquote>
    <ul>
        <li>Connect the positive end of the buzzer to the Gpio pin 17 and negative end to the ground pin </li>
        <li>Connect Led1 positive end to Gpio pin 4 and negative to ground this will indicate that all files are loaded and ready to use</li>
        <li>Connect Led2 positive end to Gpio 21 and negative to ground</li>
        <li>Connect the Camera module to Raspberry pi camera ribbon connector</li>
    </ul>
    Once Hardware setup is done we are ready to boot up raspberry pi 🚀
</blockquote>



**Setting up directory**
<blockquote>
Frist we need to setup Raspberry Pi:-
    <ol>
        <li>Install raspbian on sd card and insert it into the raspberry pi and boot it up for frist use</li>
        <li>Now save all the files given in this directory into Raspberry pi (For this we assume you have pasted the files into desktop)</li>
        <li>Now open the terminal and install the dependencies we metioned earlier</li>
        <li>Open rasp_mask_detector.py in text editor</li>
        <li>Goto line 71 and check the camera setup you are using and change accordingly</li>
        <li>Now save that file and we are ready to run the script</li>
    </ol>
</blockquote>

`python rasp_mask_detector`

**Install Dependencies Instructions**

Python3 is already installed in Raspbian Os so we only need to install other packages

`pip3 install tensorflow`

`pip3 install opencv-python`

`pip3 install imutils`

`pip3 install keras`

The good part is that python distributions for Raspberry pi comes with Matplotlib and Numpy with optimal versions so you dont have to worry about it 🕸
