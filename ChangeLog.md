# Change Log

[0.3.6] - 2025-08-04
Fixed
Forked the library to add compatibility for Android Gradle Plugin (AGP) 8.0 and higher.
Updated the Android build.gradle to use the namespace property.
Implemented conditional manifest files (AndroidManifest.xml and AndroidManifestNew.xml) to maintain backward compatibility with older versions of AGP.

[0.3.5] - 2024-10-11
Fixed
Updated SDK to fix noise issues when streaming to YouTube.

[0.3.4] - 2024-03-19
Changed
NodePublisher will now only auto-preview the camera when videoParam is set.

[0.3.3] - 2024-03-08
Added
Added a volume property to NodePublisher, which can be used for muting during a stream.

[0.3.2] - 2024-03-06
Fixed
Updated Android SDK to v3.2.7 to fix audio channel compatibility issues during streaming.

[0.3.1] - 2024-03-06
Fixed
Updated Android SDK to v3.2.6 to fix an issue that caused silent streams.

[0.3.0] - 2024-03-01
Added
Initial release compatible with SDK v3.
