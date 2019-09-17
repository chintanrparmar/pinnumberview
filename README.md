# pinnumberview
Pin Number Edittext Library

To add library simply add   implementation <b>'com.github.chintanrparmar:pinnumberview:v1.0.0'</b> in your app level gradle file.

Then go to your XML layout and add the following code.

    <com.crp.pinnumberview.PinNumberView
        android:layout_marginStart="30dp"
        android:layout_marginEnd="30dp"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:cursorVisible="false"
        android:digits="1234567890"
        android:inputType="number"
        android:id="@+id/txt_pin_entry"
        android:maxLength="6"
        android:textIsSelectable="false"
        android:textSize="20sp" />

