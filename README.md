# Android Camera2 Barcode Sample
The sample demonstrates how to scan barcodes from fast moving objects by adjusting the shutter speed. The code implementation is based on [Android Camera2Basic](https://github.com/googlesamples/android-Camera2Basic) and [Dynamsoft Barcode Reader](https://www.dynamsoft.com/Products/barcode-scanner-sdk-android.aspx). 

## Usage
1. Get a valid [trial license](https://www.dynamsoft.com/CustomerPortal/Portal/Triallicense.aspx) of Dynamsoft Barcode SDK.
2. Open the project in `Android Studio`.
3. Set the license in `Camera2BasicFragment.java`:

    ```java
    mBarcodeReader = new BarcodeReader("LICENSE-KEY"); 
    ```

4. Build and run the app:

    ![Android Camera2 Barcode](https://www.codepool.biz/wp-content/uploads/2019/05/android-camera2-barcode.gif)


