# Installing the launcher

## Android
Instructions for installing Amethyst on Android devices.

::: details GitHub Actions
If you want the latest and greatest to test before the official release, you can grab a copy from GitHub Actions.

**Using nightly.link:**
1. Download the [Latest Artifact](https://nightly.link/AngelAuraMC/Amethyst-Android/workflows/android/v3_openjdk/app-debug.zip) using this link.
2. Install as any usual .apk

**Using Github (requires an account):**

1. Start off by heading to the [Amethyst](https://https://github.com/AngelAuraMC/Amethyst-Android) repository and switching to the "Actions" tab.

![](./images/Actions/android/Android-Actions-1.png)

2. Next, select "Android CI" in the workflow selection menu.

![](./images/Actions/android/Android-Actions-2.png)

3. Choose a build with a green or blue checkmark next to the branch you want to download.
    - `v3_openjdk` will be the one for most people.

![](./images/Actions/android/Android-Actions-3.png)

4. Under "Artifacts", choose the build type you wish to download.
    - `app-debug` will be the one for most people.

![](./images/Actions/android/Android-Actions-4.png)

5. Install as any usual .apk
:::

::: details Source
**Instructions coming in a future revision to this website.**
:::

::: details Google Play
Google Play is currently unavailable. Sorry! Try one of the methods above!
:::

## iOS
Instructions for installing Amethyst on Apple devices.

::: details Sideloading (TrollStore)
We recommend TrollStore for all users if possible. This method allows for automatic JIT enabling, more memory allocation, and non-revoking installs.

Note: **Enable URL Schemes in TrollStore settings: TrollStore -> Settings -> Scroll Down -> Enable URLScheme > Rebuild Icons Cache**

### TrollStore compatibility depends on whether your iDevice is arm64 (A8-A11) or arm64e (A12+/M1+)

   #### For arm64, TrollStore is compatible with the following iOS versions:
  
    - 14.0 to 16.6.1
    - 17.0 
	- 16.7 to 16.7.10 (*)
 	- 17.0.1 to 17.7 (*)
  	- 18.0 to 18.1.1 (*)
    - 18.2 (*)

 (*) - requires arm64 iDevice jailbroken with [Palera1n](https://ios.cfw.guide/installing-palera1n)
  
   #### For arm64e, TrollStore is compatible with the following iOS versions:
  
    - 14.0 to 16.6.1
    - 17.0
    - 16.7 RC (20H18)

1. Follow these steps to install [TrollStore](https://ios.cfw.guide/installing-trollstore/).
 
2. Download the latest developer build from [here](https://nightly.link/AngelAuraMC/Amethyst-iOS/workflows/development/main/org.angelauramc.amethyst-ios.ipa.zip). Expect to encounter bugs!

3. Locate where the .ipa was downloaded, tap the Share icon, and choose TrollStore in the list of options available.

You can now enjoy Minecraft: Java Edition on your iDevice!
:::
<!-- TODO: fix the rest of IOS i am not touching sidestore shit :sob: -->
::: details Sideloading (Jailed)
**Requires an active Apple ID, that has signed into the [Apple Developer Program](https://developer.apple.com/account).**

PojavLauncher supports being sideloaded with AltStore and SideStore. Instructions to use SideStore are below--for other options, refer to their documentation.

1. Follow the official guide on installing AltStore itself:
    - Instructions for [Mac](https://docs.sidestore.io/docs/getting-started/mac) and [Windows](https://docs.sidestore.io/docs/getting-started/windows)
    
2. Install the latest release using this [Install with SideStore](sidestore://install?url=https://github.com/PojavLauncherTeam/PojavLauncher_iOS/releases/latest/download/net.kdt.pojavlauncher.ipa) button.
    - For a specific release, you can find its button on the [Releases](https://github.com/PojavLauncherTeam/PojavLauncher_iOS/releases) page

Installing PojavLauncher is not the end for Jailed iOS devices. In order to play Minecraft itself, you will need to [enable JIT](../faq/ios/JIT.md).
:::

::: details Sideloading (Jailbroken)
**Currently, AppSync Unified is not supported.** There is an [issue](https://github.com/akemin-dayo/AppSync/issues/108) regarding the data directory when installed with AppSync.

You can follow the `Sideloading (TrollStore)` or `Sideloading (Jailed)` steps to sideload on a jailbroken iDevice. Regardless of the method, you will benefit from automatic JIT enabling and more memory allocation.
:::

::: details GitHub Actions
**Requires a GitHub account in order to download.**

If you want the latest and greatest to test before the official release, you can grab a copy from GitHub Actions.

1. Start off by heading to the [PojavLauncher iOS](https://github.com/PojavLauncherTeam/PojavLauncher_iOS) repository and switching to the "Actions" tab.

![](./images/Actions/ios/iOS-Actions-1.png)

2. Next, select "Development Build" in the workflow selection menu.

![](./images/Actions/ios/iOS-Actions-2.png)

3. Choose a build with a green or blue checkmark next to the branch you want to download.
    - `main` will be the one for most people.

![](./images/Actions/ios/iOS-Actions-3.png)

4. Under "Artifacts", choose `net.kdt.pojavlauncher.ipa`

![](./images/Actions/ios/iOS-Actions-4.png)

Once you have an Actions build downloaded, you can now unzip the file and use this .ipa for TrollStore or sideloading.
:::

::: details Source
**Instructions coming in a future revision to this website.**
:::
