# Bird Scratches Analysis

Bird Scratches Analysis is a Windows application for processing and analyzing bird scratch data.

The program is distributed as a ready-to-use Windows build. You do not need to install Python or any additional Python libraries.

## Download

Download the latest version from the Releases section of this repository.

The Windows 64-bit release package is named:

Bird_Scratches_analysis_v1.0_Windows_x64

After downloading, extract the archive completely before running the program.

## How to Run

1. Download the release package from the Releases section.
2. Extract the archive to any convenient folder.
3. Open the extracted folder.
4. Run the file:

Bird_Scratches_analysis_v1.0_Windows_x64.exe

On some Windows systems, file extensions may be hidden. In that case, the program may appear simply as:

Bird_Scratches_analysis_v1.0_Windows_x64

## Important: Keep the Files Together

The executable file must remain in the same folder as the _internal folder.

The correct folder structure should look like this:

Bird_Scratches_analysis_v1.0_Windows_x64/
├── Bird_Scratches_analysis_v1.0_Windows_x64.exe
└── _internal/
    ├── python313.dll
    └── other required program files

Do not move the .exe file away from the _internal folder.

The program will not work if only the .exe file is copied or moved without the _internal folder.

## Error: Failed to Load Python DLL

If you see an error like this:

Failed to load Python DLL
_internal\python313.dll
LoadLibrary: The specified module could not be found.

it means that the program cannot find the required internal files.

This usually happens when:

* the archive was not extracted completely;
* the .exe file was moved away from the _internal folder;
* the program is being launched directly from inside the ZIP archive;
* the _internal folder was deleted or renamed.

To fix this problem:

1. Delete the incorrectly extracted folder.
2. Download the release package again.
3. Extract the archive completely.
4. Make sure that the .exe file and the _internal folder are located in the same folder.
5. Run the .exe file from the extracted folder.

## System Requirements

* Windows 10 or Windows 11
* 64-bit operating system
* Python is not required

## Windows SmartScreen Warning

When running the program for the first time, Windows may show a SmartScreen warning because the application was downloaded from the internet and may not be digitally signed.

If you trust the source of the program, click:

More info → Run anyway

## Important Note

Do not run the program directly from inside the ZIP archive.

Always extract the archive first, then run the .exe file from the extracted folder.
