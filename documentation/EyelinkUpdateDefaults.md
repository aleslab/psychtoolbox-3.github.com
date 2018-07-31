## [[Psychtoolbox]] &#8250; [[PsychHardware]] &#8250; [[EyelinkToolbox]] &#8250; [[EyelinkBasic]]

USAGE = [EyelinkUpdateDefaults](EyelinkUpdateDefaults)(el)   
  
This function passes changes to the calibration defaults structure  
to the callback function. To be called after [EyelinkInitDefaults](EyelinkInitDefaults) if any  
changes are made to the output structure of that function.  
  
el=[EyelinkInitDefaults](EyelinkInitDefaults)(window);  
el.backgroundColour = [BlackIndex](BlackIndex)(window);  
[EyelinkUpdateDefaults](EyelinkUpdateDefaults)(el);  
  
27-1-2011 NJ created   
19-12-2012 IA Fix hardcoded callback   




<div class="code_header" style="text-align:right;">
  <span style="float:left;">Path&nbsp;&nbsp;</span> <span class="counter">Retrieve <a href=
  "https://raw.github.com/Psychtoolbox-3/Psychtoolbox-3/beta/Psychtoolbox/PsychHardware/EyelinkToolbox/EyelinkBasic/EyelinkUpdateDefaults.m">current version from GitHub</a> | View <a href=
  "https://github.com/Psychtoolbox-3/Psychtoolbox-3/commits/beta/Psychtoolbox/PsychHardware/EyelinkToolbox/EyelinkBasic/EyelinkUpdateDefaults.m">changelog</a></span>
</div>
<div class="code">
  <code>Psychtoolbox/PsychHardware/EyelinkToolbox/EyelinkBasic/EyelinkUpdateDefaults.m</code>
</div>

