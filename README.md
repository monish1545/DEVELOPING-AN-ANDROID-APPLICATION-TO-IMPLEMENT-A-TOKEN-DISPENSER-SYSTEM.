# DEVELOPING-AN-ANDROID-APPLICATION-TO-IMPLEMENT-A-TOKEN-DISPENSER-SYSTEM.

## AIM:
To develop an android application to perform Token dispenser

## APPARATUS REQUIRED:
ØComputer
ØAndroid studio software


## THEORY:
The Token Dispenser App generates unique tokens for users in a queue-like system. The app allows users to input their name and receive a token number upon clicking a button. The token is displayed, and a list of previously generated tokens is maintained and shown in a ListView. This experiment demonstrates how to manage dynamic lists and use array adapters in Android for displaying data. It also introduces handling user input, generating unique tokens, and managing collections like arrays and lists. The Token Dispenser App is an excellent introduction to queue management and creating interactive applications where users can receive sequential outputs.


## PROCEDURE:
1. Open Android Studio and then click on File -> New -> New project. 46. Then type the application name as “ex.no.5″ and click Next.
2. Then select the Minimum SDK as shown below and click next. 48. Then select the Empty Activity and click next.
3. Finally click Finish.
4. Click on app -> java -> com.example -> MainActivity.java
5. Now click on Text and type the program, so now the programming part of the main activity is completed.
6. Click on app -> res -> layout -> activity_main.xml.
7. Now click on Text and type the program, so now the designing part of Activity main is also completed.
8. Select the suitable available device to display the output. 55. Now run the application to see the output. 

## PROGRAM:
```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout 
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="20dp">

    <TextView
        android:id="@+id/titleText"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Token Dispenser"
        android:textSize="24sp"
        android:textStyle="bold"
        android:layout_gravity="center"
        android:paddingBottom="16dp" />

    <EditText
        android:id="@+id/nameInput"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="Enter your name"
        android:inputType="textPersonName" />

    <Button
        android:id="@+id/getTokenButton"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Get Token"
        android:layout_marginTop="10dp" />

    <TextView
        android:id="@+id/tokenDisplay"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Issued: "
        android:textSize="18sp"
        android:textStyle="italic"
        android:layout_marginTop="16dp" />

    <ListView
        android:id="@+id/tokenListView"
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1"
        android:layout_marginTop="10dp" />
</LinearLayout>
```


## OUTPUT:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/82a65a2a-8e89-41ff-b150-48a091f26637" />

## RESULT:
Thus, the Android app for generating and tracking token numbers in a queue is developed and the output is verified. 

