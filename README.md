<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="200dp"
        android:layout_height="200dp"
        android:orientation="vertical"
        android:src="@drawable/logo"
        android:layout_marginTop="150dp"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        tools:ignore="ContentDescription"
        android:contentDescription="@string/todo"/>

    <EditText
        android:id="@+id/account"
        android:layout_width="414dp"
        android:layout_height="59dp"
        android:layout_marginTop="-50dp"
        android:background="@drawable/edittext"
        android:hint="@string/phone_number_email_or_username"
        android:importantForAutofill="no"
        android:textColorHint="@color/cardview_shadow_start_color"
        android:textSize="20sp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView"
        tools:ignore="LabelFor,TextFields,VisualLintBounds,TextContrastCheck" />

    <EditText
        android:id="@+id/passwordField"
        android:layout_width="414dp"
        android:layout_height="59dp"
        android:layout_margin="16dp"
        android:layout_marginTop="16dp"
        android:background="@drawable/edittext"
        android:hint="@string/password1"
        android:importantForAutofill="no"
        android:padding="15dp"
        android:textColorHint="@color/cardview_shadow_start_color"
        android:textSize="20sp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@id/account"
        tools:ignore="LabelFor,TextFields,VisualLintBounds,TextContrastCheck" />

    <Button
        android:id="@+id/button"
        android:layout_width="300dp"
        android:layout_height="70dp"
        android:text="@string/log_in"
        android:textColor="@color/white"
        android:backgroundTint="#764CA1"
        android:layout_margin="16dp"
        android:textAllCaps="false"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/passwordField"
        app:layout_constraintEnd_toEndOf="parent"/>

    <TextView
        android:id="@+id/textView"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:gravity="center"
        android:text="@string/english_united_states"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintEnd_toEndOf="parent"/>

    <TextView
        android:id="@+id/textForgot"
        android:layout_width="290dp"
        android:layout_height="26dp"
        android:layout_marginTop="550dp"
        android:text="@string/forgot_your_login_details"
        android:textSize="15sp"
        android:textStyle="normal"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@+id/textView"
        tools:ignore="TextSizeCheck" />

    <TextView
        android:layout_width="310dp"
        android:layout_height="26dp"
        android:layout_marginStart="368dp"
        android:layout_marginTop="550dp"
        android:text="@string/get_help_logging_in"
        android:textSize="15sp"
        android:textStyle="bold"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@+id/textView"
        tools:ignore="VisualLintBounds,TextSizeCheck" />

    <TextView
        android:layout_width="390dp"
        android:layout_height="30dp"
        android:layout_marginTop="577dp"
        android:gravity="center"
        android:text="@string/or"
        android:textSize="20sp"
        android:textStyle="normal"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        tools:ignore="TextSizeCheck" />

    <View
        android:layout_width="300dp"
        android:layout_height="3dp"
        android:background="@drawable/edittext"
        android:layout_marginTop="575dp"
        android:layout_marginEnd="330dp"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        tools:ignore="VisualLintBounds" />
    <View
        android:layout_width="300dp"
        android:layout_height="3dp"
        android:background="@drawable/edittext"
        android:layout_marginTop="575dp"
        android:layout_marginStart="330dp"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        tools:ignore="VisualLintBounds" />

    <TextView
        android:layout_width="250dp"
        android:layout_height="30dp"
        android:layout_marginTop="74dp"
        android:gravity="center"
        android:text="@string/log_in_with_facebook"
        android:textColor="@color/material_dynamic_primary60"
        android:textSize="19sp"
        android:textStyle="bold"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@+id/textForgot"
        tools:ignore="TextSizeCheck" />

    <TextView
        android:layout_width="250dp"
        android:layout_height="30dp"
        android:layout_marginTop="870dp"
        android:text="@string/don_t_have_an_account"
        android:textSize="16sp"
        android:textStyle="normal"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        tools:ignore="VisualLintBounds,TextSizeCheck" />

    <TextView
        android:layout_width="415sp"
        android:layout_height="26sp"
        android:layout_marginTop="870dp"
        android:layout_marginEnd="-495dp"
        android:text="@string/sign_up"
        android:textSize="16sp"
        android:textStyle="bold"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        tools:ignore="VisualLintBounds,TextSizeCheck" />

</androidx.constraintlayout.widget.ConstraintLayout>
