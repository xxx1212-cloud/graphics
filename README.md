<?xml version="1.0" encoding="utf-8"?> 
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android" 
    xmlns:app="http://schemas.android.com/apk/res-auto" 
    xmlns:tools="http://schemas.android.com/tools" 
    android:id="@+id/main" 
    android:layout_width="match_parent" 
    android:layout_height="match_parent" 
    tools:context=".MainActivity"> 
 
    <Button 
        android:id="@+id/animation" 
        android:layout_width="wrap_content" 
        android:layout_height="63dp" 
        android:layout_alignParentStart="true" 
        android:layout_alignParentEnd="true" 
        android:layout_alignParentBottom="true" 
        android:layout_marginStart="140dp" 
        android:layout_marginEnd="122dp" 
        android:layout_marginBottom="211dp" 
        android:text="Animation" 
        
tools:ignore="DuplicateClickableBoundsCheck,DuplicateSpeakableTextCheck,HardcodedText,VisualLintOverlap,
 VisualLintButtonSize" 
        tools:layout_editor_absoluteX="143dp" 
        tools:layout_editor_absoluteY="219dp" /> 
 
    <Button 
        android:id="@+id/graphic" 
        android:layout_width="136dp" 
        android:layout_height="63dp" 
        android:layout_alignParentStart="true" 
        android:layout_alignParentEnd="true" 
        android:layout_alignParentBottom="true" 
        android:layout_marginStart="131dp" 
        android:layout_marginEnd="144dp" 
        android:layout_marginBottom="464dp" 
        android:text="Graphics" 
        tools:ignore="HardcodedText,VisualLintButtonSize" 
        tools:layout_editor_absoluteX="149dp" 
        tools:layout_editor_absoluteY="419dp" /> 
 
</RelativeLayout> 
 
 
 
 
<?xml version="1.0" encoding="utf-8"?> 
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android" 
    xmlns:app="http://schemas.android.com/apk/res-auto" 
    xmlns:tools="http://schemas.android.com/tools" 
    android:id="@+id/main" 
    android:layout_width="match_parent" 
    android:layout_height="match_parent" 
    tools:context=".MainActivity2"> 
 
    <Button 
        android:id="@+id/button3" 
        android:layout_width="147dp" 
        android:layout_height="wrap_content" 
        android:layout_alignParentEnd="true" 
        android:layout_alignParentBottom="true" 
        android:layout_marginEnd="215dp" 
        android:layout_marginBottom="167dp" 
        android:text="Circle" 
        android:textStyle="bold" 
        tools:ignore="HardcodedText" /> 
 
    <Button 
        android:id="@+id/button4" 
        android:layout_width="145dp" 
        android:layout_height="wrap_content" 
        android:layout_alignParentEnd="true" 
        android:layout_alignParentBottom="true" 
        android:layout_marginEnd="29dp" 
        android:layout_marginBottom="254dp" 
        android:text="Square" 
        android:textStyle="bold" 
        tools:ignore="HardcodedText" /> 
 
    <Button 
        android:id="@+id/button5" 
        android:layout_width="141dp" 
        android:layout_height="wrap_content" 
        android:layout_alignParentStart="true" 
        android:layout_alignParentEnd="true" 
        android:layout_alignParentBottom="true" 
        android:layout_marginStart="51dp" 
        android:layout_marginEnd="219dp" 
        android:layout_marginBottom="252dp" 
        android:text="Rectangle" 
        android:textStyle="bold" 
        tools:ignore="HardcodedText,VisualLintButtonSize" /> 
 
    <Button 
        android:id="@+id/button6" 
        android:layout_width="143dp" 
        android:layout_height="wrap_content" 
        android:layout_alignParentEnd="true" 
        android:layout_alignParentBottom="true" 
        android:layout_marginEnd="30dp" 
        android:layout_marginBottom="164dp" 
        android:text="Line" 
        android:textStyle="bold" 
        tools:ignore="HardcodedText,TouchTargetSizeCheck" /> 
 
    <ImageView 
        android:id="@+id/imageView" 
        android:layout_width="336dp" 
        android:layout_height="401dp" 
        android:layout_alignParentStart="true" 
        android:layout_alignParentTop="true" 
        android:layout_alignParentEnd="true" 
        android:layout_alignParentBottom="true" 
        android:layout_marginStart="47dp" 
        android:layout_marginTop="0dp" 
        android:layout_marginEnd="28dp" 
        android:layout_marginBottom="330dp" 
        tools:ignore="ContentDescription" 
        tools:srcCompat="@tools:sample/avatars" /> 
