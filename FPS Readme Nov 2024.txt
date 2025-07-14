Download and extract all
•	FPSMv1-2of2.zip
•	FPSMv1-1of2.zip
•	Complex.Tier.3.example.with.full.functionality.zip

Combine FPSMv1-2of2 and FPSMv1-1of2 file in a single folder, doesn’t matter which.

In the folder Complex.Tier.3.example.with.full.functionality (unzipped), you’ll see the following files:
•	RunFPSM.bat – this is used to run the software, you double click on it, but we will edit it first below
•	FPSM_main_Aug202024.txt – this defines the model structure and parameters (see user guide)
•	log_FluxBio.csv – model input (see user guide)
•	log_FluxDOM.csv – model input (see user guide)

Before you can run the software you need to tell the RunFPSM.bat where things are.

Right click on RunFPSM.bat and choose Edit or Open With (depending on Windows version). Edit will open it in Notepad. The file looks something like this

"C:\Users\CDYMOND\Downloads\FPSMv1-2of2\Landis.Extension.FPS-v1.exe" FPSM_main_Aug202024.txt
Pause

The first path is to the files you extracted and combined from FPSMv1-2of2 and FPSMv1-1of2. Revise with the proper path. Save.

The second is to your model structure and parameters, shouldn’t need to revise at this time. 

Double-click on RunFPSM.bat. It should pop-up a command window. If it runs successfully, it will say pause and Press any key to continue.

In the folder there will be 
FPS_raw_out.csv
FPS_test_out.csv

