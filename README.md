# CoinCollector - CSharp tests

This project contains C# AltTester® tests for a project using the New Input System.
The tested actions are: tap object, key down/ key up, press key, click object, scroll, begin/end touch and tap simulated with swipe.

## Before running the tests
❗ Starting with version 2.0.0, the AltTester® Desktop must be running on your PC while the tests are running.

- Download and install the AltTester® Desktop from [here](https://alttester.com/downloads/), then open it.
- To run the tests, you must include the AltTester® Unity SDK in the project. To do that, you can choose between the following ways:
1. Add the AltTester® Unity SDK submodule to the project
    - use ``git submodule update --init`` command to pull the git submodule;
    - make sure that the submodule added is on the master branch (you can use the following command ``git checkout master`` in the <i>Assets/AltTester-Unity-SDK</i> folder);
    - also, if you already have the project, you should make a ``git pull`` on the master branch, to ensure that you are using the latest version of AltTester®.

    <br> 
2. Download AltTester® Unity SDK and import it into Unity 
    - download the AltTester® Unity SDK from the AltTester website (https://alttester.com/downloads/ - you will be able to download a package that will contain a unity package) or using this link https://alttester.com/app/uploads/AltTester/sdks/AltTesterUnitySDK.unitypackage;
    - import the package into the project (drag-n-drop the package in the Assets folder);
    - a pop-up will appear, select All and click on Import.

## Run the tests

You can open the project in the Unity Editor and run the tests from the AltTester® Editor window.

The tests can be found in the Editor -> Tests folder in the AltTester_NIS_Tests class.
