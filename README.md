<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    android:background="#ececec">

<ScrollView
    android:layout_width="414dp"
    android:layout_height="733dp"
    tools:layout_editor_absoluteY="-2dp"
    tools:ignore="MissingConstraints">
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical">

        <androidx.constraintlayout.widget.ConstraintLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent">

            <ImageView
                android:id="@+id/imageView2"
                android:layout_width="418dp"
                android:layout_height="251dp"
                android:scaleType="fitXY"
                app:layout_constraintBottom_toBottomOf="parent"
                app:layout_constraintEnd_toEndOf="parent"
                app:layout_constraintHorizontal_bias="0.571"
                app:layout_constraintStart_toStartOf="parent"
                app:layout_constraintTop_toTopOf="parent"
                app:layout_constraintVertical_bias="0.0"
                app:srcCompat="@drawable/triangles_1430105_1280"
                android:contentDescription="@string/todo"
                tools:ignore="ContentDescription" />

            <ImageView
                android:id="@+id/imageView3"
                android:layout_width="wrap_content"
                android:layout_height="135dp"
                app:layout_constraintBottom_toBottomOf="@id/imageView2"
                app:layout_constraintEnd_toEndOf="parent"
                app:layout_constraintStart_toStartOf="@id/imageView2"
                app:layout_constraintTop_toBottomOf="@id/imageView2"
                app:srcCompat="@drawable/profile"
                android:contentDescription="@string/todo1" />

            <TextView
                android:id="@+id/textView"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="@string/putut_adi_prakoso"
                android:layout_margin="16dp"
                android:textSize="25sp"
                android:textStyle="bold"
                app:layout_constraintEnd_toEndOf="@id/imageView3"
                app:layout_constraintStart_toStartOf="@id/imageView3"
                app:layout_constraintTop_toBottomOf="@id/imageView3"/>

            <TextView
                android:id="@+id/textView2"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="@string/pututadi505_gmail_com"
                android:textSize="20sp"
                app:layout_constraintEnd_toEndOf="@id/textView"
                app:layout_constraintStart_toStartOf="@id/textView"
                app:layout_constraintTop_toBottomOf="@id/textView" />

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:orientation="vertical"
                app:layout_constraintStart_toStartOf="parent"
                app:layout_constraintTop_toBottomOf="@id/textView2">

                <Button
                    android:id="@+id/button"
                    android:layout_width="match_parent"
                    android:layout_height="60dp"
                    android:layout_marginStart="32dp"
                    android:layout_marginTop="10dp"
                    android:layout_marginEnd="32dp"
                    android:layout_marginBottom="10dp"
                    android:background="@drawable/btn_background_1"
                    android:drawablePadding="20dp"
                    android:text="@string/my_profile"
                    android:textSize="18sp"
                    android:textStyle="bold"
                    style="@android:style/Widget.Button"
                    android:textAlignment="center"/>

                <Button
                    android:id="@+id/button1"
                    android:layout_width="match_parent"
                    android:layout_height="60dp"
                    android:layout_marginStart="32dp"
                    android:layout_marginTop="10dp"
                    android:layout_marginEnd="32dp"
                    android:layout_marginBottom="10dp"
                    android:background="@drawable/btn_background_1"
                    android:drawablePadding="20dp"
                    android:text="@string/my_experience"
                    android:textSize="18sp"
                    android:textStyle="bold"
                    style="@android:style/Widget.Button"
                    android:textAlignment="center"/>

                <Button
                    android:id="@+id/button2"
                    android:layout_width="match_parent"
                    android:layout_height="60dp"
                    android:layout_marginStart="32dp"
                    android:layout_marginTop="10dp"
                    android:layout_marginEnd="32dp"
                    android:layout_marginBottom="10dp"
                    android:background="@drawable/btn_background_1"
                    android:drawablePadding="20dp"
                    android:text="@string/educational_background"
                    android:textSize="18sp"
                    android:textStyle="bold"
                    style="@android:style/Widget.Button"
                    android:textAlignment="center"/>
            </LinearLayout>

        </androidx.constraintlayout.widget.ConstraintLayout>

    </LinearLayout>
</ScrollView>
</androidx.constraintlayout.widget.ConstraintLayout>
