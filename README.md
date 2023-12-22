# ReVanced CLI Automation

### [**Just download (on PC) and double click.**](https://github.com/sipun9348/auto-cli/releases/download/v3.6/auto-cli-v3.6.bat) It is *that* simple.

(You might have to click on "More info" and then "Run anyways")

---

<details>
  <summary>An overview on what it does (in case you're curious)</summary>

Setup:

1. create the revanced-cli folder at the default install location (appdata/local)
2. download input.json - this is used as a config file for tools and apps
3. check and validate curl - download it if needed
4. check and validate portable jdk - download it if needed
5. check and validate revanced tools (cli, patched, integrations) - download them if needed
6. generate a list of available apps to patch based on the input.json

Patching:

1. check the user input, and download the appropiate apk or run the custom routine
2. validate the APK and initiate patching based on the selected

Clean-up:

1. Once patching is completed, rename the patched app to PATCHED_*.apk
2. delete various files and folders that have been dropped by CLI
3. Save a backup of the apk and your keystore to the install path


</details>

## Screenshot
<details>
  <summary>A visual demonstration</summary>


![auto-cli-screenshot-new](https://github.com/taku-nm/auto-cli/assets/23640508/81e545af-86b1-400f-a58a-4ae385164797)

</details>