</RelativeLayout> 
 
 
<?xml version="1.0" encoding="utf-8"?> 
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android" 
    xmlns:app="http://schemas.android.com/apk/res-auto" 
    xmlns:tools="http://schemas.android.com/tools" 
    android:id="@+id/main" 
    android:layout_width="match_parent" 
    android:layout_height="match_parent" 
    tools:context=".MainActivity3"> 
 
    <Button 
        android:id="@+id/button7" 
        android:layout_width="110dp" 
        android:layout_height="wrap_content" 
        android:layout_alignParentStart="true" 
        android:layout_alignParentEnd="true" 
        android:layout_alignParentBottom="true" 
        android:layout_marginStart="57dp" 
        android:layout_marginEnd="244dp" 
        android:layout_marginBottom="321dp" 
        android:text="Fade" 
        tools:ignore="HardcodedText,VisualLintButtonSize,VisualLintOverlap" /> 
 
    <Button 
        android:id="@+id/button8" 
        android:layout_width="121dp" 
        android:layout_height="wrap_content" 
        android:layout_alignParentStart="true" 
        android:layout_alignParentEnd="true" 
        android:layout_alignParentBottom="true" 
        android:layout_marginStart="255dp" 
        android:layout_marginEnd="35dp" 
        android:layout_marginBottom="318dp" 
        android:text="Rotate" 
        tools:ignore="HardcodedText,VisualLintButtonSize" /> 
 
    <Button 
        android:id="@+id/button9" 
        android:layout_width="105dp" 
        android:layout_height="wrap_content" 
        android:layout_alignParentStart="true" 
        android:layout_alignParentEnd="true" 
        android:layout_alignParentBottom="true" 
        android:layout_marginStart="63dp" 
        android:layout_marginEnd="243dp" 
        android:layout_marginBottom="187dp" 
        android:text="Zoom" 
        tools:ignore="HardcodedText,VisualLintButtonSize,VisualLintOverlap" /> 
 
    <Button 
        android:id="@+id/button10" 
        android:layout_width="110dp" 
        android:layout_height="wrap_content" 
        android:layout_alignParentStart="true" 
        android:layout_alignParentEnd="true" 
        android:layout_alignParentBottom="true" 
        android:layout_marginStart="260dp" 
        android:layout_marginEnd="41dp" 
        android:layout_marginBottom="187dp" 
        android:text="Blink" 
        tools:ignore="HardcodedText,VisualLintButtonSize" /> 
 
    <TextView 
        android:id="@+id/textView" 
        android:layout_width="167dp" 
        android:layout_height="52dp" 
        android:layout_alignParentStart="true" 
        android:layout_alignParentEnd="true" 
        android:layout_alignParentBottom="true" 
        android:layout_marginStart="134dp" 
        android:layout_marginEnd="109dp" 
        android:layout_marginBottom="475dp" 
        android:text="AKSHATHA" 
        android:textSize="24sp" 
        android:textStyle="bold" 
        tools:ignore="HardcodedText" /> 
</RelativeLayout> 
 
 
package com.example.grp; 
 
import android.content.Intent; 
import android.os.Bundle; 
import android.view.View; 
import android.widget.Button; 
 
import androidx.appcompat.app.AppCompatActivity; 
 
public class MainActivity extends AppCompatActivity { 
Button graphic,animation; 
    @Override 
    protected void onCreate(Bundle savedInstanceState) { 
        super.onCreate(savedInstanceState); 
 
        setContentView(R.layout.activity_main); 
        animation=findViewById(R.id.animation); 
        graphic = findViewById(R.id.graphic); 
 
        animation.setOnClickListener(new View.OnClickListener() { 
            @Override 
            public void onClick(View v) { 
                Intent i = new Intent(MainActivity.this,MainActivity3.class); 
                startActivity(i); 
            } 
        }); 
        graphic.setOnClickListener(new View.OnClickListener() { 
            @Override 
            public void onClick(View v) { 
                Intent i = new Intent(MainActivity.this,MainActivity2.class); 
                startActivity(i); 
            } 
        }); 
    } 
} 
 
 
package com.example.grp; 
 
import android.graphics.Bitmap; 
import android.graphics.Canvas; 
import android.graphics.Color; 
import android.graphics.Paint; 
import android.os.Bundle; 
import android.view.View; 
import android.widget.Button; 
import android.widget.ImageView; 
 
import androidx.activity.EdgeToEdge; 
import androidx.appcompat.app.AppCompatActivity; 
 
public class MainActivity2 extends AppCompatActivity { 
Button rect,sq,circle,line; 
ImageView img; 
Bitmap bp; 
 
