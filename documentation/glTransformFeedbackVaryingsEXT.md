## [[Psychtoolbox]] &#8250; [[PsychOpenGL]] &#8250; [[MOGL]] &#8250; [[wrap]]

glTransformFeedbackVaryingsEXT  Interface to [OpenGL](OpenGL) function glTransformFeedbackVaryingsEXT  
  
usage:  glTransformFeedbackVaryingsEXT( program, count, varyings, bufferMode )  
  
program = GLSL shader program handle.  
  
count = Number of varyings.  
  
varyings = cell array of 'count' char() name strings of the 'count'  
varyings to return during transform feedback.  
  
bufferMode = The bufferMode to use for transform feedback.  
  
  
C function:  void glTransformFeedbackVaryingsEXT[(GLuint]((GLuint) program, [GLsizei](GLsizei) count, const [GLchar](GLchar)\*\* varyings, [GLenum](GLenum) bufferMode)  




<div class="code_header" style="text-align:right;">
  <span style="float:left;">Path&nbsp;&nbsp;</span> <span class="counter">Retrieve <a href=
  "https://raw.github.com/Psychtoolbox-3/Psychtoolbox-3/beta/Psychtoolbox/PsychOpenGL/MOGL/wrap/glTransformFeedbackVaryingsEXT.m">current version from GitHub</a> | View <a href=
  "https://github.com/Psychtoolbox-3/Psychtoolbox-3/commits/beta/Psychtoolbox/PsychOpenGL/MOGL/wrap/glTransformFeedbackVaryingsEXT.m">changelog</a></span>
</div>
<div class="code">
  <code>Psychtoolbox/PsychOpenGL/MOGL/wrap/glTransformFeedbackVaryingsEXT.m</code>
</div>

