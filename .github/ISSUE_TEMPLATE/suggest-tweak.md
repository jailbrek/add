---
name: "Request a Tweak"
about: "Submit a new tweak or modification for the project."
title: "[Tweak] - <Short description>"
labels: enhancement
assignees: ""

---

Tweak Metadata  
Please fill out the fields below for your tweak submission:

```yaml
Package: "<Package Name>"  # The name of the tweak (e.g., "ai.akemi.appsyncunified")
Version: "<Version>"  # The version of the tweak (e.g., "112.0")
Architecture: "<Architecture>"  # Architecture type (e.g., "iphoneos-arm64")
Maintainer: "<Maintainer Name> <Maintainer Email>"  # Who maintains the tweak (e.g., "Karen/あけみ <karen@akemi.ai>")
Depends: 
  - "firmware (>= 5.0)"  # List dependencies (e.g., firmware, mobilesubstrate)
  - "mobilesubstrate (>= 0.9.5100)"
Conflicts:
  - "us.hackulo.appsync50"
  - "com.teiron.ppsync"
  # List any conflicting packages here
Replaces:
  - "us.hackulo.appsync50"
Provides:
  - "<package-name>"  # Provide the core package (e.g., "appsync")
Filename: "./debs/<package-filename>.deb"  # Path to the .deb file
Size: "<Size>"  # File size in bytes (e.g., "34280")
MD5sum: "<MD5>"  # MD5 hash of the file
SHA1: "<SHA1>"  # SHA1 hash of the file
SHA256: "<SHA256>"  # SHA256 hash of the file
Section: "Tweaks"  # Category (e.g., "Tweaks")
Homepage: "<Homepage URL>"  # Link to homepage (e.g., "https://cydia.akemi.ai/")
Description: "<Short description>"  # A brief description of what the tweak does (e.g., "Enables the ability to install unsigned/fakesigned iOS applications.")
Author: "<Author(s)>"  # Author(s) of the tweak (e.g., "Karen/あけみ, Linus Yang <karen@akemi.ai>")
Depiction: "<Depiction URL>"  # URL for the depiction page (e.g., "https://cydia.akemi.ai/?page/ai.akemi.appsyncunified")
