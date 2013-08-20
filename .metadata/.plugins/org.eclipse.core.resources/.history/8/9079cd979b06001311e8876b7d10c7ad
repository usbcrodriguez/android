package com.usb.aplicacion1;

import android.os.Bundle;

// Activity - Ventanas
// Views - Controles
import android.app.Activity;
import android.view.Menu;
import android.widget.Button;
import android.widget.EditText;
import android.widget.LinearLayout;
import android.widget.TextView;

// Button
// EditText

public class MainActivity extends Activity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        LinearLayout layout;
        TextView tv = new TextView(this);
        EditText caja1 = new EditText(this);
        Button boton = new Button(this);
        
        boton.setText("Aceptar");
        layout = new LinearLayout(this);
        tv.setText("text");
        layout.addView(tv);
        layout.addView(caja1);
        layout.addView(boton);
        
        layout.setOrientation(LinearLayout.VERTICAL);
        this.setContentView(layout);
        
        
        
        
    }

    @Override
    public boolean onCreateOptionsMenu(Menu menu) {
        // Inflate the menu; this adds items to the action bar if it is present.
        getMenuInflater().inflate(R.menu.activity_main, menu);
        return true;
    }
    
}
