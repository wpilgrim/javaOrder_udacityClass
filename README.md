# javaOrder_udacityClass
coding for javaorder

<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    tools:context="com.example.apilgrim.javaorder.MainActivity">

    <TextView
        android:id="@+id/textView1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Quantity"
        android:paddingBottom="16dp"
        android:textAllCaps="true" />

    <Button
        android:id="@+id/buttonpos"
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:text="+"
        android:textAllCaps="true"
        android:textSize="24sp"
        android:onClick="increment"/>

    <TextView
        android:id="@+id/quantity_text_view"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="2"
        android:textAllCaps="true"
        android:textColor="#000000"
        android:textSize="16sp" />

    <Button
        android:id="@+id/buttonneg"
        android:layout_width="48dp"
        android:layout_height="48dp"
        android:text="-"
        android:textSize="24sp"
        android:textAllCaps="true"
        android:onClick="decrement"/>

    <TextView
        android:id="@+id/textView3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Price"
        android:paddingBottom="16dp"
        android:paddingTop="16dp"
        android:textAllCaps="true" />

    <TextView
        android:id="@+id/price_text_view"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="$0"
        android:textColor="#000000"
        android:paddingBottom="16dp"
        android:textAllCaps="true" />

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="order"
        android:textAllCaps="true"
        android:onClick="submitOrder"/>


</LinearLayout>
