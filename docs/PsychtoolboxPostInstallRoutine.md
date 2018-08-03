###### >[Psychtoolbox](Psychtoolbox)

[PsychtoolboxPostInstallRoutine](PsychtoolboxPostInstallRoutine)(isUpdate [, flavor])  
  
Psychtoolbox post installation routine. You should not call this  
function directly! This routine is called by [DownloadPsychtoolbox](DownloadPsychtoolbox),  
or [UpdatePsychtoolbox](UpdatePsychtoolbox) after a successfull download/update of  
Psychtoolbox. The routine performs tasks that are common to  
downloads and updates, so they can share their code/implementation.  
  
As [PsychtoolboxPostInstallRoutine](PsychtoolboxPostInstallRoutine) itself is downloaded or updated,  
it can contain code specific to each Psychtoolbox revision/release  
to perform special setup procedures for new features, to announce  
important info to the user, whatever...  
  
### Currently the routine performs the following tasks:  
  
1. Clean up the Matlab/Octave path to Psychtoolbox: Remove unneeded .svn subfolders.  
2. Add the [PsychJava](PsychJava) subfolder to the static Matlab class-path if neccessary.  
   This enables the Java-based [GetChar](GetChar) support on Matlab.  
3. Add the [PsychStartup](PsychStartup).m routine to Matlab's startup.m file on Windows.  
4. Perform post-installation checks and basic troubleshooting.  




<div class="code_header" style="text-align:right;">
  <span style="float:left;">Path&nbsp;&nbsp;</span> <span class="counter">Retrieve <a href=
  "https://raw.github.com/Psychtoolbox-3/Psychtoolbox-3/beta/Psychtoolbox/PsychtoolboxPostInstallRoutine.m">current version from GitHub</a> | View <a href=
  "https://github.com/Psychtoolbox-3/Psychtoolbox-3/commits/beta/Psychtoolbox/PsychtoolboxPostInstallRoutine.m">changelog</a></span>
</div>
<div class="code">
  <code>Psychtoolbox/PsychtoolboxPostInstallRoutine.m</code>
</div>

