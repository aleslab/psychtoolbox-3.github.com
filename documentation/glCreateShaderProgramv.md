## [[Psychtoolbox]] &#8250; [[PsychOpenGL]] &#8250; [[MOGL]] &#8250; [[wrap]]

glCreateShaderProgramv  Interface to [OpenGL](OpenGL) function glCreateShaderProgramv  
  
usage:  r = glCreateShaderProgramv( type, count, strings )  
  
You have to pass a single character string 'strings' that  
contains the ASCII text of the shaders source code. Each line in the  
string needs to be terminated by a '\n' aka ASCII code 10 aka newline.  
This string will be split up into the array of strings as expected by  
the C function glCreateShaderProgramv.  
  
The 'count' parameter is ignored.  
'type' is the type of shader.  
  
A simple way to read a shader from a standard text file, e.g., for a  
vertex shader is as follows:  
fid=fopen('MyShader.txt', 'r');  
shadersource=fread(fid);  
fclose(fid);  
shader = glCreateShaderProgramv(GL.VERTEX\_SHADER, 1, shadersource);  
  
C function:  [GLuint](GLuint) glCreateShaderProgramv[(GLenum]((GLenum) type, [GLsizei](GLsizei) count, const [GLchar](GLchar)\* const)  




<div class="code_header" style="text-align:right;">
  <span style="float:left;">Path&nbsp;&nbsp;</span> <span class="counter">Retrieve <a href=
  "https://raw.github.com/Psychtoolbox-3/Psychtoolbox-3/beta/Psychtoolbox/PsychOpenGL/MOGL/wrap/glCreateShaderProgramv.m">current version from GitHub</a> | View <a href=
  "https://github.com/Psychtoolbox-3/Psychtoolbox-3/commits/beta/Psychtoolbox/PsychOpenGL/MOGL/wrap/glCreateShaderProgramv.m">changelog</a></span>
</div>
<div class="code">
  <code>Psychtoolbox/PsychOpenGL/MOGL/wrap/glCreateShaderProgramv.m</code>
</div>

