# TheftDetection2

Program is built by implementing background subtraction and contour detection algorithm. The algorithms are applied plainly, background subtraction is used with the background model solely specified by the user, while contour detection is used with hierarchy of the detected object ignored. Then the detection of stealing were done by comparing each object that have been detected on each frame. There are variables in the program that can be configured manually by users to help program in detecting objects and detect theft afterward.

After the program is created, we can conclude that programs that implement background subtraction and contour detection can detect motor vehicle theft. Different environtment and place, requires distinct configuration of variables, and no variable value that suits all conditions to detect theft. However, the program that has been made were very sensitive to illumination changes, because the value of learning rate is set to 0. This makes this kind of programs are not suitable for use in places that exposed to illumination changes, such as day and night.

Currently used file:
-FXML.fxml
-FXMLController.java
-Objek.java
-ObjekLinkedList.java
-ObjekList.java
-TheftDetection.java

preview how to use it: https://www.youtube.com/watch?v=1oa_TbabcCQ

