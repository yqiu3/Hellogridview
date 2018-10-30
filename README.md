|layout|
|---|
|home|
# Hellogridview

 &emsp;&emsp;In this project, I try to use linear layout in it. I changed the code in the activity_main.xml which is in the foder layout.
 Here is the code I used.
 ```javascript
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout
        xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:tools="http://schemas.android.com/tools"
        xmlns:app="http://schemas.android.com/apk/res-auto"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        tools:context=".MainActivity">


    <LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
                  android:layout_width="match_parent"
                  android:layout_height="match_parent"
                  android:paddingLeft="16dp"
                  android:paddingRight="16dp"
                  android:orientation="vertical" >
        <EditText
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:hint="Name" />
        <EditText
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:hint="SEX" />
        <EditText
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:gravity="top"
                android:hint="Introduce yourself" />
        <Button
                android:layout_width="100dp"
                android:layout_height="wrap_content"
                android:layout_gravity="right"
                android:text="upload" />
    </LinearLayout>



</android.support.constraint.ConstraintLayout>
```

&emsp;&emsp;You can find the source code here [linear layout](https://developer.android.com/guide/topics/ui/layout/linear)
