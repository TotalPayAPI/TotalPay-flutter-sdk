# TotalPay-flutter-sdk
![](https://jitpack.io/v/TotalPay/TotalPay-android-sdk.svg) | [View SDK Wiki](https://github.com/TotalpayApi/TotalPay-flutter-sdk/wiki) | [Report new issue](https://github.com/TotalpayApi/TotalPay-flutter-sdk/issues/new)

# TotalPay Flutter SDK

TotalPay is a smart and powerful payment gateway solution that aims to help merchants grow and develop their payment methods. We allow for a better and unified online commerce experience for shoppers and merchants alike, aiming to simplify the complexities of payments to help you grow.

<p align="center">
  <a href="https://totalpay.global">
      <img src="/media/header.png" alt="TotalPay" width="400px"/>
  </a>
</p>


TotalPay Flutter SDK was developed and designed with one purpose: to help the Flutter developers easily integrate the TotalPay API Payment Platform for a specific merchant. 

To properly set up the SDK, read [Wiki](https://github.com/TotalpayApi/TotalPay-flutter-sdk/wiki) first.

To get used to the SDK, download a [sample app](https://github.com/TotalpayApi/TotalPay-flutter-sdk/blob/main/totalpay_sdk-1.0.9.zip).

## Setup and Installation

This Flutter plugin is based on iOS and Android native libraries. You need to add the jitpack repository support and credentials to the gradle to access the secured Android library. Follow Below

**Setup Android** Add to the root build.gradle in Android Project at Path:(${ProjectRoot}/android/build.gradle):

```groovy

allprojects {
    repositories {
        ...
        jcenter()
        maven {
            url 'https://jitpack.io'
            credentials { username 'jp_tjnosefflebgig8l3i0q6cgf09' }
        }
    }
}
```

Setup iOS iOS does not required any setup just install flutter plugin where the iOS framewework is embedded within the plugin in iOS plaform directory. If you need to enable Apple Pay in your app it can be enable by following the instructions at [Link](https://github.com/TotalpayApi/TotalPay-flutter-sdk/wiki/TotalPay-ApplePay-Payment)

## Installting Flutter Plugin

In the dependencies: section of your pubspec.yaml, add the following lines:

```groovy

dependencies:
  intl: ^0.17.0
  totalpay_sdk: any
  
```

## Initialize SDK

```groovy

TotalpaySdk.instance.config(
    key: MERCHANT_CLIENT_KEY, // Your Secret Merchant Key
    password: MERCHANT_CLIENT_PASSWORD,  // Your Secret Merchant Password
    enableDebug: true
);

``` 
[More Details](https://github.com/TotalpayApi/TotalPay-flutter-sdk/wiki)

##Quick Payment Implementation

[Card Payment for IOS/Android](https://github.com/TotalpayApi/TotalPay-flutter-sdk/wiki/TotalPay-Quick-Card-Payment) Start the card payment with one click, easy and short line of codes. It will help the developer to easily implement the payment using card in thier application. click the link for easy steps to start payments.

[ApplePay Payment for IOS](https://github.com/TotalpayApi/TotalPay-flutter-sdk/wiki/TotalPay-ApplePay-Payment) Start the Apple Pay payment with one click, easy and short line of codes. It will help the developer to easily implement the payment using ApplePay in thier application. the developer just need to configure and enable the Apple Pay in thier AppleDeveloper Account and call the simple function. click the link for easy steps to start payments with ApplePay.

## Getting help

To report a specific issue or feature request, open a [new issue](https://github.com/TotalpayApi/TotalPay-flutter-sdk/issues).

Or write a direct letter to the [support@totalpay.global](mailto:support@totalpay.global).

## License

MIT License. See the [LICENSE](https://github.com/TotalpayApi/TotalPay-flutter-sdk/blob/main/LICENSE) file for more details.

## Contacts

Website: [https://totalpay.global](https://totalpay.global)

Email: info@totalpay.global

Address: TotalPay Payment Services Provicer LLC - UAE 



© 2022 TotalPay. All rights reserved
