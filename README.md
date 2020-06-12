M0_ReactNative_TS

K6B.
React Native TypeScript empty project for OS setup test (type M0).

According to https://reactnative.dev/docs/environment-setup.

NOTE:
npx react-native init AwesomeTSProject --template react-native-template-typescript
installs with some errors.

Here was used next steps:

npx react-native init AwesomeJSProject;
cd AwesomeJSProject;
npx react-native init AwesomeTSProject --template react-native-template-typescript;
(React Native logo displays while install);
And move folder AwesomeTSProject from AwesomeJSProject;

Result file sizes (JSC - JavaScript compiler, H - Hermes engine):

app-arm64-v8a-release-H.apk       4 957 217

app-arm64-v8a-release-JSC.apk     6 927 390

app-armeabi-v7a-release-H.apk     4 637 769

app-armeabi-v7a-release-JSC.apk   6 558 790

app-release-H.aab                14 685 192

app-release-H.apk                14 787 809

app-release-JSC.aab              22 777 688

app-release-JSC.apk              22 856 917

app-x86_64-release-H.apk          5 219 301

app-x86_64-release-JSC.apk        7 398 370

app-x86-release-H.apk             5 280 681

app-x86-release-JSC.apk           6 865 830
