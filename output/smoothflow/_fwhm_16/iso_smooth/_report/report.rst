Node: iso_smooth (fsl)
======================


 Hierarchy : smoothflow.iso_smooth
 Exec ID : iso_smooth.aI.a2


Original Inputs
---------------


* args : <undefined>
* environ : {'FSLOUTPUTTYPE': 'NIFTI_GZ'}
* fwhm : 16.0
* in_file : /opt/home/aracena/thesis_practica/tips_nipype/iterables/output/smoothflow/skullstrip/sub-01_T1w_brain.nii.gz
* internal_datatype : <undefined>
* nan2zeros : <undefined>
* out_file : <undefined>
* output_datatype : <undefined>
* output_type : NIFTI_GZ
* sigma : <undefined>


Execution Inputs
----------------


* args : <undefined>
* environ : {'FSLOUTPUTTYPE': 'NIFTI_GZ'}
* fwhm : 16.0
* in_file : /opt/home/aracena/thesis_practica/tips_nipype/iterables/output/smoothflow/skullstrip/sub-01_T1w_brain.nii.gz
* internal_datatype : <undefined>
* nan2zeros : <undefined>
* out_file : <undefined>
* output_datatype : <undefined>
* output_type : NIFTI_GZ
* sigma : <undefined>


Execution Outputs
-----------------


* out_file : /opt/home/aracena/thesis_practica/tips_nipype/iterables/output/smoothflow/_fwhm_16/iso_smooth/sub-01_T1w_brain_smooth.nii.gz


Runtime info
------------


* cmdline : fslmaths /opt/home/aracena/thesis_practica/tips_nipype/iterables/output/smoothflow/skullstrip/sub-01_T1w_brain.nii.gz -s 6.79457 /opt/home/aracena/thesis_practica/tips_nipype/iterables/output/smoothflow/_fwhm_16/iso_smooth/sub-01_T1w_brain_smooth.nii.gz
* duration : 12.638569
* hostname : daniela-MS-7760
* prev_wd : /opt/home/aracena/thesis_practica/tips_nipype/iterables
* working_dir : /opt/home/aracena/thesis_practica/tips_nipype/iterables/output/smoothflow/_fwhm_16/iso_smooth


Terminal output
~~~~~~~~~~~~~~~


 


Terminal - standard output
~~~~~~~~~~~~~~~~~~~~~~~~~~


 


Terminal - standard error
~~~~~~~~~~~~~~~~~~~~~~~~~


 


Environment
~~~~~~~~~~~


