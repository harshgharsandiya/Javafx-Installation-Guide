JavaFX Installation Guide 🚀
Easy Steps for Installing JavaFX on Windows via Command Prompt

1. Check Java Version:
        Open Command Prompt and type java --version.
        If the version is older than 8, download and set up a newer Java version.
        Check Java Icon Ensure Java version is > 8

2. Download JavaFX SDK:
        Get the JavaFX SDK for Windows from below:
        https://download2.gluonhq.com/openjfx/21.0.1/openjfx-21.0.1_windows-x64_bin-sdk.zip

4. Extract and Copy Path:
        Extract the downloaded file and copy the path of the 'lib' folder.
        Extract and copy 'lib' path

5. Update Path in Command:
        Replace the 'lib' path in the command line:

        --module-path "path of lib file" --add-modules javafx.base,javafx.controls,javafx.fxml,javafx.graphics,javafx.media,javafx.swing,javafx.web

5.Set System Environment Variable:

    Go to system environment variables, click 'New', and add the following details:
        Variable Name: javafxlib
        Variable Value: the copied path above

6.Verification:

    Open a new Command Prompt and type 
    echo "%javafxlib%"

7.Run Basic Java Code:

    Use the sample Java code provided in the repository.
    
8.Compile and Run:

    Open Command Prompt at the code location.
    
    For Compilation: 
    javac %javafxlib% Filename.java
    For Execution: 
    java %javafxlib% Filename
    Compile Run Icon Compile and run Java code

That's It! 🎉
