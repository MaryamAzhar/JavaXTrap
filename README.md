# JavaXTrep


<h1>JavaXTrap : This is for Console base Desktop Application by Java</h1>
<h4>JavaXTrap is a package of swing library it will help your project building an AWT components.In this most of components are built in where your only have to call the class and use it instead of making your own.</h4>
<h4>Java XTrep is a lightweight Graphical User Interface (GUI) toolkit that includes a rich set of widgets. It includes package lets you make GUI components for your Java applications, and It is platform independent.</h4>
<h4>The Java XTrep library is built on top of the Java Abstract Widget Toolkit (AWT), an older, platform dependent GUI toolkit. You can use the Java GUI components like button, textbox, etc. from the library and do not have to create the components from scratch.</h4>

<h2>STEPS TO USE JAVA XTREP IN YOUR PROJECTS :</h2>
<h3>1.Add jar file of custom controls in your project.</h3>
 <img src="https://github.com/azharandmaryam/JavaXTrap/blob/master/Images/1.png"/)
 <br/>


<h3>2.Import libraries and package in your project</h3>
<h4>
<ol type="i">
<li>package UsingCustomControls;</li>
<li>import CustomControls.*;</li>
<li>import java.awt.*;</li>
<li>import javax.swing.*;</li>
</ol>
	</h4>







NOW YOU ARE ABLE TO USE THE COMPONENTS OF JAVA XTREP
DANGER BUTTON:
CustomDangerousButton mdb = new CustomDangerousButton("DANGER", 0, 51);





SIZABLE DANGER BUTTON :
CustomDangerousButton mdbc = new CustomDangerousButton("DANGER", 0, 0, 150, 50);





INFORMATION BUTTON :
CustomInfoButton mib = new CustomInfoButton("INFO", 101, 51);









SIZABLE INFORMATION BUTTON:
CustomInfoButton mibc = new CustomInfoButton("INFO", 151, 0, 150, 50);





SUCCESS BUTTON :
CustomSuccessButton msb = new CustomSuccessButton("SUCCESS", 301, 51);












SIZABLE  SUCCESS BUTTON :


CustomSuccessButton msbc = new CustomSuccessButton("SUCCESS", 451,0 , 150, 50);









PRIMARY BUTTON :
CustomPrimaryButton mpb = new CustomPrimaryButton("PRIMARY", 201, 51);
 



PRIMARY BUTTON SIZABLE:
 CustomPrimaryButton mpbc = new CustomPrimaryButton("PRIMARY", 301, 0, 150, 50);






TEXT FIELDS:
TEXT FIELDS WITH FIXED SIZE:
CustomTextField mtf1 = new CustomTextField(0, 102, 200, 50, Color.BLACK,Color.CYAN);

 




CustomTextField mtf2 = new CustomTextField(203, 102, 200, 50, Color.cyan, Color.black, "text");

 



CustomTextField mtf3 = new CustomTextField(404, 102, 200, 50, Color.decode("#FFFFFF"),225, 63, 23);

 




CustomTextField mtf4 = new CustomTextField(605, 102, 200, 50,Color.decode("#FFFFFF"),225, 63, 23,"text");

 

 

CustomTextField mtf5 = new CustomTextField(806, 102, 200,50,  255, 255, 255,225, 63, 23  );
 




Custom TextField mtf6 =new CustomTextField(1007, 102, 200,50, 255, 255, 255,225, 63, 23 ,"text ");




SIZABLE TEXT FIELDS :
CustomTextArea mta1 = new CustomTextArea(0, 153, 200, 100, Color.black, Color.cyan);

 



CustomTextArea mta2 = new CustomTextArea(203, 153, 200, 100, Color.cyan, Color.black, "text ");
 




CustomTextArea mta3 = new CustomTextArea(404, 153, 200,100,Color.decode("#FFFFFF"), 255, 63, 23);
 




CustomTextArea mta4 = new CustomTextArea(605, 153, 200, 100,		Color.decode("#FFFFFF"),255, 63, 23,"text");





CustomTextArea mta5 = new CustomTextArea(806, 153, 200,100, 255, 255, 255,255, 63, 23 );

 



CustomTextArea mta6 =new CustomTextArea(1007, 153, 200,100,  255, 255, 255,255, 63, 23 ,"text");







PROGRESS BAR:
CustomProgressBar mpb1 = new CustomProgressBar(151, 274, 150, 50, 0, 10);
 




CustomProgressBar mpb2 = new CustomProgressBar(Color.darkGray , 301, 274, 150, 50, 10, 10);
 





CustomProgressBar mpb3 = new CustomProgressBar(452, 274, 150, 50, 20, 10, Color.blue);
 




CustomProgressBar mpb4 = new CustomProgressBar(602, 274, 150, 50, 30,10, Color.green, Color.red);

 








CustomProgressBar mpb5 = new CustomProgressBar(753, 274, 150, 50, 40, 10, 136, 202, 198, Color.yellow)



 
 




CustomProgressBar mpb6 = new CustomProgressBar(904, 274, 150, 50, 50, 10, 255,255,255,199, 0, 57  );
 
        



CIRCLE PROGRESS BAR:



  













SIZABLE CIRCLE PROGRESS BAR:


































