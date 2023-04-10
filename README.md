# kalkulator2
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">


    <TextView
        android:id="@+id/angka"
        android:layout_width="match_parent"
        android:layout_height="70dp"
        android:layout_marginLeft="300dp"
        android:layout_marginTop="220dp"
        android:text="0"
        android:textAlignment="center"
        android:textSize="50dp">

    </TextView>

    <GridLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="308dp"
        android:rowCount="5"
        android:columnCount="4">

        <Button
            android:id="@+id/clear_btn"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="C"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="0"
            android:layout_column="0"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/persen_btn"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="%"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="0"
            android:layout_column="1"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/hapus_btn"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="<-"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="0"
            android:layout_column="2"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/bagi_btn"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="/"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="0"
            android:layout_column="3"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>


        <Button
            android:id="@+id/btn7"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="7"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="1"
            android:layout_column="0"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/btn8"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:layout_row="1"
            android:layout_column="1"
            android:layout_columnWeight="1"
            android:textColor="@color/white"
            android:background="@color/black"
            android:onClick="onButtonClicked"
            android:text="8"
            android:textSize="28sp" />

        <Button
            android:id="@+id/btn9"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="9"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="1"
            android:layout_column="2"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/kali_btn"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="X"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="1"
            android:layout_column="3"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/btn4"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="4"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="2"
            android:layout_column="0"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/btn5"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="5"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="2"
            android:layout_column="1"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/btn6"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="6"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="2"
            android:layout_column="2"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/kurang_btn"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="-"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="2"
            android:layout_column="3"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/btn1"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="1"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="3"
            android:layout_column="0"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/btn2"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="2"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="3"
            android:layout_column="1"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/btn3"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="3"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="3"
            android:layout_column="2"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/tambah_btn"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="+"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="3"
            android:layout_column="3"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/btn0"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="0"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="4"
            android:layout_column="0"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/btn00"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="00"
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="4"
            android:layout_column="1"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/koma_btn"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text=","
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="4"
            android:layout_column="2"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>

        <Button
            android:id="@+id/hasil_btn"
            android:layout_width="wrap_content"
            android:layout_height="85dp"
            android:text="="
            android:textColor="@color/white"
            android:background="@color/black"
            android:textSize="28sp"
            android:layout_row="4"
            android:layout_column="3"
            android:layout_columnWeight="1"
            android:onClick="onButtonClicked"/>


    </GridLayout>


</RelativeLayout>
