- https://docs.fastlane.tools/getting-started/android/release-deployment/#building-your-app
- sudo xcodebuild -license accept
- brew install fastlane
- `fastlane init` in project directory

- https://docs.fastlane.tools/actions/supply/

- I had to create a service account in the developer console with permissions to talk to the Google Play console
- I then had to download the creds for the service account as a .json file

- Changed to Java 11

- fastlane android beta - DIDN'T WORK
- fastlane android deploy - WORKED