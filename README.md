# CircleView
CircleView
A Circle View containing Title and Subtitle

CircleView


Attributes to choose from:

titleText - The text in the first row.
subtitleText - The text in the second row.
titleSize - The size of the first row text.
subtitleSize - The size of the second row text.
strokeWidth - The size of the outter line surrounding the view.
fillRadius - The radius of the inner circle.
titleColor - The color of the first row text.
subtitleColor - The color of the second row text.
fillColor - The color of the inner circle.
strokeColorValue - The color of the outter line circle.
backgroundColorValue - the color between the circle and the stroke.


Example
 <com.github.circleView
        xmlns:app="http://schemas.android.com/apk/res-auto"
        android:layout_width="300dp"
        android:layout_height="300dp"
        app:titleText="title"
        app:subtitleText="subtitle"
        app:titleSize="12dp"
        app:subtitleSize="9dp"
        app:titleColor="@color/white"
        app:subtitleColor="@color/red"
        app:strokeColorValue="@color/blue"
        app:backgroundColorValue="@color/gray"
        app:fillColor="@color/green"
        app:fillRadius="0.9"
        app:strokeWidth="5"/>
        
How To Use

You can search us on Gradle,please http://gradleplease.appspot.com/ or just add

the dependency to your module's build.gradle file:

compile 'com.github.pavlospt:circleview:1.2'

Credits
Author : Pavlos-Petros Tournaris (p.tournaris@gmail.com)
