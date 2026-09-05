# Android Static Analysis

## Objective

The objective of this challenge is to uncover a hidden flag within an APK using static analysis techniques.

## Description

This challenge focuses on Android application static analysis and reverse engineering. The APK can be analyzed without running it on a device or emulator.

The analysis involves:

- Extracting the APK contents
- Inspecting the `AndroidManifest.xml`
- Decompiling the application using JADX
- Searching for strings and resources
- Analyzing Java and Smali code
- Identifying obfuscated or encoded data
- Reconstructing the correct input expected by the application

## Tools

- JADX
- unzip
- strings
- Android static analysis tools

## Flag

The recovered flag is stored in `0-flag.txt`.
