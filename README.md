# LEGO Education WeDo 2.0 – Android Recovery Guide

LEGO Education WeDo 2.0 is discontinued and may no longer be available for installation from the Google Play Store.

Many schools, teachers and families still have perfectly working WeDo 2.0 SmartHubs and kits, but after replacing or factory-resetting an Android tablet they may no longer be able to reinstall the original WeDo 2.0 application.

This guide documents a method that was successfully tested on a factory-reset Android tablet.

---

# What You Need

- An Android tablet
- A Windows laptop or computer
- A backed-up WeDo 2.0 `.apks` file
- An APK extractor
- An installer capable of installing `.apks` packages, such as APK Installer by Braveheart
- A USB cable

> IMPORTANT: Keep the WeDo 2.0 `.apks` backup exactly as it was created.  
> Do NOT rename it, convert it, unzip it or modify its contents.

---

# Installation Instructions

## Step 1 – Install an APK Extractor

On the Android tablet, install an APK extractor.

You can first install any small free Android application from Google Play to use as a test.

Open the APK extractor and extract that small application.

This causes the extractor to create its storage folder on the tablet.

On the tablet used for this test, the folder created was:

`ApkExtract`

You do NOT need the extracted test application afterward. Its purpose is simply to make sure the extractor has created and initialized its folder.

---

## Step 2 – Install an APKS-Compatible Installer

Install:

**APK Installer by Braveheart**

or another Android installer that specifically supports `.apks` split-package files.

A normal APK installer may not work because WeDo 2.0 can be stored as an `.apks` package containing multiple application components.

---

## Step 3 – Connect the Tablet to the Computer

Connect the Android tablet to the Windows computer using USB.

On the tablet select:

**File Transfer**

Then open the tablet from Windows File Explorer.

Go to:

`Internal shared storage`

Find:

`ApkExtract`

---

## Step 4 – Copy the WeDo 2.0 Backup

# ⬇️ Download WeDo 2.0

**[👉 CLICK HERE TO OPEN THE DOWNLOAD PAGE](https://github.com/eyadnasrr/wedo2.0-android-recovery/releases/latest)**

On the Release page, scroll to **Assets** and download:

`WeDo.2.0v1.10.259.apks`

Copy your original WeDo 2.0 `.apks` backup file from the computer into:

`Internal shared storage/ApkExtract/`

### VERY IMPORTANT

Do not:

- Rename the `.apks` file
- Change `.apks` to `.apk`
- Extract or unzip the file
- Modify anything inside the package

Copy the original file exactly as it was backed up.

---

## Step 5 – Install WeDo 2.0

Disconnect the tablet from the computer.

Open **APK Installer by Braveheart**.

Allow storage/file access if Android asks for permission.

Let the installer scan the tablet.

It should detect the WeDo 2.0 `.apks` package inside the `ApkExtract` folder.

Select the WeDo package and press:

**Install**

Android may ask you to allow installation of unknown applications from APK Installer.

Allow it.

Continue the installation.

Once installation finishes, LEGO Education WeDo 2.0 should appear in the tablet's application list.

---

# Bluetooth / SmartHub Fix

After installation, WeDo 2.0 may open correctly but fail to find the WeDo 2.0 SmartHub.

This happened during our test.

The application itself was working. The problem was Android permissions.

Go to:

**Settings → Apps → WeDo 2.0 → Permissions**

Enable the permissions available on your Android version, especially:

- Location
- Nearby devices

Then:

1. Turn Bluetooth ON.
2. Turn Location/GPS ON.
3. Close WeDo 2.0 completely.
4. Open WeDo 2.0 again.
5. Open a project.
6. Select the SmartHub connection option.
7. Press the green button on the WeDo 2.0 SmartHub.

The SmartHub should now be detected.

This procedure was successfully tested and Bluetooth communication with the WeDo 2.0 SmartHub was restored.



# Tested Result


✅ WeDo 2.0 successfully reinstalled

✅ Application launched normally

✅ Bluetooth permissions restored

✅ WeDo 2.0 SmartHub successfully connected

---

# Important Notice

This repository documents a recovery procedure for owners of existing LEGO Education WeDo 2.0 equipment and software backups.

LEGO, LEGO Education and WeDo are trademarks of the LEGO Group.

This project is independent and is not affiliated with, sponsored by, or endorsed by the LEGO Group.
