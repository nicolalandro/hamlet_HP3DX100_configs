# hamlet_HP3DX100_configs
Cura and other slicers configs for hamlet 3D printer HP3DX100

## Old cura settings
Using te [old CURA version 13.06.4](https://github.com/Ultimaker/Cura/releases/tag/13.06.4) compiled by myself i create the standard configuration using [official instructions](http://www.hamletcom.com/media/67174/cura_setup.zip):
* Generated file path: 'old_CURA-13.06.4_printer_config/hamlet.ini'
* it is iportable as printer profile

## Cura 4.6.2 settings
Start from the old version I create the new version configurations:
* Starting fro Ultimaker printer config I modify as in figures
![printer settings](CURA-4.6.2_printer_and_materials_config/printer_settings_1.png)
![nozel settings](CURA-4.6.2_printer_and_materials_config/printer_settings_2.png)
* start gcode path: 'CURA-4.6.2_printer_and_materials_config/start_gcode.txt'
* end gcode path: 'CURA-4.6.2_printer_and_materials_config/end_gcode.txt'
* materials settings path
  * ABS: 'CURA-4.6.2_printer_and_materials_config/ABS.xml.fdm_material'
  * PLA: 'CURA-4.6.2_printer_and_materials_config/PLA.xml.fdm_material'
  * TPU: 'CURA-4.6.2_printer_and_materials_config/TPU.xml.fdm_material'
* printing profiles path:
  * ABS: 'CURA-4.6.2_printer_and_materials_config/ABS.curaprofile'
  * PLA: 'CURA-4.6.2_printer_and_materials_config/PLA.curaprofile'
  * TPU: 'CURA-4.6.2_printer_and_materials_config/TPU.curaprofile'
* Also at "Extensions>Post Processing>Modify G-Code" add ```M566.*``` and check "Use Regular Expressions" 
![modify gcode post processing](CURA-4.6.2_printer_and_materials_config/printer_post_scripting.png)

## Simplify3D
In [this topic](https://www.stampa3d-forum.it/forum/topic/567-adattare-la-mia-hamlet/) I found a Simplify3D settings for Hamlet HP3DX100, and I store it at path 'Simplify3D/3dx100_v2.fff' because someties the post files disappear.

