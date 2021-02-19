# OculusDK2LeapMotion
If you have an old Oculus DK2 and in 2021 or beyond do you want to setup a working stack environment here I put the stack that worked for me in a Windows 10 machine hope this save you time.

# Requirements:

- UnitySetup64-5.3.4f1
- oculus_runtime_sdk_0.8.0.0_win
- LeapDeveloperKit_3.2.1_win
- LeapMotion_CoreAsset_Orion_4.1.4_0253ddb

Download the Installers From the releases section here: https://github.com/gislersoft/OculusDK2LeapMotion/releases/tag/v2016.0.0-dk2-stack

# Installation Steps

1. Install LeapDeveloperKit (Leap Motion Driver)
2. Restart Windows 10
3. Install Oculus Runtime 0.8 (Oculus Driver)
4. Restart Windows 10
5. Install Unity
6. Restart Windows 10
7. Connect your Oculus DK2
8. Check the demo scene with Oculus Config Tool
9. Close the Config Tool
10. If was working then Open Unity
11. Create a new 3D Project
12. Go To ***Edit > Project Settings > Player > Other Settings***
13. Check the "Virtual Reality Supported" option
14. Start the scene with play (Oculus should work now)
15. Stop the scene
16. If everything was working then import the Leap Motion Core Assets Orion to your unity project
17. Wait until imports ends.
18. Open the "Leap Motion Hands VR" Scene in ***Assets/LeapMotion/Scenes***
19. Add some blank cubes and plain to your scene for perpective
20. Put you oculus and leap motion (attached as VR to the HMD)
21. Press Play.
22. Enjoy!

# Disclaimer

All this files are public in 2021, Download at your discretion from here. I'm just gathering in a public repo to help other researches with old Oculus DK2 as me to easily start a project.

