# Structure Tools

## Toggle Edit Mode

*Toggle edit mode* (Normal and Expert mode) disables the parenting of all the children of the selected *Structure* element to be able to move it without affecting the other elements.

1. Select some Structure elements
2. Click the *Toggle edit mode* button
3. You can now edit the Structure elements, moving, rotating and scaling them as you wish
4. Once you have moved the Structure as you wish, do not forget to click the *Toggle edit mode* button again (with the elements selected) to re-parent the children.

## Select Structures

Click the *Select structures* button to select all the Structures in the composition.

## Show/Hide Structures

Shows or hides all (or selected) *Structures* found in the composition.

If there is no layer selected, this will show of hide all Structures in the composition, or else it will use the layer selection.

## Edit Structures

In the edition panel, you can adjust the appearance of the Structures (Normal and Expert mode).

All changes made in this panel will affect all selected Structures and the creation of all other Structures.

- You can change the size of the Structures, either automatically, relatively to the size of the composition (small, medium and large options), or with an absolute value (custom option).
- You can change the color of the Structures: if you click on the colored label, a color picker will be shown, but you can also set your on hexadecimal color code in the text field. A random button will set a random color.  

!!! hint
    The color parameter is ignored when you create [predefined limbs](../Create-Structures) (arm, leg, etc.), but you can always change the color afterwards.

- You can pick the selected Structure appearance with the *Get* button, and set the parameters to the selection with the "Set" button.
- The "Bake Appearance" button will remove all expressions used by the Structure to set its appearance. This will improve the performance of the rig, but you will not be able to change the appearance afterwards.  

!!! note
    By default, the [Auto-Rig](../Autorig) automatically bakes the appearance of the Structures.
