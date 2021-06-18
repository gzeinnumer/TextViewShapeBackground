# TextViewShapeBackground

<p align="center">
  <img src="https://github.com/gzeinnumer/TextViewShapeBackground/blob/master/preview/example1.png"/>
</p>

#

- View
```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:gravity="center"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginEnd="5dp"
        android:background="@drawable/shape_green"
        android:paddingStart="5dp"
        android:paddingEnd="5dp"
        android:text="Hello"
        android:textColor="@color/white" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:background="@drawable/shape_red"
        android:paddingStart="5dp"
        android:paddingEnd="5dp"
        android:text="World!"
        android:textColor="@color/white" />

</LinearLayout>
```

- [res/drawable/shape_green.xml](https://github.com/gzeinnumer/TextViewShapeBackground/blob/master/app/src/main/res/drawable/shape_green.xml)
- [res/drawable/shape_red.xml](https://github.com/gzeinnumer/TextViewShapeBackground/blob/master/app/src/main/res/drawable/shape_red.xml)

---

```
Copyright 2021 M. Fadli Zein
```
