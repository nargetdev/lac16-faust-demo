
This folder contains a little demo patch showing how to run LV2 plugins in Pd
using the `lv2plugin~` external available at:

<https://bitbucket.org/agraef/pd-lv2plugin>

To run the patch, you must install the external (as well as a few
dependencies). Please check the link above for sources and
instructions. Arch users can find the `lv2plugin~` external in the AUR
(pd-lv2plugin-git package).

The patch uses some of the faust-lv2 example plugins, so you'll have to
install these first. Some presets for the subtractive synth are included as
well (`subtractive-presets.lv2` folder), just copy the bundle to your `~/.lv2`
directory to make them work.

NB: The generic plugin GUIs (GOP subpatches) in the demo patch are
auto-generated and will be overwritten each time the patch is loaded. If you
edit these manually and want to preserve your edits, change the subpatch names
before saving the patch.