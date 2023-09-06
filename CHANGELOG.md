#### Version 1.2.0
* [UPDATE] Removed `OAuth1` from runtime requests. For further details on this see our [migration guide](https://docs.medallia.com/en/?resourceId=mxo-android-sdk-migration-v1.2.0).
* [UPDATE] Removed `renderscript` support. For further details on this see our [migration guide](https://docs.medallia.com/en/?resourceId=mxo-android-sdk-migration-v1.2.0).
* [UPDATE] Compatible with [Android Gradle Plugin version 7.3.1](https://developer.android.com/build/releases/past-releases/agp-7-3-0-release-notes).
* [UPDATE] Compatible with [Gradle version 7.5.0](https://docs.gradle.org/7.5/release-notes.html).
* [BUGFIX] Fixed an issue where multiple customer Attribute data type selections were allowed.
* [BUGFIX] Fixed an issue where some Capture Points were not sent on tap.
* [BUGFIX] Fixed an issue where a location was not shared on API 29.
* [BUGFIX] Fixed an issue with logging for an invalid or missing SDK configuration.
* [BUGFIX] Fixed an issue where an error message was not shown on an empty view in Admin mode.
* [BUGFIX] Fixed an issue where an error message was not shown when logging into a non-existing MXO Space.
* [BUGFIX] Fixed an issue where a user with no permissions was not getting an error message in Admin mode.

#### Version 1.1.2
* [BUGFIX] Fixed an issue with `contentUrl` not being returned in `MXOAsset` for external assets.
* [BUGFIX] Fixed an issue with `MXOAssetResponse` not returning `label`, `target`, and `targetUrl`.
* [BUGFIX] Fixed an issue with `MXOCaptureAttributePoint` not returning `capturePhase`, `captureType`, `captureDelay`, `elementType`, `elementName`, and `elementAttributeName`.

#### Version 1.1.1
* [BUGFIX] Fixed an issue with `directives` not being returned in `MXOOptimizationPoint`.

#### Version 1.1.0
* [UPDATE] Updated to support up to Android API 33.
* [UPDATE] Added support to include Telemetry data in network calls.
* [BUGFIX] Fixed an issue where the SDK logging was not creating new log files correctly.

#### Version 1.0.0
* [BREAKING] Requires the matching Medallia Orchestration Plugin version 1.0.0.
* [BREAKING] Requires [Kotlin version 1.7.0](https://github.com/JetBrains/kotlin/releases/tag/v1.7.0).
* [BREAKING] Requires [Java version 11](https://developer.android.com/studio/write/java11-minimal-support-table).
* [BREAKING] Requires [Android Gradle Plugin version 7.2.2](https://developer.android.com/build/releases/past-releases/agp-7-2-0-release-notes).
* [BREAKING] Requires [Gradle version 7.3.3](https://docs.gradle.org/7.3.3/release-notes.html).
* [BREAKING] Updated the SDK's public APIs. For further details on this, see our [online documentation](https://docs.medallia.com/en/?resourceId=mxo-android-sdk-features). If migrating from Thunderhead SDK, please visit our [migration guide](https://docs.medallia.com/en/?resourceId=mxo-anddroid-sdk-migration-api).
* [BREAKING] Updated prebuilt Interactions. If migrating from Thunderhead SDK, please visit our [migration guide](https://docs.medallia.com/en/?resourceId=mxo-android-sdk-migration-prebuilt).
* [UPDATE] Updated Designtime error messaging.
* [UPDATE] Updated `WebChromeClient` for APIs below 26. For further details on this, see our [documentation](https://docs.medallia.com/en/?resourceId=mxo-android-sdk-features-webview).
* [BUGFIX] Fixed a `Ljava/time/Duration` runtime error on APIs below 26. For further details on this, see our [Additional integration considerations documentation](https://docs.medallia.com/en/medallia-experience-orchestration/orchestration-for-android/additional-integration-considerations#adding-support-for-an-android-api-version-below-26-0).
* [BUGFIX] Fixed a crash on custom Web Views.
* [BUGFIX] Fixed a crash that was occurring when selecting an Activity Type in an empty Space.
* [BUGFIX] Fixed an issue when selected Propositions, Activities, and Attributes were discarded by double tap.
* [BUGFIX] Fixed an issue when automatic Propositions were missing at the Propositions screen.
* [BUGFIX] Fixed an issue when nested Propositions were missing at the Propositions screen.
* [BUGFIX] Fixed an issue when completion Activity was not being honored.
* [BUGFIX] Fixed an issue when Poker Chip remained displayed after leaving the app.
* [BUGFIX] Fixed an issue when multiple selections for App Preferences were allowed.
* [BUGFIX] Fixed an issue when the Create New Attribute button was not tappable when there was a text input in the Attributes search field.
* [BUGFIX] Fixed an issue when `SeekBar` Activity was captured while should not be.
* [BUGFIX] Fixed an issue when `MenuItem` Activity was not captured ontap.
* [BUGFIX] Fixed a placeholder text for Propositions and Activity Types search fields.
* [BUGFIX] Fixed zero state messages for Propositions, Activities, and Attributes.
