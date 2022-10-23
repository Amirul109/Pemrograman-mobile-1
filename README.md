# Template Awal - DESIGN UI
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:padding="20dp"
    tools:context=".MainActivity">

    <Button
        android:id="@+id/button"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Scan Qr Code"
        android:layout_alignParentBottom="true"/>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical">

        <TextView
            android:id="@+id/textView"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="nama" />

        <TextView
            android:id="@+id/textView2"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="xyz"
            android:textAppearance="@style/TextAppearance.AppCompat.Large"/>

        <ImageView
            android:id="@+id/imageView"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            tools:srcCompat="@tools:sample/backgrounds/scenic" />
    </LinearLayout>
</RelativeLayout>

![Screenshot (38)](https://user-images.githubusercontent.com/116171779/197368209-be8d304a-f710-4e87-8fcd-d663d113c306.png)




# Pemrograman-mobile-1
<?xml version="1.0" encoding="utf-8"?>
    <RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:app="http://schemas.android.com/apk/res-auto"
        xmlns:tools="http://schemas.android.com/tools"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical"
        android:padding="10dp"
        tool:context="MainActivity">

    <Button
            android:id="@+id/buttonScan"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Scan QR Code"
            android:layout_alignParentBottom="true" />

    <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:layout_centerVertical="true">

            <TextView
                android:id="@+id/textView"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Nama" />
            <TextView
                android:id="@+id/textViewNama"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Amirul Mu'minin"
                android:textAppearance="@style/TextAppearance.AppCompat.Large" />

            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="Kelas" />

            <TextView
                android:id="@+id/textViewKelas"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="TI.21.C2"
                android:textAppearance="@style/TextAppearance.AppCompat.Large" />

            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="NIM" />

            <TextView
                android:id="@+id/textViewNIM"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="312110109"
                android:textAppearance="@style/TextAppearance.AppCompat.Large"


        <ImageView
            android:id="@+id/imageView"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            tools:srcCompat="@tools:sample/backgrounds/scenic" />
    </LinearLayout>
    </RelativeLayout>
![Screenshot (36)](https://user-images.githubusercontent.com/116171779/197367664-59f2d40d-87de-43de-9558-61a1a6b6d493.png)
