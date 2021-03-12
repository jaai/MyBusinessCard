# i_am_rich

A new Flutter application.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


4

Yes it is. Open CMD in your project directory.

You need to enable web support for flutter. use following command to do that.

flutter channel beta

flutter upgrade

flutter config --enable-web
If you want your existing flutter project to run on web then in your project directory you should call flutter create . command. This will create a web project if it is not created already.

Use flutter devices command, you should see chrome as a device.

In device list of Android studio it will show you the option to run your project on web.

You can do the same using command line too. Use flutter run -d chrome command to run your project on web.
