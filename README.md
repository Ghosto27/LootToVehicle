# LootToVehicle
Loot to Vehicle for ACE and Antistasi


Add files from mission_folder to your mission folder

If description.ext already exist "class CfgFunctions" add content into it.


- distance to vehicle increased from 15 to 20 m

- if you woun't box removing after transfer, comment lines 61-64 in file "functions/fn_transferToVehicle.sqf"

    //delete box
    /*
    if (typeOf _target == "Box_T_East_Wps_F") then {
        deleteVehicle _target;
    }; 
    */
