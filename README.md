# ReaPository
Reaper scripts written with help from Chat GPT

Current scripts:
 - AI_toggle_active_envelopes
   - Toggles the active state of all envelopes on a selected track.

 - AI_Melodyne_workflow
   - A script to speed up my Melodyne render workflow by combining several actions into one.
      - The way I use this with a custom action is:
         - Script: AI_toggle_active_envelopes
         - Script: AI_Melodyne_workflow
         - Item properties: Lock to active take (mouse click will not change active take)
         - Script: AI_toggle_active_envelopes

 - AI_bypass_all_fx
   - On the current selected track, bypass all plugins except for the first plugin.

 - AI_remove_first_fx
   - On the current selected track, remove the first plugin.

