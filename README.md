# exe1
实验一截图：
https://github.com/7419adf/exe1/blob/master/images/activity%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F.png
https://github.com/7419adf/exe1/blob/master/images/hello%20world.png

主要代码：

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Log.i("MainActivityLife","调用onCreate()");
    }
    @Override
    protected void onStart() {
        super.onStart();
        Log.i("MainActivityLife","调用onStart()");
    }
    @Override
    protected void onResume() {
        super.onResume();
        Log.i("MainActivityLife","调用onResume()");
    }
    @Override
    protected void onPause() {
        super.onPause();
        Log.i("MainActivityLife","调用onPause()");
    }
    @Override
    protected void onStop(){
        super.onStop();
        Log.i("MainActivityLife","调用onStop()");
    }
    @Override
    public void onDestroy() {
        super.onDestroy();
        Log.i("MainActivityLife","调用onDestroy()");
    }
    @Override
    public void onRestart(){
        super.onRestart();
        Log.i("MainActivityLife","调用onRestart()");
    }



    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />



