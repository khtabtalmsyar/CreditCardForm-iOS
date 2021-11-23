< ?xml version="1.0" encoding="utf-8"?>
< RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
  xmlns:tools="http://schemas.android.com/tools"
  android:layout_width="match_parent"
  android:layout_height="match_parent"
  tools:context="com.codingdemos.creditcardform.MainActivity">

  < com.braintreepayments.cardform.view.CardForm
    android:id="@+id/card_form"
    android:layout_width="match_parent"
    android:layout_height="wrap_content" />

  < Button
    android:id="@+id/btnBuy"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_alignParentBottom="true"
    android:layout_marginBottom="10dp"
    android:layout_marginLeft="40dp"
    android:layout_marginRight="40dp"
    android:layout_marginTop="10dp"
    android:background="@color/colorAccent"
    android:text="@string/label_buy_now"
    android:textColor="@android:color/white" />

< /RelativeLayout>
