## [[Psychtoolbox]] &#8250; [[PsychOpenGL]] &#8250; [[MOGL]] &#8250; [[wrap]]

glReadPixels  Interface to [OpenGL](OpenGL) function glReadPixels  
  
usage:    
For standard readback into a Matlab or Octave image matrix:  
retpixels = glReadPixels( x, y, width, height, format, type )  
  
For readback into the currently bound [OpenGL](OpenGL) Pixelbuffer object (PBO):  
glReadPixels( x, y, width, height, format, type, bufferoffset )  
where bufferoffset is the positive integer byte-offset into the PBO.  
  
C function:  void glReadPixels[(GLint]((GLint) x, [GLint](GLint) y, [GLsizei](GLsizei) width, [GLsizei](GLsizei) height, [GLenum](GLenum) format, [GLenum](GLenum) type, [GLvoid](GLvoid)\* retpixels)  




<div class="code_header" style="text-align:right;">
  <span style="float:left;">Path&nbsp;&nbsp;</span> <span class="counter">Retrieve <a href=
  "https://raw.github.com/Psychtoolbox-3/Psychtoolbox-3/beta/Psychtoolbox/PsychOpenGL/MOGL/wrap/glReadPixels.m">current version from GitHub</a> | View <a href=
  "https://github.com/Psychtoolbox-3/Psychtoolbox-3/commits/beta/Psychtoolbox/PsychOpenGL/MOGL/wrap/glReadPixels.m">changelog</a></span>
</div>
<div class="code">
  <code>Psychtoolbox/PsychOpenGL/MOGL/wrap/glReadPixels.m</code>
</div>

