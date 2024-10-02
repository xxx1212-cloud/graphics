package com.example.grp;

import android.content.Intent;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {
    Button btnAnimation, btnGraphic;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        btnAnimation = findViewById(R.id.btnAnimation);
        btnGraphic = findViewById(R.id.btnGraphic);

        btnAnimation.setOnClickListener(v -> {
            Intent intent = new Intent(MainActivity.this, MainActivity3.class);
            startActivity(intent);
        });

        btnGraphic.setOnClickListener(v -> {
            Intent intent = new Intent(MainActivity.this, MainActivity2.class);
            startActivity(intent);
        });
    }
}


package com.example.grp;

import android.graphics.Bitmap;
import android.graphics.Canvas;
import android.graphics.Color;
import android.graphics.Paint;
import android.os.Bundle;
import android.widget.Button;
import android.widget.ImageView;
import androidx.appcompat.app.AppCompatActivity;

public class MainActivity2 extends AppCompatActivity {
    Button btnRectangle, btnSquare, btnCircle;
    ImageView imageView;
    Bitmap bitmap;
    Canvas canvas;
    Paint paint;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main2);

        imageView = findViewById(R.id.imageView);
        btnRectangle = findViewById(R.id.btnRectangle);
        btnSquare = findViewById(R.id.btnSquare);
        btnCircle = findViewById(R.id.btnCircle);

        bitmap = Bitmap.createBitmap(600, 600, Bitmap.Config.ARGB_8888);
        canvas = new Canvas(bitmap);
        imageView.setImageBitmap(bitmap);

        paint = new Paint();
        paint.setStyle(Paint.Style.FILL);

        btnRectangle.setOnClickListener(v -> {
            paint.setColor(Color.BLUE);
            canvas.drawRect(100, 100, 400, 300, paint);
            imageView.invalidate();
        });

        btnSquare.setOnClickListener(v -> {
            paint.setColor(Color.RED);
            canvas.drawRect(100, 100, 300, 300, paint);
            imageView.invalidate();
        });

        btnCircle.setOnClickListener(v -> {
            paint.setColor(Color.GREEN);
            canvas.drawCircle(250, 250, 100, paint);
            imageView.invalidate();
        });
    }
}


package com.example.grp;

import android.os.Bundle;
import android.view.animation.Animation;
import android.view.animation.AnimationUtils;
import android.widget.Button;
import android.widget.TextView;
import androidx.appcompat.app.AppCompatActivity;

public class MainActivity3 extends AppCompatActivity {
    Button btnFade, btnRotate, btnZoom, btnBlink;
    TextView textView;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main3);

        textView = findViewById(R.id.textView);
        btnFade = findViewById(R.id.button7);
        btnRotate = findViewById(R.id.button8);
        btnZoom = findViewById(R.id.button9);
        btnBlink = findViewById(R.id.button6);

        btnFade.setOnClickListener(v -> {
            Animation fadeAnim = AnimationUtils.loadAnimation(MainActivity3.this, R.anim.fade);
            textView.startAnimation(fadeAnim);
        });

        btnRotate.setOnClickListener(v -> {
            Animation rotateAnim = AnimationUtils.loadAnimation(MainActivity3.this, R.anim.rotate);
            textView.startAnimation(rotateAnim);
        });

        btnZoom.setOnClickListener(v -> {
            Animation zoomAnim = AnimationUtils.loadAnimation(MainActivity3.this, R.anim.zoom);
            textView.startAnimation(zoomAnim);
        });

        btnBlink.setOnClickListener(v -> {
            Animation blinkAnim = AnimationUtils.loadAnimation(MainActivity3.this, R.anim.blink);
            textView.startAnimation(blinkAnim);
        });
    }
}
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <Button
        android:id="@+id/btnAnimation"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Animation"
        android:layout_centerInParent="true" />

    <Button
        android:id="@+id/btnGraphic"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Graphics"
        android:layout_below="@id/btnAnimation"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="20dp"/>
</RelativeLayout>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="match_parent"
        android:layout_height="500dp"
        android:layout_centerInParent="true" />

    <Button
        android:id="@+id/btnRectangle"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Rectangle"
        android:layout_below="@id/imageView"
        android:layout_alignParentStart="true" />

    <Button
        android:id="@+id/btnSquare"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Square"
        android:layout_below="@id/imageView"
        android:layout_centerHorizontal="true" />

    <Button
        android:id="@+id/btnCircle"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Circle"
        android:layout_below="@id/imageView"
        android:layout_alignParentEnd="true" />
</RelativeLayout>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="AKSHATHA"
        android:textSize="24sp"
        android:textStyle="bold"
        android:layout_centerHorizontal="true"
        android:layout_marginBottom="50dp"
        android:layout_alignParentTop="true" />

    <Button
        android:id="@+id/button7"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/textView"
        android:layout_alignParentStart="true"
        android:layout_marginStart="30dp"
        android:layout_marginTop="402dp"
        android:text="Fade" />

    <Button
        android:id="@+id/button8"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/textView"
        android:layout_alignParentEnd="true"
        android:layout_marginTop="510dp"
        android:layout_marginEnd="139dp"
        android:text="Rotate" />

    <Button
        android:id="@+id/button9"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/textView"
        android:layout_alignParentEnd="true"
        android:layout_marginTop="458dp"
        android:layout_marginEnd="40dp"
        android:text="Zoom" />

    <Button
        android:id="@+id/button6"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/textView"
        android:layout_alignParentEnd="true"
        android:layout_marginTop="456dp"
        android:layout_marginEnd="148dp"
        android:text="Blink" />
</RelativeLayout>


<alpha xmlns:android="http://schemas.android.com/apk/res/android"
    android:toAlpha="0.0"
    android:fromAlpha="1.0"
    android:duration="500"
    android:repeatCount="3"
    android:repeatMode="reverse" />

    
<alpha xmlns:android="http://schemas.android.com/apk/res/android"
    android:toAlpha="0.0"
    android:fromAlpha="100.0"
    android:duration="500" />

    
<rotate xmlns:android="http://schemas.android.com/apk/res/android"
    android:duration="500"
    android:fromDegrees="0"
    android:toDegrees="360"
    android:pivotX="50%"
    android:pivotY="50%" />

    
<scale xmlns:android="http://schemas.android.com/apk/res/android"
    android:duration="500"
    android:fromXScale="0.5"
    android:toXScale="1.0"
    android:fromYScale="0.5"
    android:toYScale="1.0"
    android:pivotX="50%"
    android:pivotY="50%" />