* ANTSPATH : /home/aracena/antsbin/bin/
* CHROME_CONFIG_HOME : /home/aracena/.config/chrome-remote-desktop/chrome-config
* CHROME_REMOTE_DESKTOP_SESSION : 1
* CLICOLOR : 1
* CLUTTER_IM_MODULE : ibus
* COLORTERM : truecolor
* CONDA_DEFAULT_ENV : base
* CONDA_EXE : /home/aracena/anaconda3/bin/conda
* CONDA_PREFIX : /home/aracena/anaconda3
* CONDA_PROMPT_MODIFIER : (base) 
* CONDA_PYTHON_EXE : /home/aracena/anaconda3/bin/python
* CONDA_SHLVL : 1
* DBUS_SESSION_BUS_ADDRESS : unix:path=/run/user/1002/bus
* DESKTOP_SESSION : ubuntu
* DISPLAY : :20
* FIX_VERTEX_AREA : 
* FMRI_ANALYSIS_DIR : /home/aracena/freesurfer/fsfast
* FREESURFER : /home/aracena/freesurfer
* FREESURFER_HOME : /home/aracena/freesurfer
* FSFAST_HOME : /home/aracena/freesurfer/fsfast
* FSF_OUTPUT_FORMAT : nii.gz
* FSLCONVERT : /usr/bin/convert
* FSLDIR : /home/aracena/fsl
* FSLDISPLAY : /usr/bin/display
* FSLGECUDAQ : cuda.q
* FSLLOCKDIR : 
* FSLMACHINELIST : 
* FSLMULTIFILEQUIT : TRUE
* FSLOUTPUTTYPE : NIFTI_GZ
* FSLREMOTECALL : 
* FSLTCLSH : /home/aracena/fsl/bin/fsltclsh
* FSLWISH : /home/aracena/fsl/bin/fslwish
* FSL_BIN : /home/aracena/fsl/bin
* FSL_DIR : /home/aracena/fsl
* FS_OVERRIDE : 0
* FUNCTIONALS_DIR : /home/aracena/freesurfer/sessions
* GDK_BACKEND : x11
* GDMSESSION : ubuntu
* GIT_PAGER : cat
* GNOME_DESKTOP_SESSION_ID : this-is-deprecated
* GNOME_TERMINAL_SCREEN : /org/gnome/Terminal/screen/815c29a8_40cd_40a5_ab66_9d8a990e1d65
* GNOME_TERMINAL_SERVICE : :1.1462
* GPG_AGENT_INFO : /run/user/1002/gnupg/S.gpg-agent:0:1
* GSETTINGS_SCHEMA_DIR : /home/aracena/anaconda3/share/glib-2.0/schemas
* GSETTINGS_SCHEMA_DIR_CONDA_BACKUP : 
* GTK_IM_MODULE : ibus
* GTK_MODULES : gail:atk-bridge
* HOME : /home/aracena
* IM_CONFIG_PHASE : 1
* JPY_PARENT_PID : 121225
* KMP_DUPLICATE_LIB_OK : True
* KMP_INIT_AT_FORK : FALSE
* LANG : en_US.UTF-8
* LC_ADDRESS : es_CL.UTF-8
* LC_IDENTIFICATION : es_CL.UTF-8
* LC_MEASUREMENT : es_CL.UTF-8
* LC_MONETARY : es_CL.UTF-8
* LC_NAME : es_CL.UTF-8
* LC_NUMERIC : es_CL.UTF-8
* LC_PAPER : es_CL.UTF-8
* LC_TELEPHONE : es_CL.UTF-8
* LC_TIME : es_CL.UTF-8
* LD_LIBRARY_PATH : /usr/lib/mesa-diverted/x86_64-linux-gnu:/usr/lib/x86_64-linux-gnu/mesa:/usr/lib/x86_64-linux-gnu/dri:/usr/lib/x86_64-linux-gnu/gallium-pipe
* LESSCLOSE : /usr/bin/lesspipe %s %s
* LESSOPEN : | /usr/bin/lesspipe %s
* LOCAL_DIR : /home/aracena/freesurfer/local
* LOGNAME : aracena
* LS_COLORS : rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=30;41:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.webp=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:
* MATLABCMD : /home/aracena/MATLAB/R2021b/bin/glnxa64/MATLAB
* MINC_BIN_DIR : /home/aracena/freesurfer/mni/bin
* MINC_LIB_DIR : /home/aracena/freesurfer/mni/lib
* MNI_DATAPATH : /home/aracena/freesurfer/mni/data
* MNI_DIR : /home/aracena/freesurfer/mni
* MNI_PERL5LIB : /home/aracena/freesurfer/mni/share/perl5
* MPLBACKEND : module://matplotlib_inline.backend_inline
* NIPYPE_NO_ET : 1
* OLDPWD : /home/aracena/thesis_practica/tips_nipype
* OS : Linux
* PAGER : cat
* PATH : /home/aracena/MATLAB/R2021b/bin:/home/aracena/fsl/bin:/home/aracena/freesurfer/bin:/home/aracena/freesurfer/fsfast/bin:/home/aracena/freesurfer/tktools:/home/aracena/fsl/bin:/home/aracena/freesurfer/mni/bin:/home/aracena/antsbin/bin:/home/aracena/anaconda3/bin:/home/aracena/anaconda3/condabin:/home/aracena/fsl/bin:/home/aracena/.local/bin:/home/aracena/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin:/usr/local/go/bin:/opt/abin:/opt/abin
* PERL5LIB : /home/aracena/freesurfer/mni/share/perl5
* PULSE_CONFIG_PATH : /home/aracena/.config/chrome-remote-desktop/pulseaudio#0fecd1539a
* PULSE_RUNTIME_PATH : /home/aracena/.config/chrome-remote-desktop/pulseaudio#0fecd1539a
* PULSE_SINK : chrome_remote_desktop_session
* PULSE_STATE_PATH : /home/aracena/.config/chrome-remote-desktop/pulseaudio#0fecd1539a
* PWD : /home/aracena/thesis_practica/tips_nipype/iterables
* PYDEVD_USE_FRAME_EVAL : NO
* QT_ACCESSIBILITY : 1
* QT_IM_MODULE : ibus
* SESSION_MANAGER : local/daniela-MS-7760:@/tmp/.ICE-unix/65356,unix/daniela-MS-7760:/tmp/.ICE-unix/65356
* SHELL : /bin/bash
* SHLVL : 1
* SPM_PATH : /home/aracena/login/spm12/
* SSH_AGENT_LAUNCHER : gnome-keyring
* SSH_AUTH_SOCK : /run/user/1002/keyring/ssh
* SUBJECTS_DIR : /home/aracena/freesurfer/subjects
* TERM : xterm-color
* USER : aracena
* USERNAME : aracena
* VTE_VERSION : 6203
* WINDOWPATH : 2
* XAUTHORITY : /home/aracena/.Xauthority
* XDG_CONFIG_DIRS : /etc/xdg/xdg-ubuntu:/etc/xdg
* XDG_CURRENT_DESKTOP : GNOME
* XDG_DATA_DIRS : /usr/share/gnome:/usr/local/share:/usr/share:/var/lib/snapd/desktop
* XDG_MENU_PREFIX : gnome-
* XDG_RUNTIME_DIR : /run/user/1002
* XDG_SESSION_CLASS : user
* XDG_SESSION_DESKTOP : ubuntu
* XDG_SESSION_TYPE : x11
* XMODIFIERS : @im=ibus
* _ : /home/aracena/anaconda3/bin/jupyter
* _CE_CONDA : 
* _CE_M : 

