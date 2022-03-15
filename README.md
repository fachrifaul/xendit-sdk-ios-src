# xendit-sdk-ios-src

## Ownership

Team: [Credit Cards Team](https://www.draw.io/?state=%7B%22ids%22:%5B%221Vk1zqYgX2YqjJYieQ6qDPh0PhB2yAd0j%22%5D,%22action%22:%22open%22,%22userId%22:%22104938211257040552218%22%7D)

Slack Channel: [#p-cards-product](https://xendit.slack.com/messages/p-cards-product)

Slack Mentions: `@troops-cards`

## Running Tests
1. Install [Cocoapods](https://cocoapods.org/) by running `sudo gem install cocoapods`. Additionally, you can read how to setup and use it in you app [here](https://guides.cocoapods.org/using/using-cocoapods.html). (Ruby is required)
2. In console open repository root folder and install test dependencies by running `pod install`
3. Open `Xendit.xcworkspace`

To run UI tests: choose `Xendit` scheme and press `cmd+u` (or "Run Product" -> "Test")
To run unit tests: choose `XenditExample` scheme and press `cmd+u`



## Run the app

### Prerequisite
- Latest xcode version
- Cocoapods installed

1. Open your terminal, go to the repository root folder on the  and run `pod install`

2. Open xcode, click on the `Open a project or file`

<img width="809" alt="Screen Shot 2020-12-08 at 11 17 45" src="https://user-images.githubusercontent.com/16671326/101439516-3a639c80-3947-11eb-96de-f5aa518dd45b.png">

3. Browse to the repository folder, and open `Xendit.xcworkspace`

<img width="643" alt="Screen Shot 2020-12-08 at 11 18 18" src="https://user-images.githubusercontent.com/16671326/101439618-6e3ec200-3947-11eb-96c8-2087dcfdcea8.png">

4. Click the project scheme button (its beside stop button)

<img width="319" alt="Screen Shot 2020-12-08 at 11 23 22" src="https://user-images.githubusercontent.com/16671326/101439776-d8effd80-3947-11eb-8218-9f621762a8f5.png">



5. A dropdown list will appear, click `Edit scheme...`

<img width="197" alt="Screen Shot 2020-12-08 at 11 24 26" src="https://user-images.githubusercontent.com/16671326/101439832-fde47080-3947-11eb-97ae-14f619a68d86.png">

6. On the `Run` section, at the `Info` tab, click the `Executable` dropdown

<img width="888" alt="Screen Shot 2020-12-08 at 11 28 21" src="https://user-images.githubusercontent.com/16671326/101440128-a4c90c80-3948-11eb-89d7-570f0dabc638.png">

7. Select `XenditExample.app` and `Close` the window

<img width="901" alt="Screen Shot 2020-12-08 at 11 30 31" src="https://user-images.githubusercontent.com/16671326/101440250-e954a800-3948-11eb-94a3-17d302948fd4.png">

8. Click the `Run` button

<img width="335" alt="Screen Shot 2020-12-08 at 11 32 29" src="https://user-images.githubusercontent.com/16671326/101440380-2d47ad00-3949-11eb-9615-c6aaa5928394.png">


9. Wait for the app build and the simulator will showed up

<img width="434" alt="Screen Shot 2020-12-08 at 11 34 43" src="https://user-images.githubusercontent.com/16671326/101440486-66801d00-3949-11eb-8212-d5307ad0f5cb.png">



## Swift Package Manager

Xendit iOS SDK is compatible with Swift Package Manager, and provides target for consumption: `Xendit`.

### Run the app using SPM dependency

1. Open xcode, click on the `Open a project or file`

<img width="809" alt="Screen Shot 2020-12-08 at 11 17 45" src="https://user-images.githubusercontent.com/16671326/101439516-3a639c80-3947-11eb-96de-f5aa518dd45b.png">

2. Browse to the repository folder, and open `XenditExample.xcodeproj`

<img width="912" alt="Screenshot 2022-03-15 at 1 39 40 PM" src="https://user-images.githubusercontent.com/36880960/158318491-5ea5997d-26bf-4907-bd51-d3341f345525.png">

3. Click the `XenditExample` target, remove any framework from the list `Frameworks, Libraries, and Embedded Content`

<img width="865" alt="Screenshot 2022-03-15 at 1 45 50 PM" src="https://user-images.githubusercontent.com/36880960/158318576-9da7892e-5522-4c4d-8f91-07f690048bf8.png">

4. On the `XenditExample` project, add our SDK from `Package Dependencies`

<img width="870" alt="Screenshot 2022-03-15 at 2 10 14 PM" src="https://user-images.githubusercontent.com/36880960/158318641-9d2fa77f-f6b2-4a9e-9d0a-b5f6348f1e39.png">

5. Enter the package URL as `https://github.com/xendit/xendit-sdk-ios-src.git`, Dependency Rule `Up to Next Major Version` from `3.6.0`

<img width="1080" alt="Screenshot 2022-03-15 at 10 11 26 PM" src="https://user-images.githubusercontent.com/36880960/158397849-5fd4f311-4ed4-4df5-a257-cd332462ce41.png">

<img width="870" alt="Screenshot 2022-03-15 at 10 13 34 PM" src="https://user-images.githubusercontent.com/36880960/158397994-9253f9ab-124c-443e-b31c-5e09bcf0d4da.png">

6. Click the `Run` button

<img width="340" alt="Screenshot 2022-03-15 at 2 14 26 PM" src="https://user-images.githubusercontent.com/36880960/158318699-50a4bea4-1a33-46a6-8cbc-d7acd9f6ef88.png">

7. Wait for the app build and the simulator will showed up

<img width="506" alt="Screenshot 2022-03-15 at 1 52 03 PM" src="https://user-images.githubusercontent.com/36880960/158318729-8703e622-b652-4044-8329-3af751942429.png">