    @Override 
    protected void onCreate(Bundle savedInstanceState) { 
        super.onCreate(savedInstanceState); 
        EdgeToEdge.enable(this); 
        setContentView(R.layout.activity_main2); 
        rect=findViewById(R.id.button5); 
        sq=findViewById(R.id.button4); 
        circle=findViewById(R.id.button3); 
        line=findViewById(R.id.button6); 
        bp=Bitmap.createBitmap(520,1200,Bitmap.Config.ARGB_8888); 
        img=findViewById(R.id.imageView); 
        img.setImageBitmap(bp); 
        Canvas c =new Canvas(bp); 
rect.setOnClickListener(new View.OnClickListener() { 
    @Override 
    public void onClick(View v) { 
        Paint p = new Paint(); 
        p.setColor(Color.BLUE); 
        p.setTextSize(50); 
 
        c.drawText("Rectangle",50,150,p); 
        c.drawRect(50,200,200,500,p); 
    } 
}); 
sq.setOnClickListener(new View.OnClickListener() { 
    @Override 
    public void onClick(View v) { 
        Paint p1 = new Paint(); 
        p1.setColor(Color.RED); 
        p1.setTextSize(50); 
 
        c.drawText("Square",350,150,p1); 
        c.drawRect(270,270,400,400,p1); 
    } 
}); 
circle.setOnClickListener(new View.OnClickListener() { 
    @Override 
    public void onClick(View v) { 
        Paint p2 = new Paint(); 
        p2.setColor(Color.GREEN); 
        p2.setTextSize(50); 
 
        c.drawText("Circle",100,600,p2); 
        c.drawCircle(200,700,80,p2); 
    } 
}); 
line.setOnClickListener(new View.OnClickListener() { 
    @Override 
    public void onClick(View v) { 
        Paint p3 = new Paint(); 
        p3.setColor(Color.BLACK); 
        p3.setTextSize(50); 
 
        c.drawText("Line",400,800,p3); 
        c.drawLine(300,600,700,500,p3); 
 
    } 
}); 
    } 
 
} 
 
 
package com.example.grp; 
 
import android.os.Bundle; 
import android.view.View; 
import android.view.animation.Animation; 
import android.view.animation.AnimationUtils; 
import android.widget.Button; 
import android.widget.TextView; 
 
import androidx.activity.EdgeToEdge; 
import androidx.appcompat.app.AppCompatActivity; 
 
public class MainActivity3 extends AppCompatActivity { 
Button fade,rotate,zoom,blink; 
TextView t1; 
    @Override 
    protected void onCreate(Bundle savedInstanceState) { 
        super.onCreate(savedInstanceState); 
        EdgeToEdge.enable(this); 
        setContentView(R.layout.activity_main3); 
        fade=findViewById(R.id.button7); 
        rotate=findViewById(R.id.button8); 
        zoom=findViewById(R.id.button9); 
        blink=findViewById(R.id.button10); 
        t1=findViewById(R.id.textView); 
        fade.setOnClickListener(new View.OnClickListener() { 
            @Override 
            public void onClick(View v) { 
                Animation blinkanim= AnimationUtils.loadAnimation(MainActivity3.this,R.anim.fade); 
                t1.startAnimation(blinkanim); 
            } 
        }); 
        rotate.setOnClickListener(new View.OnClickListener() { 
            @Override 
            public void onClick(View v) { 
                Animation rotateanim= AnimationUtils.loadAnimation(MainActivity3.this,R.anim.rotate); 
                t1.startAnimation(rotateanim); 
            } 
        }); 
        zoom.setOnClickListener(new View.OnClickListener() { 
            @Override 
            public void onClick(View v) { 
                Animation zoomanim= AnimationUtils.loadAnimation(MainActivity3.this,R.anim.zoom); 
                t1.startAnimation(zoomanim); 
            } 
        }); 
        blink.setOnClickListener(new View.OnClickListener() { 
            @Override 
            public void onClick(View v) { 
                Animation blinkanim= AnimationUtils.loadAnimation(MainActivity3.this,R.anim.blink); 
                t1.startAnimation(blinkanim); 
            } 
        }); 
    } 
} 
 
blink: 
 
<?xml version="1.0" encoding="utf-8"?> 
<alpha xmlns:android="http://schemas.android.com/apk/res/android" 
    android:toAlpha="0.0" 
    android:fromAlpha="1.0" 
    android:duration="500" 
    android:repeatCount="3" 
    android:repeatMode="reverse"    /> 
 
 
 
 
fade: 
<?xml version="1.0" encoding="utf-8"?> 
<alpha xmlns:android="http://schemas.android.com/apk/res/android" 
    android:toAlpha="0.0" 
    android:fromAlpha="1.0" 
    android:duration="5000"/> 
 
rotate: 
<?xml version="1.0" encoding="utf-8"?> 
<rotate xmlns:android="http://schemas.android.com/apk/res/android" 
    android:duration="500" 
    android:fromDegrees="0" 
    android:toDegrees="360" 
    android:pivotX="50%" 
    android:pivotY="50%"> 
 
</rotate> 
 
zoom: 
<?xml version="1.0" encoding="utf-8"?> 
<scale xmlns:android="http://schemas.android.com/apk/res/android" 
    android:duration="500" 
    android:fromXScale="0.5" 
    android:toXScale="0.5" 
    android:fromYScale="1.0" 
    android:toYScale="1.0" 
    android:pivotX="50%" 
    android:pivotY="50%"> 
 
</scale># pgm5
