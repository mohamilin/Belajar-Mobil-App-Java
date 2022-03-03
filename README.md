# Belajar Membuat Mobile App with Java

## Overview
```html
<p>Jadi saya diminta oleh CEO <h1>penulis.id</h1> untuk belajar mobile app dengan java, karena akan produk yang dibangun dalam bentuk mobile app (codebas: java).  Sebelumnya belum pernah belajar java. Akhirnya saya ikut kelas <strong>dicoding</strong>. Nah project didalam repo ini sebagai latihan saya dalam belajar pengembangan mobile app (codebas : java) Ingat yaa... JAVA</p>
<hr>
<p>Mungkin untuk kedepannya perlu belajar kotlin atau flutter, Basicly saya seorang backend</p>
```

## Project 1 : BarVolume
1. Bikin new Project pake Android Studio
2. Setelah masuk kedalam project : pilih `activity_main.xml`, lalu singkat ceritnya code sebagai berikut :
   ```xml
    <?xml version="1.0" encoding="utf-8"?>
    <LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:app="http://schemas.android.com/apk/res-auto"
        xmlns:tools="http://schemas.android.com/tools"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:padding="16dp"
        android:orientation="vertical"
        tools:context=".MainActivity">

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="@string/length" />
        <EditText
            android:id="@+id/edt_length"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:inputType="numberDecimal"
            android:lines="1"/>
        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="@string/width"/>
        <EditText
            android:id="@+id/edt_width"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:lines="1"/>
        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="@string/height"/>
        <EditText
            android:id="@+id/edt_height"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:lines="1"/>
        <Button
            android:id="@+id/btn_calculate"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="@string/calculate"/>
        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:text="@string/result"
            android:textSize="24sp"
            android:textStyle="bold"/>
    </LinearLayout>
   ```
3. sdsd
4. 