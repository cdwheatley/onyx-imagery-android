# onyx-imagery-android
Sample app demonstrating the Raw, Processed, and Enhanced images that can be obtained with ONYX.  It utlizes the RawBitmapCallback, ProcessedBitmapCallback, and EnhancedBitmapCall
back.

Getting Started
---------------

If you don't already have Android Studio, you can download it <a href="http://developer.android.com/sdk/index.html" target="_blank">here</a>.

Once Android Studio is installed, please contact DFT to purchase your ONYX license <a href="http://www.diamondfortress.com/contact" target="_blank">here</a>. <br />
**Note: Make sure you have updated to the latest Android SDK via the SDK Manager.**

You should receive a license key of the form XXXX-XXXX-XXXX-X-X at your provided e-mail address.
<br />
Next, you can clone our sample repository on the command-line using the following commands:

    > cd <YOUR_DEVELOPMENT_ROOT>
    > git clone https://github.com/DFTinc/onyx-demo-image-pyramiding-android.git

Alternatively, you can clone the project via Android Studio:
<br/>
Select `VCS >> Checkout from Version Control >> GitHub`, and follow the on-screen instructions.

Place the trial key into `onyx-imagery/src/main/res/values/strings.xml` shown below:

    ...
    <string name="onyx_license">XXXX-XXXX-XXXX-X-X</string>
    ...

This sample uses the Gradle build system. To build this project, use the
"gradlew build" command or use "Build >> Make Project" in Android Studio.

Now plug in your compatible device, and select Run >> Run 'onyx-imagery'.

Support
-------

- Diamond Fortress Technologies Support Site: <a href="http://support.diamondfortress.com" target="_blank">support.diamondfortress.com</a>



