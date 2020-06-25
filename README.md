# SettingsSingleton
 Example assets for modding with Ark: Survival Evolved DevKit. This is an example of using a replicated singleton to make your mod's INI settings easily available in any graph. See the images in 'Examples' for more info on using this.

## Contents
- _SettingsCCA/
  - _ISettings
    - _interface for accessing the settings cca without needing a hard ref on its type_
  - _SettingsCCA_Funcs
    - _function library for getting settings values from any graph_
  - _SettingsCCA_Actor
    - _the singleton actor that loads the GUS INI settings and replicates to clients_
- Examples/
  - _contains screenshot images that will help explain the content further as well as how to use it_
- TestAssets/
  - SettingsCCA_TestActor
    - _test cca only used to add the test buff to player in PIE_
  - SettingsCCA_TestBuff
    - _test player buff added during PIE (short delay), which then demonstrates setting value retrieval and logging the results_

