# Komodo Contact Android App

This repository contains the source code for [Komodo Contacts](http://www.komodocontacts.com/)
Android app available from [Google Play](https://play.google.com/store/apps/details?id=com.komodo.contacts).

Please see the [issues](https://github.com/radiofrequency/komodo-contacts-android/issues) section
to report any bugs or feature requests and to see the list of known issues.

<a href="https://play.google.com/store/apps/details?id=com.komodo.contacts" alt="Download from Google Play">
  <img src="http://www.komodocontacts.com/images/device_new.png">
</a>

## License

* [Apache Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

## Building

The build requires the [Android SDK](http://developer.android.com/sdk/index.html)
to be installed in your development environment. In addition you'll need to put the SDK platform-tools and
tools directory in your PATH.

    export PATH=/home/rf/tools/android-sdk/platform-tools:/home/rf/tools/android-sdk/tools/

After satisfying those requirements, the build is pretty simple:

    git clone https://github.com/radiofrequency/komodo-contacts-android
    cd komodo-contacts-android
    android update project -p .
    ant debug install

## Contributing

Please fork this repository and contribute back using
[pull requests](https://github.com/radiofrequency/komodo-contacts-android/pulls).

