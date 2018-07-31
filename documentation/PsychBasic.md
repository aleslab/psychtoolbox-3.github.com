## [[Psychtoolbox]] &#8250; [[PsychBasic]]

  
Psychtoolbox:[[PsychBasic]]  
Psychtoolbox:[[PsychBeta]]:[[PsychBasic]]  
  
  
  [[Beeper]]               - Play a nice beep tone of selectable duration, frequency and volume.  
  [[CharAvail]]            - Is a keypress available for [[GetChar]]?         
  [[DisableKeysForKbCheck]] - Tell [[KbCheck]] and [[KbWait]] to ignore specific keys.  
  [[DoNothing]]            - Does nothing. Used to time Matlab's overhead.  
  [[DrawFormattedText]]    - Drawing of formatted text into windows.  
  [[DrawFormattedText2]]   - Drawing of formatted text into windows, with more formatting options.  
  [[FlushEvents]]          - Flush any unprocessed events.   
  [[FontInfo]]             - Return a struct array describing installed fonts.  
  [[Gestalt]]              - Query system configuration on OS 9 and OS X.   
  [[GetBusTicks]]          - Number of system bus ticks since startup.  
  [[GetBusTicksTick]]      - Duration of one tick of the [[GetBusTicks]] clock.  
  [[GetChar]]              - Wait for keyboard character and return it.  
  [[GetPID]]               - Get the process ID of the MATLAB process.  
  [[GetMouse]]             - Get mouse position.   
  [[GetMouseWheel]]        - Get mouse wheel position delta on a wheel mouse.  
  [[GetSecs]]              - Time since startup with high precision.   
  [[GetSecsTick]]          - Duration of one tick of the [[GetSecs]] clock.  
  [[GetTicks]]             - Number of 60.15 Hz ticks since startup.   
  [[GetTicksTick]]         - Duration of one tick of the [[GetTicks]] clock.  
  [[HideCursor]]           - Hide cursor.  
  [[IOPort]]               - A I/O driver for access to serial ports.  
  [[KbCheck]]              - Get instantaneous keyboard state.  
  [[KbEventAvail]]         - Return number of pending keyboard events in ringbuffer.  
  [[KbEventFlush]]         - Remove all pending keyboard events in ringbuffer.  
  [[KbEventGet]]           - Get oldest pending keyboard event in ringbuffer.  
  [[KbKeysAction]]         - Return an incremented or decremented value, depending on keys pressed.  
  [[KbName]]               - Convert keycode to key name and vice versa.  
  [[KbPressWait]]          - Wait for key press, make sure no keys pressed before.  
  [[KbQueueCreate]]        - Create keyboard queue.  
  [[KbQueueRelease]]       - Destroy keyboard queue.  
  [[KbQueueFlush]]         - Empty keyboard queue.  
  [[KbQueueStart]]         - Start recording of key presses into queue.  
  [[KbQueueStop]]          - Stop recording of key presses into queue.  
  [[KbQueueCheck]]         - Check keyboard queue for key presses/releases.  
  [[KbReleaseWait]]        - Wait until all keys on keyboard are released.  
  [[KbStrokeWait]]         - Wait for single, isolated key stroke.  
  [[KbTriggerWait]]        - Wait for trigger keys on keyboard.  
  [[KbWait]]               - Wait until at least one key is pressed and return its time.  
  [[ListenChar]]           - Start [[GetChar]] queue.  
  [[LoadPsychHID]]         - Helper function for loading [[PsychHID]] on MS-Windows.  
  [[MachAbsoluteTimeClockFrequency]] - Mach Kernel time measurement.    
  [[PredictVisualOnsetForTime]] - Predict stimulus onset for given [[Screen]]('[[Flip]]') 'when' timespec.  
  [[psychassert]]          - Drop in replacement for Matlabs assert().  
  [[psychlasterror]]       - Drop in replacement for Matlabs lasterror().  
  [[psychrethrow]]         - Drop in replacement for Matlabs rethrow().  
  [[PsychCV]]              - Miscellaneous C routines for computer vision and related stuff.  
  [[PsychDrawSprites2D]]   - Fast drawing of many 2D sprite textures.  
  [[PsychKinect]]          - Psychtoolbox driver for the Microsoft XBOX-360 Kinect.  
  [[PsychtoolboxDate]]     - Current version date, e.g. '1 August 1998'  
  [[PsychtoolboxVersion]]  - Current version number, e.g. 2.32  
  [[PsychWatchDog]]        - Watchdog mechanism and error handler for Psychtoolbox.  
  [[PsychTweak]]           - Tweak Psychtoolbox low-level operating parameters.  
  [[RemapMouse]]           - Map mouse position to stimulus position.  
  [[RestrictKeysForKbCheck]] - Restrict operation of [[KbCheck]] et al. to a subset of keys on the keyboard.  
  [[Screen]]               - Control the video display. \*\* Type "[[Screen]]" for a list. \*\*   
  [[SetMouse]]             - Set mouse position.  
  [[ShowCursor]]           - Show the cursor, and set cursor type.  
  [[Snd]]                  - Play sounds.  
  [[TouchEventAvail]]      - Return count of available (queued) touch events in a touch queue.  
  [[TouchEventFlush]]      - Delete all queued events from a touch queue.  
  [[TouchEventGet]]        - Retrieve oldest touch event from a touch queue.  
  [[TouchQueueCreate]]     - Create an event queue for reception of touch input.  
  [[TouchQueueRelease]]    - Release an event queue for touch input, once no longer needed.  
  [[TouchQueueStart]]      - Start touch recording on a touch queue.  
  [[TouchQueueStop]]       - Stop touch recording on a touch queue.  
  [[VideoRefreshFromMeasurement]] - Alternative calibration procedure to find exact video refresh interval.  
  [[WaitSecs]]             - Wait specified time.  
  [[WaitTicks]]            - Wait specified number of 60.15 Hz ticks.  




<div class="code_header" style="text-align:right;">
  <span style="float:left;">Path&nbsp;&nbsp;</span> <span class="counter">Retrieve <a href=
  "https://raw.github.com/Psychtoolbox-3/Psychtoolbox-3/beta/Psychtoolbox/PsychBasic/Contents.m">current version from GitHub</a> | View <a href=
  "https://github.com/Psychtoolbox-3/Psychtoolbox-3/commits/beta/Psychtoolbox/PsychBasic/Contents.m">changelog</a></span>
</div>
<div class="code">
  <code>Psychtoolbox/PsychBasic/Contents.m</code>
</div>

{{category}}