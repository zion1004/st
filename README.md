# st - Simple Terminal
My fork of st (suckless's simple terminal) with patches for my convenience.\
\
Links to st :
+ https://st.suckless.org/
+ https://git.suckless.org/st


## Patches applied
+ alpha
+ anysize
+ bold is not bright
+ boxdraw
+ clipboard
+ font2
+ scrollback


## Note
Each patch is in its own branch. The branch called custom has everything merged. \
\
While the patches are applied, no configuration has beed done other than the font size changed to 16, instead of the default that is 12. \
\
The custom branch is like a vanilla st with vanilla patches done with zero configuration (except for the font size). \
Patches applied in the custom branch :
+ alpha
+ anysize
+ bold is not bright
+ boxdraw
+ clipboard
+ font2
+ scrollback 



The branch called custom-config is the custom branch with gruvbox-light patch applied and some changes in config.def.h to suite my needs. 


## Wierd interaction
For some reason, alpha doesn't like light background color and interacts very weirdly. Works fine for black background, but not with the light beige gruvbox-light bg color. 

## Extra
`libxft-bgra (AUR) for color emoji support`
