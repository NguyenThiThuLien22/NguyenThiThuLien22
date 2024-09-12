<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/login_bachkground"
    android:gravity="center"
    android:padding="16dp"
    tools:context=".MainActivity">
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:gravity="center"
        android:orientation="vertical">
        <ImageView
            android:layout_width="160dp"
            android:layout_height="160dp"
            android:src="@drawable/icon_account_circle"/>
<EditText
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:hint="Username"
    android:textColor="@color/white"
    android:textSize="20sp"
    android:background="@drawable/rounded_corner"
    android:padding="18dp"
    android:inputType="text"
    android:id="@+id/username_input"/>
        <EditText
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginTop="16dp"
            android:hint="Password"
            android:textColor="@color/white"
            android:textSize="20sp"
            android:background="@drawable/rounded_corner"
            android:padding="18dp"
            android:inputType="textPassword"
            android:id="@+id/Password_input"/>
        <Button
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Login"
            android:background="@color/white"
            android:textColor="#3B84F1"
            android:padding="18dp"
            android:layout_marginTop="32dp"
            android:textSize="20sp"
            android:id="@+id/login_bth"/>
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Social Login"
            android:textSize="18sp"
            android:textColor="@color/white"
            android:layout_marginTop="32dp"/>
        <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="horizontal"
                android:layout_marginTop="8dp"
                android:gravity="center"/>

        <ImageView
            android:layout_width="64dp"
            android:layout_height="64dp"
            android:layout_margin="16dp"
            android:id="@+id/img_btn"
            android:src="@drawable/img_2" />


    </LinearLayout>
</RelativeLayout>
