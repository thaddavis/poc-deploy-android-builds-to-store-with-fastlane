# STEPS

## Mac prerequisites

- https://docs.fastlane.tools/getting-started/android/release-deployment/#building-your-app
- sudo xcodebuild -license accept

## Install fastlane with homebrew

- brew install fastlane
- `fastlane init` in project directory

- https://docs.fastlane.tools/actions/supply/

## Create service account witht admin permissions on Google Play Console

1) On Google Play Console

2) Setup > API access

3) Click View In Google Cloud Platform

4) APIs & Services > Credentials

5) Create Credentials -> Service Account

6) Fill out `Create Service Account` form

	6a - Owner role

7) Create Key for Service Account aka from APIs & Services > Credentials
select newly created Service Account and `ADD KEY` in JSON format :)

8) Give Service Account Permissions to Access `Google Play Console` via Setup > API access
select service account > Account permision -> Admin

- I then had to download the creds for the service account as a .json file
- Changed to Java 11

## Build and Deploy to Google Play Store 

- fastlane android beta - DIDN'T WORK * TODO *
- fastlane android deploy - WORKED
